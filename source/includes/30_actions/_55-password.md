## password

`<default></default>`


### Parent

[`<param>`][1]


The password element supports the ability to activate (true) the use of a password field for the Action. The only significance to the use of this field includes the ability to hide the characters that are entered into the Password field in Composer Pro. Note that while the string entered for this action is not logged, the use of this element does not include any type of encryption. A driver must be encrypted to protect the string value required here.


### Example

```xml
<action>
			<name>Allow Execute</name>
			<command>AllowExecute</command>
			<params>
				<param>
					<name>Password</name>
					<type>STRING</type>
					<password>true</password>
				</param>
			</params>
</action>
```








[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-param