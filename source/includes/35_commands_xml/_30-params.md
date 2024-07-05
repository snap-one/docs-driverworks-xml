## params

`<params></params>`


### Parent

[`<command>`][1]


The params element contains the XML definition of the Command Parameter Types that the command defined in the XML will use. It is the root element for al parameters for a command. 

In the example, the command Toggle has a params element containing the XML definition of one parameter. The parameter name is Zone and uses the Command Parameter Type of DYNAMIC LIST to dynamically create a list of Zones that the command can toggle through.


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





[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-action