## true text

`<true_text></true_text>`


### Parent

[`<conditional>`][1]


The true text element provides the ability to define text that will be displayed in Composer Pro programming if a Boolean Conditional is True.

### Example


```xml
<conditional>
			<id>3</id>
			<name>BOOL_LIGHT_ON</name>
			<type>BOOL</type>
			<condition_statement>[3-BOOL] Light is On</condition_statement>
			<description>[3] NAME Light is On is STRING</description>
			<true_text>True</true_text>
			<false_text>False</false_text>
</conditional>
```

[1]:	https://verbose-telegram-5004f902.pages.github.io/#conditionals-xml-conditional