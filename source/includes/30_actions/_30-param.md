## param

`<param></param>`


### Parent

[`<params>`][1]


The param element contains the definition of a single parameter used by the Action’s Command. In the example, a parameter named outlet is used by the LUA function AddRelays to support the Add and Connect Relays Action.

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