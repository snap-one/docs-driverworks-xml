
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the doorstation driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample Door Station driver.

```xml
<connections>
    <connection>
      <id>5001</id>
      <facing>6</facing>
      <connectionname>DOORSTATION</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <classes>
        <class>
          <classname>DOORSTATION</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>5002</id>
      <facing>6</facing>
      <connectionname>INTERCOM</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <classes>
        <class>
          <classname>INTERCOM</classname>
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