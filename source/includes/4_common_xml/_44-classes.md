## classes

`<classes></classes>`


### Parent

[`<connection>`][1]


This element is the root for one or more classes defined within the connection. If the class is TCP or UDP then there may be a ports section as seen in the example to the right. This includes the IP Port number for the network connection.



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

[1]:	https://snap-one.github.io/docs-driverworks-xml/#connection