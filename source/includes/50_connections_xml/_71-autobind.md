## autobind

`<autobind></autobind>`


### Parent

[`<class>`][1]


The autobind XML element, when set to True, marks this class as needed to be autobound. If an idautobind is provided then this class will be connected on that binding. Otherwise, it will be connected on the first connection in the project providing this class.


### Example

In the example, a single serial connection is defined using the class name of TCP. Its autobind XML element is set to True.

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
                    <autobind>True</autobind>
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





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-class