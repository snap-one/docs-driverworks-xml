## readonly

`<readonly></readonly>`


### Parent

[`<property>`][1]


When set to True, the readonly element designates a Property as one that only displays information regarding the driver. If the property needs to provide information that is selectable, this must be set to false or omitted. 

### Example

```xml
<properties>
		<property>
			<name>Driver Version</name>
			<type>STRING</type>
			<readonly>true</readonly>
			<default>--</default>
		</property>
</properties>
```




[1]:	https://verbose-telegram-5004f902.pages.github.io/#properties-xml-property