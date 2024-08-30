
## events

`<events></eventss>`


### Parent

[`<devicedata>`][1]


The events element contains the driver’s XML that defines the Events displayed in Composer Pro programming. It is the root element for all Events. 

In the example, and Event named “Static Event” is defined under the `<events></events>` XML.


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

[1]:	https://snap-one.github.io/docs-driverworks-xml/#common-xml-devicedata