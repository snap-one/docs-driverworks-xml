## monitor\_connection

`<monitor_connection></monitor_connection>`


### Parent

[`<connection>`][1]


The monitor\_connection  XML element, when set to True,  provides monitoring of this socket. Director will periodically check the connection, if data is not returned on this socket it will be considered down.


### Example
In the example, a single serial connection is defined using the class name of TCP. Its monitor\_connect xml element is set to True.

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
		</connection>
</connections>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#connections-xml-connection