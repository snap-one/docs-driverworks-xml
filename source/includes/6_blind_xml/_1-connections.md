
## connections

`<connections></connections>`

### Parent

[`<devicedata>`][1]


This element defines the blind driver [connections][2] which are utilized to create the bindings within the Control4 system. Numerous connections can be defined within the `<connections>` element under the `<connection>` element.


### Example

The example to the right is an entire connections XML section from a sample Blind driver. 

```xml
<connections>
		<connection>
			<id>5001</id>
			<facing>6</facing>
			<connectionname>Blind</connectionname>
			<type>2</type>
			<consumer>False</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>False</linelevel>
			<classes>
				<class>
					<classname>BLIND</classname>
				</class>
			</classes>
		</connection>
		<connection>
			<id>2</id>
			<facing>6</facing>
			<connectionname>Up Relay</connectionname>
			<type>1</type>
			<consumer>True</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>True</linelevel>
			<classes>
				<class>
					<classname>RELAY</classname>
				</class>
			</classes>
		</connection>
		<connection>
			<id>3</id>
			<facing>6</facing>
			<connectionname>Down Relay</connectionname>
			<type>1</type>
			<consumer>True</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>True</linelevel>
			<classes>
				<class>
					<classname>RELAY</classname>
				</class>
			</classes>
		</connection>
	</connections>
</devicedata>
```

[1]:	https://control4.github.io/docs-driverworks-xml/#devicedata
[2]:	https://control4.github.io/docs-driverworks-fundamentals/#connections