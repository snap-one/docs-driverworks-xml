## false text

`<false_text></false_text>`


### Parent

[`<conditional>`][1]


The false text element provides the ability to define text that will be displayed in Composer Pro programming if a Boolean Conditional is false.

### Example


```xml
<conditional>
			<id>3</id>
			<name>BOOL_LIGHT_ON</name>
			<type>BOOL</type>
			<condition_statement> Light is On</condition_statement>
			<description> NAME Light is On is STRING</description>
			<true_text>True</true_text>
			<false_text>False</false_text>
</conditional>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#conditionals-xml-conditional