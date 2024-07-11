## maximum

`<maximum></maximum>`


### Parent

[`<param>`][1]


The maximum element provides the ability to define a value that represents the highest number accepted by the Action. The minimum and maximum elements are supported in the following parameter types:

- Ranged Float
- Ranged Integer
- Track

 In the example, the minimum value of 120 will be accepted for this ranged integer type action named Ranged Integer.

### Example

```xml
<action>
			<name>Test Action with Paramters</name>
			<command>TestActionWithParamters</command>
			<params>
				<param>
					<name>RANGED_INTEGER</name>
					<type>RANGED_INTEGER</type>
					<minimum>79</minimum>
					<maximum>120</maximum>
				</param>
			</params>
		</action>
```






[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-param