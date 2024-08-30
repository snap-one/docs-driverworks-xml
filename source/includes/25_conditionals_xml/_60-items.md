## items

`<items></items>`


### Parent

[`<conditional>`][1]


The items element provides the ability to define a list of items used by the [LIST][2] type Conditional. The content is defined within the `<items></items>` XML. 

In the list Conditional example, ten percentages are defined in list format when this Conditional is displayed in Composer Pro. Note that each item is formed within its own `<item></items>` XML tag.

Use of the Item element is supported in the following Conditional Types:


### Example


```xml
<conditional>
				<id>6</id>
				<name>LIST_LIGHT_LEVEL</name>
				<type>LIST</type>
				<condition_statement>[6-LIST] Light Level</condition_statement>
				<description>[6] NAME is LOGIC STRING</description>
				<items>
					<item>10%</item>
					<item>20%</item>
					<item>30%</item>
					<item>40%</item>
					<item>50%</item>
					<item>60%</item>
					<item>70%</item>
					<item>80%</item>
					<item>90%</item>
					<item>100%</item>
				</items>
			</conditional>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#conditionals-xml-conditional
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#conditionals-understanding-xml-in-a-list-type-conditional