
# Commands XML

`<commands></commands>`

This area contains definitions for the XML elements that are supported in the Commands section of a device driver’s driver.xml file. These Commands are specific to the device and fall outside of the commands defined by the Proxy. Defining these commands in the driver XML will make them available under the Device Specific Programming area of Composer Pro

For example, a AV Switch might have the following section in the XML of the .c4z file:

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
 <command>
   <name>ZONE2_ON</name>
   <description>ZONE2_ON</description>~
 </command>
 <command>
   <name>ZONE2_OFF</name>
   <description>~ZONE2_OFF</description>~
 </command>
</command>
```

The commands defined here fall outside of the scope found in the AV Switch area of the Proxy and Protocol Guide. Additional information regarding Commands and how they can be configured in a driver can be found here: [DriverWorks Fundamentals: Commands][1]

[1]:	https://snap-one.github.io/docs-driverworks-fundamentals/#commands