
## av switch connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the av switch driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample [AV Switch Driver Development Template][3].

```xml
 <connections>
    <connection>
      <id>1</id>
      <facing>1</facing>
      <connectionname>RS-232</connectionname>
      <type>1</type>
      <consumer>True</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>RS_232</classname>
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
    <connection>
      <id>5001</id>
      <type>2</type>
      <connectionname>AVSWITCH</connectionname>
      <consumer>False</consumer>
      <linelevel>True</linelevel>
      <classes>
        <class>
          <classname>AVSWITCH</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>6001</id>
      <facing>1</facing>
      <connectionname>Network</connectionname>
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
              <number>1000</number>
              <auto_connect>True</auto_connect>
              <monitor_connection>True</monitor_connection>
              <keep_connection>True</keep_connection>
            </port>
          </ports>
        </class>
      </classes>
    </connection>
  </connections>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#devicedata
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#connections
[3]:	https://github.com/snap-one/docs-driverworks/tree/master/driver_development_templates/avswitch