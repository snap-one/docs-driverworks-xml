## params

`<params></params>`


### Parent

[`<action>`][1]


The params contains the definition for the parameter(s) used by the Action’s Command. The parameters defined here will be displayed in a box in ComposerPro when the Action is selected.

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





[1]:	https://snap-one.github.io/docs-driverworks-xml/#actions-xml-action