## description

`<description></description>`


### Parent

[`<command>`][1]


The description element is used to provide text that helps describe the purpose of the command that is defined in the XML. This text is displayed in Composer pro programming. In the example, the description element is used to inform the user that the Turn On command has the ability to turn on a zone which is chosen from a dynamic List to a certain level, which is also chosen from a dynamically created list.


### Example



```xml
~<command>~
			<name>Turn On</name>
			<description>Turn on PARAM1 to PARAM2</description>
			<params>
				<param>
					<name>Zone</name>
					<type>DYNAMIC_LIST</type>
				</param>
				<param>
					<name>Level</name>
					<type>DYNAMIC_LIST</type>
				</param>
			</params>
</command>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-action