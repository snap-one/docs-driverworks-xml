## type

`<type></type>`


### Parent

[`<property>`][1]


The type element identifies the type of data supported by the Property. contains the name of the Property. This name is used to identify the property and is displayed  in Composer Pro.

Below is table of currently supported Property Types. For detailed information regarding each, please see: [Property Types][2].

| Property            | Description                                                                                        |
| ------------------- | -------------------------------------------------------------------------------------------------- |
| **List**            | Provides a list of selectable objects.                                                             |
| **Ranged Float**    | Provides a range of selectable floating-point or non-integer numbers.                              |
| **Ranged Integer**  | Provides a range of selectable integers.                                                           |
| **String**          | Provides a read only string.                                                                       |
| **String Password** | Provides a string which can be used as a password.                                                 |
| **Device Selector** | Provides a list of selectable drivers. See the Device Selector topic for more information.         |
| **Color Selector**  | Provides the ability to select a color. See the Color Selector topic for more information.         |
| **Dynamic List**    | Provides driver-based, dynamically updated lists. See the Dynamic List topic for more information. |
| **Link**            | Provides a link to a resource which can be used to support your driver.                            |

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