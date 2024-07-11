## name

`<classname></classname>`


### Parent

[`<class>`][1]


The name element contains the name of the Class. This name is used to identify the connection and is displayed in Composer Pro Connections area.


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




[1]:	https://verbose-telegram-5004f902.pages.github.io/#properties-xml-property