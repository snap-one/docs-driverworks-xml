## multiselect

`<multiselect></multiselect>`


### Parent

[`<property>`][1]


The multiselect element provides the ability for the user to make a selection from defined items when using the Property. In the device selector property example, two items are shown when this Property is displayed in Composer Pro. The user can select from two defined `<items></items>`: pool.c4z or thermostat.c4z.


### Example

```xml
<property>
				<name>Device Multi Selector</name>
				<type>DEVICE_SELECTOR</type>
				<items>
					<item>pool.c4z</item>
					<item>thermostat.c4z</item>
				</items>
				<multiselect>true</multiselect>
				<default></default>
				<tooltip>DEVICE_SELECTOR Property Tooltip</tooltip>
</property>
```




[1]:	https://verbose-telegram-5004f902.pages.github.io/#properties-xml-property