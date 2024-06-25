## condition statement

`<condition_statement></condition_statement>`


### Parent

[`<conditional>`][1]


The conditional statement states a question being asked regarding a state of the driver. This is the statement that is shown before the condition logic. For example, the Simple Light On conditional , asks the question ‘The Light is on’. It is basically a useful statement that supports the conditional. When an integrator is viewing this driver’s conditionals in ComposerPro, they can select “The Light is on” from the list of conditionals and can ultimately initiate programming when the light is in the On state.


### Example


```xml
\<conditionals\>
			<conditional>
				<id>0</id>
				<name>SIMPLE_LIGHT_ON</name>
				<type>SIMPLE</type>
				<condition_statement> Light is on</condition_statement>
				<description>NAME is On</description>
			</conditional>
</conditionals>
```

[1]:	https://verbose-telegram-5004f902.pages.github.io/#conditionals-xml-conditional