## sort\_order

`<sort_order></sort_order>`


### Parent

[`<action>`][1]


The sort order element allows for an ordered display of Actions in Composer Pro. These Actions can be selected by integrators configuring the driver. In the example, the Actions will be displayed in the following order:

1. Display Globals
2. Create Programming Project
3. Main Flood ID

For more information on Sorting Actions please see: [Actions][2]

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

[1]:	https://verbose-telegram-5004f902.pages.github.io/#actions-xml-action
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#composerpro-the-interface-into-the-sdk-actions