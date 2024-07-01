## type

`<param></param>`


### Parent

[`<params>`][1]


The type element is used to identify which of the support Command Parameter Type are being used by the parameter. 

 The following Command Parameter Types are supported:

|                     |                                                                                                                                                                                                                               |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Device Selector** | The Device Selector command parameter type supports the Device Selector property. Device Selector allows you (as the driver developer) to display a list of devices that may be associated with the driver.                   |
| **Custom Select**   | The ability of a Proxy driver to deliver a browse-able list of related elements can be supported through the use of the CUSTOM/\\\_SELECT property.                                                                           |
| **Dynamic List**    | The Dynamic List command parameter type supports the ability to use the Dynamic List Property. This property provides ability to include driver-based, dynamically updated lists in ComposerPro’s Advanced Properties screen. |
| **LIST**            | The List command parameter type supports the ability to provide a non-dynamic list of selectable objects within the Properties tab in ComposerPro.                                                                            |
| **Ranged Float**    | The Ranged Float command parameter type supports the ability to provide a range of selectable floating-point or non-integer numbers within the Properties tab in ComposerPro.                                                 |
| **Ranged Integer**  | The Ranged Integer command parameter type supports the ability to provide a range of selectable integers within the Properties tab in ComposerPro.                                                                            |
| **String**          | The STRING command parameter type supports the ability to provide a read only string within the Properties tab in ComposerPro.                                                                                                |


In the example, the command Toggle has a params element containing the XML definition of one parameter defined within the \<param\>\</param\> element. The parameter name is Zone and uses the Command Parameter Type of DYNAMIC LIST to dynamically create a list of Zones that the command can toggle through.

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





[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-params