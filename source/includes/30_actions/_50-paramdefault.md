## name

`<default></default>`


### Parent

[`<param>`][1]


The parameter default element provides the ability to define a default value for parameter. This value will be displayed by default to integrators configuring the driver. 


### Example

```xml
<action>
        <action>
			<name>Display Globals</name>
			<command>DisplayGlobals</command>
			<sort_order>1</sort_order>
		</action>
		<action>
			<name>Create Programming Project</name>
			<command>CreateProgrammingProject</command>
			<sort_order>2</sort_order>
			<params>
				<param>
					<name>Main Flood ID</name>
					<type>RANGED_INTEGER</type>
					<default>4</default>
				</param>
			</params>
        </action>
</action>
```







[1]:	https://snap-one.github.io/docs-driverworks-xml/#actions-xml-param