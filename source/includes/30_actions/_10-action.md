## action

`<action></action>`


### Parent

[`<actions>`][1]


The property element contains the driver’s XML that defines an individual Action displayed in Composer Pro.


### Example

```xml
<actions>
			<action>
				<name>Add and Connect Relays</name>
				<command>AddRelays</command>
				<params>
					<param>
						<name>Outlet</name>
					<type>CUSTOM_SELECT:GetPropertiesForAction</type>
					</param>
				</params>
			</action>
</actions>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#actions-xml-actions