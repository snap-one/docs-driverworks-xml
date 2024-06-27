## name

`<name></name>`


### Parent

[`<command>`][1]


The name element contains the name of the Parameter Type for the Command. The following Command Parameter Types are supported:

|                     |                                                                                                                                                                                                                               |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Device Selector** | The Device Selector command parameter type supports the Device Selector property. Device Selector allows you (as the driver developer) to display a list of devices that may be associated with the driver.                   |
| **Custom Select**   | The ability of a Proxy driver to deliver a browse-able list of related elements can be supported through the use of the CUSTOM/_SELECT property.                                                                              |
| **Dynamic List**    | The Dynamic List command parameter type supports the ability to use the Dynamic List Property. This property provides ability to include driver-based, dynamically updated lists in ComposerPro’s Advanced Properties screen. |
| **LIST**            | The List command parameter type supports the ability to provide a non-dynamic list of selectable objects within the Properties tab in ComposerPro.                                                                            |
| **Ranged Float**    | The Ranged Float command parameter type supports the ability to provide a range of selectable floating-point or non-integer numbers within the Properties tab in ComposerPro.                                                 |
| **Ranged Integer**  | The Ranged Integer command parameter type supports the ability to provide a range of selectable integers within the Properties tab in ComposerPro.                                                                            |
| **String**          | The STRING command parameter type supports the ability to provide a read only string within the Properties tab in ComposerPro.                                                                                                |



### Example

In the example, 

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