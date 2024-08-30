## type

`<param></param>`


### Parent

[`<params>`][1]


The type element is used to identify which of the support Command Parameter Type are being used by the parameter. 

 The following Command Parameter Types are supported:

|                     |                                                                                                                                                                                                                                                                                                                              |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Device Selector** | The Device Selector command parameter type supports the Device Selector property. Device Selector allows you (as the driver developer) to display a list of devices based on driver name.                                                                                                                                    |
| **Custom Select**   | The ability of a Proxy driver to deliver a browse-able list of related elements can be supported through the use of the CUSTOM SELECT property. For more information, please see: [Using Custom Select.][2]                                                                                                                  |
| **Dynamic List**    | The Dynamic List command parameter type supports the ability to use the Dynamic List Property. This property provides ability to include driver-based, dynamically updated lists in ComposerPro’s Advanced Properties screen. For more information, please see: [Using Dynamic List][3] and the [UpdatePropertyList ][4]API. |
| **LIST**            | The List command parameter type supports the ability to provide a static list of selectable objects within the Device Specific Commands tab in ComposerPro. Implementation of this command needs to be done within the driver LUA code.                                                                                      |
| **Ranged Float**    | The Ranged Float command parameter type supports the ability to provide a range of selectable floating-point or non-integer numbers within the Device Specific Commands tab in ComposerPro.                                                                                                                                  |
| **Ranged Integer**  | The Ranged Integer command parameter type supports the ability to provide a range of selectable integers within the Device Specific Commands tab in ComposerPro.                                                                                                                                                             |
| **String**          | The STRING command parameter type supports the ability to provide a string within the Device Specific Commands tab in ComposerPro.                                                                                                                                                                                           |


In the example, the command Toggle has a params element containing the XML definition of one parameter defined within the `<param></param>` element. The parameter name is Zone and uses the Command Parameter Type of DYNAMIC LIST to dynamically create a list of Zones that the command can toggle through.

### Example

```xml
<command>
			<name>Toggle</name>
			<description>Toggle PARAM1</description>
			<params>
				<param>
					<name>Zone</name>
					<type>DYNAMIC_LIST</type>
				</param>
			</params>
</command>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#commands-xml-params
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-custom-select-property
[3]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-dynamic-list-properties
[4]:	https://snap-one.github.io/docs-driverworks-api/#properties-interface-updatepropertylist