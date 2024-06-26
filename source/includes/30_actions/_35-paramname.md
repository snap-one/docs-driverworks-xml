## name

`<name></name>`


### Parent

[`<param>`][1]


The parameter name element contains the ……………………

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




[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-param