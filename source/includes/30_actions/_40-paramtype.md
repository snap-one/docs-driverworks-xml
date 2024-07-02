## type

`<type></type>`


### Parent

[`<param>`]()


The parameter type element identifies the type of Action supported by the parameter. Action Types include: 

- STRING
- LIST
- RANGED INTEGER
- RANGED FLOAT
- COLOR SELECTOR


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






