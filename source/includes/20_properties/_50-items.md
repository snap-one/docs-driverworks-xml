## items

`<items></items>`


### Parent

[`<property>`][1]


The items element provides the ability to define the content displayed through the `<item></item>` XML. In the list property example, six items are displayed in list format when this Property is displayed in Composer Pro. Note that each item is formed within its own `<item></items>` XML tag.

Use of the Item element is supported in the following Property Types:

[List][2]


[Dynamic List ][3]


[Device Selector][4]

### Example

```xml
<property>
			<name>Test List</name>
			<type>LIST</type>
			<readonly>false</readonly>
			<tooltip>Test List Property Tooltip</tooltip>
			<default>Item 3</default>
			<items>
				<item>Item 1</item>
				<item>Item 2</item>
				<item>Item 3</item>
				<item>Item 4</item>
				<item>Item 5</item>
				<item>Item 6</item>
			</items>
</property>
```




[1]:	https://snap-one.github.io/docs-driverworks-xml/#properties-xml-property
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk
[3]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-dynamic-list-properties
[4]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-device-selector-property