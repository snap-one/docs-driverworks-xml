## name

`<name></name>`


### Parent

[`<action>`]()


The name element contains the name of the Action. This name is used to identify the action and is displayed  in Composer Pro.


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




