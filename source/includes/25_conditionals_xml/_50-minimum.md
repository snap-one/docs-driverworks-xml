## minimum

`<minimum></minimum>`


### Parent

[`<conditional>`][1]


The minimum element provides the ability to define a value that represents the lowest value of a range of numbers used by a NUMBER type Conditional.  In the example, the minimum value of the range is 10.

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

[1]:	https://snap-one.github.io/docs-driverworks-xml/#conditionals-xml-conditional