## sort\_order

`<sort_order></sort_order>`


### Parent

[`<event>`][1]


The sort order element allows for an ordered display of Events in Composer Pro. These Events can be selected by integrators configuring event based programming. In the example, the Actions will be displayed in the following order:

1. Test Event 1
2. Test Event 2
3. Test Event 3

For more information on Sorting Actions please see: [Sorting Events in Composer Pro][2]

### Example

```xml
<events>
	<event>
		<id>1</id>
		<name>Test Event 1</name>
		<description>When the NAME Static Event changes</description>
		<sort_order>1</sort_order>
	</event>
	<event>
		<id>2</id>
		<name>Test Event 2</name>
		<description>When the NAME Event 1 changes</description>
		<sort_order>2</sort_order>
	</event>
	<event>
		<id>3</id>
		<name>Test Event 2</name>
		<description>When the NAME Event 2 changes</description>
		<sort_order>3</sort_order>
	</event>
	<event>
</events>
```

[1]:	https://verbose-telegram-5004f902.pages.github.io/#events-xml-event
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#events-sorting-events-in-composerpro