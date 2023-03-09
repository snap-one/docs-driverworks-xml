
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the av switch driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from the Thermostat proxy driver development template.

```xml
<connection>
      <id>5001</id>
      <facing>6</facing>
      <connectionname>Thermostat</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <hidden>True</hidden>
      <classes>
        <class>
          <classname>THERMOSTAT</classname>
        </class>
      </classes>
    </connection>
    <connection>
      <id>7000</id>
      <facing>6</facing>
      <connectionname>Room Selection</connectionname>
      <type>7</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <classes>
        <class>
          <autobind>True</autobind>
          <classname>TEMPERATURE</classname>
        </class>
        <class>
          <autobind>True</autobind>
          <classname>TEMPERATURE_CONTROL</classname>
        </class>
      </classes>
    </connection>
  </connections>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#devicedata
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#connections