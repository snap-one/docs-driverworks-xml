## variable\_type

`<varaible_type></varaible_type>`


### Parent

[`<param>`][1]


The variable type element provides the ability to define a value that represents the highest number accepted by the Action. In the example, the minimum value of 120 will be accepted for this ranged integer type action named Ranged Integer.

### Example

```xml
~<action>~
			<name>Test Action with Variable Paramters That is really long</name>
			<command>TestActionWithVarParamters</command>
			<params>
				<param>
					<name>Test boolean Variable Selector</name>
					<type>VARIABLE_SELECTOR</type>
					<variabletype>boolean</variabletype>
				</param>
				<param>
					<name>Test string Variable Selector</name>
					<type>VARIABLE_SELECTOR</type>
					<variabletype>string</variabletype>
				</param>
             </params>
</action>
```






[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-param