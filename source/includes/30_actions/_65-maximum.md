## maximum

`<maximum></maximum>`


### Parent

[`<param>`]()


The maximum element provides the ability to define a value that represents the highest number accepted by the Action. In the example, the minimum value of 120 will be accepted for this ranged integer type action named Ranged Integer.

### Example

```xml
~<action>~
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





