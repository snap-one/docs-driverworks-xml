## conditionals

`<conditionals></conditionals>`


### Parent

[`<devicedata>`][1]


The conditionals element contains the driver’s XML that defines the Conditionals displayed in Composer Pro. It is the root element for all Conditionals. in the example, the `<conditionals></conditionals>` XML contains one conditional named SIMPLE LIGHT ON.


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



[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-devicedata