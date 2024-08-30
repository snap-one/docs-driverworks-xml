## auto\_connect

`<auto_connect></auto_connect>`


### Parent

[`<connection>`][1]


The auto\_connect  XML element, when set to True,  creates an Auto Connect for this socket. This socket will be created and connected when the driver is started.

### Example
In the example, a single serial connection is defined using the class name of TCP. Its auto\_connect xml element is set to True.

```xml
<connections>
 <connections>
		<connection>
			<id>1</id>
			<facing>6</facing>
			<connectionname>Serial RS-232</connectionname>
			<type>1</type>
			<consumer>True</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>False</linelevel>
			<classes>
				<class>
					<classname>TCP</classname>
                    <ports>
                      <port>
                        <number>8750</number>
                      </port>
                    </ports>
				</class>
			</classes>
            <auto_connect>True</auto_connect>
		</connection>
</connections>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-connection