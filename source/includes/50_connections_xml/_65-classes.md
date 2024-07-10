## classes

`<classes></classes>`


### Parent

[`<connection>`][1]


The hidden element is an optional tag to specify if this connection should be hidden in Composer Pro or not. This defaults to false, except for proxy bindings.

### Example

In the example, a single connection for a Thermostat is defined using an hidden value of true.  This indicates that this connection will not be displayed in Composer Pro as it is a Proxy connection. 


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





[1]:	https://verbose-telegram-5004f902.pages.github.io/#connections-xml-connection