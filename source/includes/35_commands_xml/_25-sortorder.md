## sort\_order

`<sort_order></sort_order>`


### Parent

[`<command>`][1]


The sort order element is used to assign order to commands. This order refelects the manner in which the commands are displayed in Composer Pro’s programming area. 

In the example, the sort order element is used to display the command Select Channel 3 in the third spot in a list of channels. 


### Example


```xml
~<command>~
			<name>Select Channel 3</name>
			<description>Select Channel PARAM1</description>
			<sort_order>3</sort_order>
			<params>
				<param>
					<name>Channel</name>
					<type>CUSTOM_SELECT:SelectChannelParamSelectThree</type>
				</param>
			</params>
</command>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-action