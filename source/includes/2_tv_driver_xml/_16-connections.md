
## connections

`<connections></connections>
`
This element defines the driver [connections][1] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connection>` element.


| Attributes | Description |
| --- | --- |
| connection | Root attribute for a connection |
| id | Connection id value. |
| facing | Numerical value indicating the location of the physical connection location |
| connectionname | This connection’s name. This value will be displayed in Composer pro’s Connection area. |
| type | The value indicates the type of this connection. |
| consumer | This value “True” or “False” indicates if this driver is a consumer or a provider of this connection. |
| audiosource | This value “True” or “False” indicates if this device provides a source of audio. |
| videosource | This value “True” or “False” indicates if this device provides a source of video. |
| linelevel | This value “True” or “False” indicates if this connection provides a line level source. |
| classes | Root attribute for one or more classes defined within the connection. If the class is TCP or UDP then there may be a |ports section as seen to the right. This includes the IP Port number for the network connection. |


### Example

```xml
  <connections>
    <connection>
      <id>5001</id>
      <facing>6</facing>
      <connectionname>TV</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <classes>
        <class>
          <classname>TV</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>6001</id>
      <facing>6</facing>
      <connectionname>Network Connection</connectionname>
      <type>4</type>
      <consumer>true</consumer>
      <audiosource>false</audiosource>
      <videosource>false</videosource>
      <linelevel>true</linelevel>
      <idautobind>5001</idautobind>
      <classes>
        <class>
          <classname>TCP</classname>
          <ports>
            <port>
              <number>20060</number>
              <auto_connect>False</auto_connect>
              <monitor_connection>False</monitor_connection>
              <keep_connection>False</keep_connection>
            </port>
          </ports>
          <ports>
            <port>
              <number>80</number>
              <auto_connect>False</auto_connect>
              <monitor_connection>False</monitor_connection>
              <keep_connection>False</keep_connection>
            </port>
          </ports>
        </class>
        <class>
          <classname>UDP</classname>
          <ports>
            <port>
              <number>9</number>
            </port>
          </ports>
        </class>
      </classes>
    </connection>
```



[1]:	https://control4.github.io/docs-driverworks-fundamentals/#connections