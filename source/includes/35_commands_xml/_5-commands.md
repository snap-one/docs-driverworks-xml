## commands

`<commands></commands>`


### Parent

[`<config>`][1]


The commands element contains the driver’s XML that defines the Commands displayed in the Device Specific Programming area of Composer Pro. It is the root element for all Commands. In the example, two commands are defined within the `<commands></commands>` XML: a command named “MAIN ZONE ON” and a command named MAIN ZONE OFF. 

### Example

```xml
<commands>
	<command>
   		<name>MAIN_ZONE_ON</name>
   		<description>MAIN_ZONE_ON</description>
 	</command>
 	<command>
   		<name>MAIN_ZONE_OFF</name>
   		<description>MAIN_ZONE_OFF</description>
 	</command>
</commands>
```



[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-config