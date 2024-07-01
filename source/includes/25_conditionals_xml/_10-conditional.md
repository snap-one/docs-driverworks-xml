## conditional

`<conditional></conditional>`


### Parent

[`<conditionals>`][1]


The conditional element contains the driver’s XML that defines an individual conditional displayed in Composer Pro. In the example, the `<conditional></conditional>` contains the XML elements that make up a conditional named SIMPLE LIGHT ON.


### Example

```xml
<conditionals>
			<conditional>
				<id>0</id>
				<name>SIMPLE_LIGHT_ON</name>
				<type>SIMPLE</type>
				<condition_statement>[0-SIMPLE] Light is on</condition_statement>
				<description>[0] NAME is On</description>
			</conditional>
</conditionals>
```



[1]:	https://verbose-telegram-5004f902.pages.github.io/#conditionals-xml-conditionals