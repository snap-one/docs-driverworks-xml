## audiosource

`<audiosource></audiosource>`


### Parent

[`<connection>`][1]


The audiosource element indicates (True or False) if this connection is a source of audio. 


### Example

In the example, a single connection for a Thermostat is defined using a audiosource value of False.  This indicates that this connection is not a source of audio distributions.   

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