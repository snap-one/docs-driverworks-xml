
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the av switch driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample AV Switch driver.

```xml
<connections>
<connection proxybindingid="5001">
    <id>1000</id>
    <facing>6</facing>
    <connectionname>Source 1</connectionname>
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
<connection proxybindingid="5001">
    <id>1001</id>
    <facing>6</facing>
    <connectionname>Source 2</connectionname>
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
<connection proxybindingid="5001">
    <id>1002</id>
    <facing>6</facing>
    <connectionname>Source 3</connectionname>
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
<connection proxybindingid="5001">
    <id>1003</id>
    <facing>6</facing>
    <connectionname>Source 4</connectionname>
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
<connection proxybindingid="5001">
    <id>1004</id>
    <facing>6</facing>
    <connectionname>Source 5</connectionname>
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
<connection proxybindingid="5001">
    <id>1005</id>
    <facing>6</facing>
    <connectionname>Source 6</connectionname>
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
<connection proxybindingid="5001">
    <id>2000</id>
    <facing>6</facing>
    <connectionname>Zone 1</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>2001</id>
    <facing>6</facing>
    <connectionname>Zone 2</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>2002</id>
    <facing>6</facing>
    <connectionname>Zone 3</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>2003</id>
    <facing>6</facing>
    <connectionname>Zone 4</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>2004</id>
    <facing>6</facing>
    <connectionname>Zone 5</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>2005</id>
    <facing>6</facing>
    <connectionname>Zone 6</connectionname>
    <type>5</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>True</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>HDMI</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3064</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 1</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3065</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 2</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3066</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 3</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3067</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 4</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3068</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 5</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3069</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 6</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3070</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 7</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>3071</id>
    <facing>1</facing>
    <connectionname>SPDIF Audio Input 8</connectionname>
    <type>6</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>DIGITAL_COAX</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4000</id>
    <facing>6</facing>
    <connectionname>Audio Output 1 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4001</id>
    <facing>6</facing>
    <connectionname>Audio Output 2 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4002</id>
    <facing>6</facing>
    <connectionname>Audio Output 3 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4003</id>
    <facing>6</facing>
    <connectionname>Audio Output 4 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4004</id>
    <facing>6</facing>
    <connectionname>Audio Output 5 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4005</id>
    <facing>6</facing>
    <connectionname>Audio Output 6 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4006</id>
    <facing>6</facing>
    <connectionname>Audio Output 7 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>4007</id>
    <facing>6</facing>
    <connectionname>Audio Output 8 (Audio Matrix)</connectionname>
    <type>6</type>
    <consumer>False</consumer>
    <audiosource>True</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>STEREO</classname>
        </class>
    </classes>
</connection>
<connection>
    <id>5001</id>
    <facing>6</facing>
    <connectionname>LEAF 6X6 HDMI MATRIX</connectionname>
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
<connection>
  <id>1</id>
  <facing>1</facing>
  <connectionname>RS-232</connectionname>
  <type>1</type>
  <consumer>True</consumer>
  <audiosource>False</audiosource>
  <videosource>False</videosource>
  <linelevel>False</linelevel>
  <classes>
    <class>
      <classname>RS_232</classname>
    </class>
  </classes>
</connection>
<connection>
    <id>6001</id>
    <facing>6</facing>
    <connectionname>Ethernet</connectionname>
    <type>4</type>
    <consumer>True</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>TCP</classname>
            <ports>
                <port>
                    <number>8105</number>
                    <auto_connect>True</auto_connect>
                    <monitor_connection>True</monitor_connection>
                    <keep_connection>True</keep_connection>
                </port>
            </ports>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7000</id>
    <facing>1</facing>
    <connectionname>Room Selection - Audio Output 1 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7001</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 2 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7002</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 3 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7003</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 4 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7004</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 5 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7005</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 6 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7006</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 7 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
<connection proxybindingid="5001">
    <id>7007</id>
    <facing>6</facing>
    <connectionname>Room Selection - Audio Output 8 (Audio Matrix)</connectionname>
    <type>7</type>
    <consumer>False</consumer>
    <audiosource>False</audiosource>
    <videosource>False</videosource>
    <linelevel>True</linelevel>
    <classes>
        <class>
            <classname>AUDIO_VOLUME</classname>
        </class>
    </classes>
</connection>
	</connections>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#devicedata
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#connections