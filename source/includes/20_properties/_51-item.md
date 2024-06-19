## item

`<item></item>`


### Parent

[`<items>`][1]


The item element provides the ability to display up to six  items in support of the Property’s use. In the list property example, six items are displayed in list format when this Property is displayed in Composer Pro. Note that each item is formed within its own `<item></item>` XML tag.


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




[1]:	https://verbose-telegram-5004f902.pages.github.io/#properties-xml-property