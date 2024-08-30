## connectionname

`<connectionname></connectionname>`


### Parent

[`<connection>`][1]


The connectionname element indicates the name of this connection. This name is used by Composer when displaying the connection.  


### Example

In the example, a single connection for a Thermostat is defined using a connectionname of “Thermostat”. This connection will be displayed as “Thermostat” in the connections area of Composer Pro.  

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





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-connection