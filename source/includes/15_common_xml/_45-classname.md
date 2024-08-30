## classname

`<classname></classname>`


### Parent

[`<class>`][1]


This element defines the name of a single class for a connection.


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
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#common-xml-class