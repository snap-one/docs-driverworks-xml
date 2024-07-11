## maximum

`<maximum></maximum>`


### Parent

[`<conditional>`][1]


The maximum element provides the ability to define a value that represents the highest value of a range of numbers used by a NUMBER type Conditional.  In the example, the maximum value of the range is 150.

### Example


```xml
<conditional>
				<id>4</id>
				<name>NUMBER_LIGHT_LEVEL</name>
				<type>NUMBER</type>
				<condition_statement>[4-NUMBER] Light Level</condition_statement>
				<description>[4] NAME is LOGIC INTEGER</description>
				<minimum>10</minimum>
				<maximum>150</maximum>
</conditional>
```

[1]:	https://verbose-telegram-5004f902.pages.github.io/#conditionals-xml-conditional