## linelevel

`<linelevel></linelevel>`


### Parent

[`<connection>`][1]


This element indicates if this connection provides a line level source. Values are: “True” or “False”.


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