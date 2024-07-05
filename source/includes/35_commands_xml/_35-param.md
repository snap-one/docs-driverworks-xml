## param

`<param></param>`


### Parent

[`<params>`][1]


The param element contains the XML definition for a single parameter for the Command Parameter Type that the command defined in the XML will use. 

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