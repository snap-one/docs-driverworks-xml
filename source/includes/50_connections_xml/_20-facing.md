## facing
`<facing></facing>`


### Parent

[`<connection>`][1]


This connection element  indicates which side of the device this connection is on if it is a physical connection. Values are:

| Location | Value |
| -------- | ----- |
| Front    | 0     |
| Back     | 1     |
| Top      | 2     |
| Bottom   | 3     |
| Left     | 4     |
| Right    | 5     |
| Unknown  | 6     |


### Example

In the example, a single connection for a Thermostat is defined using a facing value of 6. In this example, the physical connection location of the thermostat is unknown

```xml
<connections>
     <connection>      
	  <id>5001</id>
      <facing>6</facing>
      <connectionname>Thermostat</connectionname>
      <type>2</type>
      <consumer>False</consumer>
      <audiosource>False</audiosource>
      <videosource>False</videosource>
      <linelevel>False</linelevel>
      <classes>
        <class>
          <classname>THERMOSTAT</classname>
        </class>
      </classes>
      <hidden>True</hidden>
     </connection>
</connections>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#connections-xml-connection