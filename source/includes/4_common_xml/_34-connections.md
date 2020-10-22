
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the \<connection\> element.


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
| classes | Root attribute for one or more classes defined within the connection. If the class is TCP or UDP then there may be a ports section as seen in the example to the right. This includes the IP Port number for the network connection. |


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
    <connection proxybindingid="5001" verified="False">
      <id>4000</id>
      <facing>6</facing>
      <connectionname>AUDIO OUT</connectionname>
      <type>6</type>
      <consumer>false</consumer>
      <audiosource>true</audiosource>
      <videosource>false</videosource>
      <linelevel>true</linelevel>
      <classes>
        <class>
          <classname>DIGITAL_OPTICAL</classname>
        </class>
        <class>
          <classname>STEREO</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1000</id>
      <facing>6</facing>
      <connectionname>ANTENNA</connectionname>
      <type>5</type>
      <consumer>true</consumer>
      <audiosource>false</audiosource>
      <videosource>false</videosource>
      <linelevel>true</linelevel>
      <classes>
        <class>
          <classname>RF_UHF_VHF</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1020</id>
      <facing>6</facing>
      <connectionname>CABLE</connectionname>
      <type>5</type>
      <consumer>true</consumer>
      <audiosource>false</audiosource>
      <videosource>false</videosource>
      <linelevel>true</linelevel>
      <classes>
        <class>
          <classname>RF_CABLE</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1001</id>
      <facing>6</facing>
      <connectionname>HDMI 1</connectionname>
      <type>5</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>HDMI</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1002</id>
      <facing>6</facing>
      <connectionname>HDMI 2</connectionname>
      <type>5</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>HDMI</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1003</id>
      <facing>6</facing>
      <connectionname>HDMI 3</connectionname>
      <type>5</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>HDMI</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1004</id>
      <facing>6</facing>
      <connectionname>HDMI 4</connectionname>
      <type>5</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>HDMI</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>1005</id>
      <facing>6</facing>
      <connectionname>Video1 (Composite)</connectionname>
      <type>5</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>COMPOSITE</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001" verified="False">
      <id>3005</id>
      <facing>6</facing>
      <connectionname>Video1 (Composite)</connectionname>
      <type>6</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>STEREO</classname>
        </class>
      </classes>
    </connection>
    <connection proxybindingid="5001">
      <id>7000</id>
      <facing>6</facing>
      <connectionname>Room Selection - Output</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <audiosource>True</audiosource>
      <videosource>True</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>VIDEO_SELECTION</classname>
        </class>
        <class>
          <classname>AUDIO_VOLUME</classname>
        </class>
        <class>
          <classname>AUDIO_SELECTION</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>2</id>
      <facing>1</facing>
      <connectionname>IR</connectionname>
      <type>1</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>IR_OUT</classname>
        </class>
      </classes>
    </connection>
   </connections>
```



[1]:	https://control4.github.io/docs-driverworks-xml/#devicedata
[2]:	https://control4.github.io/docs-driverworks-fundamentals/#connections