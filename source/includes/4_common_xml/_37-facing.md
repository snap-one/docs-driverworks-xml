## facing

`<facing></facing>`


### Parent

`<connection>`


This element is the numerical value indicating the location of the physical [connection][1] location. Values are:

- Front - 0
- Back - 1
- Top - 2
- Bottom - 3
- Left - 4
- Right - 5
- Unknown - 6


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

[1]:	https://control4.github.io/docs-driverworks-fundamentals/#connections