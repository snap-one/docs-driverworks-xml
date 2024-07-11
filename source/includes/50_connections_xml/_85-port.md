## port

`<port></port>`


### Parent

[`<class>`][1]


The port XML element defines a single port for the class used by the  connection. If the class is TCP or UDP then there may be a ports section. This includes the IP Port number for the network connection.

### Example

In the example, a single serial connection is defined using the class name of TCP. It has a single port defined: 8750.

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
		</connection>
</connections>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#connections-xml-connection