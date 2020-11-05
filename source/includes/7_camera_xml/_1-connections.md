
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the blind driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample Camera driver. 

```xml
<connections>
		<connection>
			<id>5001</id>
			<facing>6</facing>
			<connectionname>Camera</connectionname>
			<type>2</type>
			<consumer>False</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>False</linelevel>
			<classes>
				<class>
					<classname>CAMERA</classname>
				</class>
			</classes>
			<hidden>True</hidden>
		</connection>

		<connection proxybindingid="5001">
			<id>6001</id>
			<facing>1</facing>
			<connectionname>Ethernet</connectionname>
			<type>4</type>
			<consumer>True</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>True</linelevel>
			<classes>
				<class>
					<classname>TCP</classname>
					<ports>
						<port>
							<number>80</number>
						</port>
					</ports>
				</class>
			</classes>
		</connection>
</connections>
```

[1]:	https://control4.github.io/docs-driverworks-xml/#devicedata
[2]:	https://control4.github.io/docs-driverworks-fundamentals/#connections