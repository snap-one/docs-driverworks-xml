## connection

`<connection></connection>`


### Parent

[`<connections>`][1]


This element defines a single driver [connection][2] which are utilized to create the bindings within the Control4 system.


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
   </connections>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#connections