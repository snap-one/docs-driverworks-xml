## description

`<description></description>`


### Parent

[`<event>`][1]


The description element needs to contain the NAME macro. NAME is a key value that is equivalent to your driver’s unique name. Every conditional needs to include NAME. ComposerPro treats the NAME macro in your Event XML in a way that replaces it with your driver’s unique name. The unique name is formatted by the name of the room where the driver resides followed by “-\>”, followed by the name of the driver as it is named in the project. 

For example, consider that the name of our example driver is “Living Room Lamp” and it is in the Living Room. Based on this, “Living Room-\>Living Room Lamp” will replace NAME when your Event programming description is displayed in the Event window and the script actions area of ComposerPro. Using the example, ComposerPro will display the description XML element as: “When the Living Room-\>Living Room Lamp Static Event changes”.


### Example

```xml
<events>
   <event>
		<id>0</id>
		<name>Static Event</name>
		<description>When the NAME Static Event changes</description>
		<sort_order>1</sort_order>
	</event>
</events>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#events-xml-event