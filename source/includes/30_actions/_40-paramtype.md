## type

`<type></type>`


### Parent

[`<param>`]()


The parameter type element identifies the parameter type used by the command for the Action. Supported by the parameter. Action Types include: 

| Property            | Description                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **List**            | Provides a static list of selectable objects.                                                                                                                                          |
| **Ranged Float**    | Provides a range of selectable floating-point or non-integer numbers.                                                                                                                  |
| **Ranged Integer**  | Provides a range of selectable integers.                                                                                                                                               |
| **String**          | Provides a read only string.                                                                                                                                                           |
| **String Password** | Provides a string which can be used as a password. Note that this value is not persisted.                                                                                              |
| **Device Selector** | Provides a list of selectable drivers. See the Device Selector topic for more information. For more information, please see: [Using Device Selector][2]                                |
| **Color Selector**  | Provides the ability to select a color. See the Color Selector topic for more information. For more information, please see: [Using COLOR SELECTOR.][3]                                |
| **Dynamic List**    | Provides driver-based, dynamically updated lists. See the [Dynamic List ][4]topic for more information.                                                                                |
| **Link**            | Provides a link to a resource which can be used to support your driver.                                                                                                                |
| **Label**           | Action that provides a Header Label on the Properties Screen in Composer Pro.                                                                                                          |
| **Scroll**          | Action that provides a graphical way to set an integer value on a scale on the Properties Screen in Composer Pro.                                                                      |
| **Track**           | Action that provides another option  for setting an integer value which is similar to Scroll. However, Track is more of a discrete slider control.                                     |
| **Custom Select**   | Provides a dynamically generated list of selectable objects. This property relies upon supporting LUA code to function properly. For more information, see: [Using CUSTOM SELECT ][5]. |


### Example

In the example shown, the parameter type of CUSTOM SELECT is used. CUSTOM SELECT uses a function written by the driver writer in the driver’s LUA code called GetPropertiesForAction.

When an integrator selects the Add and Connect Relays Action they are presented with a parameter list box that includes a header for a list of outlets. The box also includes the Custom Select button. When clicked, the GetPropertiesForAction function is called and it populates the Outlet list with a dynamically created list of available outlets in the project. The list is searchable and multiple items can be selected. Once the appropriate outlets are selected, selected the OK button is clicked and the AddRelays command is executed.

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







[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-device-selector-property
[3]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-color-selector-property
[4]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-dynamic-list-properties
[5]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-custom-select-property