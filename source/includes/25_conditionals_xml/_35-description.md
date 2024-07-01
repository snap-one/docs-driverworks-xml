## description

`<description></description>`


### Parent

[`<conditional>`][1]


The description element needs to contain the NAME macro. NAME is a key value that is equivalent to your driver’s unique name. Every conditional needs to include NAME. ComposerPro treats the NAME macro in your conditional XML in a way that replaces it with your driver’s unique name. The unique name is formatted by the name of the room where the driver resides followed by “-\>”, followed by the name of the driver as it is named in the project. 

For example, consider that the name of our example driver is “Living Room Lamp” and it is in the Living Room. Based on this, “Living Room-\>Living Room Lamp” will replace NAME when your conditional programming description is displayed in the conditionals window and the script actions area of ComposerPro. Using the example above, ComposerPro will display the description XML element as: “If Living Room-\>Living Room Lamp is on”.


### Example

```xml
<conditionals\>
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