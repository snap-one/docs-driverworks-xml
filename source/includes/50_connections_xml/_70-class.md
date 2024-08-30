## class

`<classes></classes>`


### Parent

[`<classes>`][1]


The class element contains the driver’s XML that defines an individual Class needed by the connection.

### Example

In the example, a single serial connection is defined using the class name of TCP.

```xml

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
		</connection>
</connections>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-classes