## command

`<command></command>`


### Parent

[`<action>`][1]


The command element contains the name of the function that has been written in the driver’s LUA code that supports the use of the Action. In the example, the Add and Connect Relays Action, relies upon a function written by the driver writer called AddRelays. When an integrator executes the Add and Connect Relays Action, it calls the AddRelays function.

Without the inclusion of a corresponding LUA function, an Action will not function.


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





[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-action