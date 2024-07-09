## connections
`<properties></properties>`


### Parent

[`<devicedata>`][1]


The connections element contains the driver’s XML that defines the Connections that are made available for the driver in Composer Pro. It is the root element for all Connections.


### Example


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





[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-devicedata