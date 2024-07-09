## auto connect

`<autoconnect></autoconnect>`


### Parent

[`<port>`][1]


This element indicates if the connection should connect automatically through this port.  Values are “True” or  “False”.


### Example

```xml
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

[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-port