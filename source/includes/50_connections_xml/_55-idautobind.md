## idautobind

`<idautobind></idautobind>`


### Parent

[`<connection>`][1]


The idautobind element is an optional tag that allows the connection to automatically connect to a connection with the defined idautobind value. The supported value range is 0 - 999.

### Example

In the example, a single connection for a Thermostat is defined using an idautobind value of 15.  This indicates that this connection will automatically connect to another defined connection with the idautobind value of 15. 


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
	  <idautobind>15</idautobind>
      <classes>
        <class>
          <classname>THERMOSTAT</classname>
        </class>
      </classes>
      <hidden>True</hidden>
     </connection>
</connections>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-connection