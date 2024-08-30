## type

`<type></type>`


### Parent

[`<connection>`][1]


The type element indicates the type of this connection. Supported values include:

| Type        | Value |
| ----------- | ----- |
| Control     | 1     |
| Proxy       | 2     |
| Audio/Video | 3     |
| Nectwork    | 4     |
| Video       | 5     |
| Audion      | 6     |
| Room        | 7     |


### Example

In the example, a single connection for a Thermostat is defined using a type value of 2.  This connection is a Proxy connection type.  

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