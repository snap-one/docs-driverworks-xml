## linelevel

`<linelevel></linelevel>`


### Parent

[`<connection>`][1]


The linelevel element indicates (True or False) if this connection provides a line level source. Line level signals are the highest level signals before amplification.

### Example

In the example, a single connection for a Thermostat is defined using a linelevel value of False.  This indicates that this connection does not provide a linelevel source.  

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
	  <idautobind>0</idautobind>
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