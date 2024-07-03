## name

`<name></name>`


### Parent

[`<param>`][1]


The parameter name element contains the name of the parameter used by the Action’s Command. In the example, when an integrator selects the Add and Connect Relays Action they are presented with a parameter list box that includes a header for a list of outlets. The header is “Outlet”.

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