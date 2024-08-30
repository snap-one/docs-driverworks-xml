## keep\_connection

`<keep_connection></keep_connection>`


### Parent

[`<connection>`][1]


The keep\_connection  XML element, when set to True, keeps this connection connected. This means if the connection goes down, Director will attempt to re-connect it.

### Example
In the example, a single serial connection is defined using the class name of TCP. Its keep\_connection xml element is set to True.

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
            <auto_connect>True</auto_connect>
            <monitor_connection>True</monitor_connection>
            <keep_connection>True</keep_connection>
		</connection>
</connections>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-connection