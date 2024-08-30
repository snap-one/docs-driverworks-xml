## default

`<default></default>`


### Parent

[`<property>`][1]


The default element provides the ability to define a default value for the Property that will be shown when it is viewed in Composer Pro.  In the example, the default value of 20 will be displayed for this ranged integer type property named  Ranged Integer.

### Example

```xml
<property>
			<name>Ranged Integer</name>
			<type>RANGED_INTEGER</type>
			<minimum>0</minimum>
			<maximum>100</maximum>
			<default>20</default>
</property>
```




[1]:	https://snap-one.github.io/docs-driverworks-xml/#properties-xml-property