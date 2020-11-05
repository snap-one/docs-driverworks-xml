
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the amplifier driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample Amplifier driver. 

```xml
<connections>
  <connection>
      <id>3000</id>
      <facing>6</facing>
      <connectionname>Global Audio Input</connectionname>
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
    <connection>
      <id>3001</id>
      <facing>6</facing>
      <connectionname>Audio Input 1</connectionname>
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
    <connection>
      <id>3002</id>
      <facing>6</facing>
      <connectionname>Audio Input 2</connectionname>
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
    <connection>
      <id>3003</id>
      <facing>6</facing>
      <connectionname>Audio Input 3</connectionname>
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
    <connection>
      <id>3004</id>
      <facing>6</facing>
      <connectionname>Audio Input 4</connectionname>
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
    <!-- #################################################################### -->
    <!--                        PROXY BINDING                                 -->
    <!-- #################################################################### -->
    <connection>
      <id>5001</id>
      <facing>6</facing>
      <connectionname>Amplifier</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AVSWITCH</classname>
        </class>
      </classes>
    </connection>
     <!-- #################################################################### -->
    <!--                  POWER CONTROL BINDING                               -->
    <!-- #################################################################### -->
    <connection>
      <id>8000</id>
      <type>1</type>
      <connectionname>12 Volt Trigger In</connectionname>
      <consumer>True</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>RELAY</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>200</id>
      <type>1</type>
      <connectionname>12 Volt Trigger Out</connectionname>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>RELAY</classname>
        </class>
      </classes>
    </connection>
    <!-- #################################################################### -->
    <!--                      SPEAKER BINDINGS                                -->
    <!-- #################################################################### -->
     <connection>
      <id>4000</id>
      <facing>6</facing>
      <connectionname>Audio Output 1</connectionname>
      <type>6</type>
      <consumer>False</consumer>
      <audiosource>True</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>SPEAKER</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>4001</id>
      <facing>6</facing>
      <connectionname>Audio Output 2</connectionname>
      <type>6</type>
      <consumer>False</consumer>
      <audiosource>True</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>SPEAKER</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>4002</id>
      <facing>6</facing>
      <connectionname>Audio Output 3</connectionname>
      <type>6</type>
      <consumer>False</consumer>
      <audiosource>True</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>SPEAKER</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>4003</id>
      <facing>6</facing>
      <connectionname>Audio Output 4</connectionname>
      <type>6</type>
      <consumer>False</consumer>
      <audiosource>True</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>SPEAKER</classname>
        </class>
      </classes>
    </connection>
    <!-- #################################################################### -->
    <!--                        ROOM BINDINGS                                 -->
    <!-- #################################################################### -->
    <connection>
      <id>7000</id>
      <facing>6</facing>
      <connectionname>Zone 1 Audio End-Point</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AUDIO_SELECTION</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>7001</id>
      <facing>6</facing>
      <connectionname>Zone 2 Audio End-Point</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AUDIO_SELECTION</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>7002</id>
      <facing>6</facing>
      <connectionname>Zone 3 Audio End-Point</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AUDIO_SELECTION</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>7003</id>
      <facing>6</facing>
      <connectionname>Zone 4 Audio End-Point</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AUDIO_SELECTION</classname>
        </class>
      </classes>
    </connection>
</connections>
```

[1]:	https://control4.github.io/docs-driverworks-xml/#devicedata
[2]:	https://control4.github.io/docs-driverworks-fundamentals/#connections