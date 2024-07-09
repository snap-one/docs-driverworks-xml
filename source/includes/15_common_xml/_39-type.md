## type

`<type></type>`


### Parent

[`<connection>`][1]


This element  contains the type of this connection. Values are:

- Control - 1
- Proxy - 2
- Audio/Video - 3
- Network - 4
- Video - 5
- Audio - 6
- Room - 7


### Example

```xml


  <connections>
   <connection>
      <id>5001</id>
      <facing>5</facing>
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

[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-connection