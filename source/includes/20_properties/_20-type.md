## type

`<type></type>`


### Parent

[`<property>`][1]


The type element identifies the type of data supported by the Property. It contains the name of the Property Type. 

Below is table of currently supported Property Types. For detailed information regarding each, please see: [Property Types][2] and [Advanced Property Types][3].

| Property            | Description                                                                                                                                                                            |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **List**            | Provides a static list of selectable objects.                                                                                                                                          |
| **Ranged Float**    | Provides a range of selectable floating-point or non-integer numbers.                                                                                                                  |
| **Ranged Integer**  | Provides a range of selectable integers.                                                                                                                                               |
| **String**          | Provides a  read only string.                                                                                                                                                          |
| **String Password** | Provides a string which can be used as a password. Note that this value is persisted.                                                                                                  |
| **Device Selector** | Provides a list of selectable drivers. See the Device Selector topic for more information. For more information, please see: [Using Device Selector][4]                                |
| **Color Selector**  | Provides the ability to select a color. See the Color Selector topic for more information. For more information, please see: [Using COLOR SELECTOR.][5]                                |
| **Dynamic List**    | Provides driver-based, dynamically updated lists. See the [Dynamic List][6] topic for more information.                                                                                |
| **Link**            | Provides a link to a resource which can be used to support your driver.                                                                                                                |
| **Label**           | Advanced Property that provides a Header Label on the Properties Screen in Composer Pro.                                                                                               |
| **Scroll**          | Advanced Property that provides a graphical way to set an integer value on a scale on the Properties Screen in Composer Pro.                                                           |
| **Track**           | Advanced Property that provides another option  for setting an integer value which is similar to Scroll. However, Track is more of a discrete slider control.                          |
| **Custom Select**   | Provides a dynamically generated list of selectable objects. This property relies upon supporting LUA code to function properly. For more information, see: [Using CUSTOM SELECT ][7]. |

### Example

```xml
<properties>
		<property>
			<name>Driver Version</name>
			<type>STRING</type>
			<readonly>true</readonly>
			<default>--</default>
		</property>
</properties>
```




[1]:	https://verbose-telegram-5004f902.pages.github.io/#properties-xml-property
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk
[3]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-advanced-properties
[4]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-device-selector-property
[5]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-color-selector-property
[6]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-dynamic-list-properties
[7]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-using-the-custom-select-property