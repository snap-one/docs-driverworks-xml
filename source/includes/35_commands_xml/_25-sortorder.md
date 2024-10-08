## sort\_order

`<sort_order></sort_order>`


### Parent

[`<command>`][1]


The sort order element is used to assign order to commands. This order reflects the manner in which the commands are displayed in Composer Pro’s programming area. For more information, please see: [Sorting Commands.][2]

In the example, the sort order element is used to display the command Select Channel 3 in the third spot in a list of channels. 


### Example


```xml
<command>
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





[1]:	https://snap-one.github.io/docs-driverworks-xml/#commands-xml-command
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#commands-sorting-commands-in-composerpro