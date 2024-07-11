## consumer

`<consumer></consumer>`


### Parent

[`<connection>`][1]


The consumer element indicates (True or False) if this connection is the consumer (or a provider) for the connection.


### Example

In the example, a single connection for a Thermostat is defined using a consumer value of False.  This connection is not on the receiving end of a provider/consumer connection.   

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