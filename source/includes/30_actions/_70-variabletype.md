## variable\_type

`<varaible_type></varaible_type>`


### Parent

[`<param>`][1]

The variable type element is only used with the `VARIABLE_SELECTOR` parameter type. The Variable Selector parameter type will return a list of a type of variable found within the project. The variable type element is used to define the type of variable that will be returned. Supported variable types include:

- boolean
- string
- number
- float
- device
- media
- user
- room

In the example, the Action named: Test Action with Parameters will return all of the boolean and string variables found in the project. An integrator can then select the desired variable and it will be placed within the Action.


### Example

```xml
<action>
			<name>Test Action with Variable Paramters</name>
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