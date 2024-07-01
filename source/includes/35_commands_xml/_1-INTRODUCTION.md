
# Commands XML

`<commands></commands>`

This area contains definitions for the XML elements that are supported in the Commands section of a device driver’s driver.xml file. Commands  come from the Device Proxy. For example, a AV Switch might have the following section in the XML of the .c4z file:

```xml
<commands>
 ~<command>~
   ~<name>~MAIN_ZONE_ON~</name>~
   ~<description>~MAIN_ZONE\_ON~</description>~
 ~</command>~
 ~<command>~
   ~<name>~MAIN_ZONE_OFF~</name>~
   ~<description>~MAIN\_ZONE\_OFF~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE2_ON~</name>~
   ~<description>~ZONE2\_ON~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE2_OFF~</name>~
   ~<description>~ZONE2\_OFF~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE3_ON~</name>~
   ~<description>~ZONE3\_ON~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE3_OFF~</name>~
   ~<description>~ZONE3\_OFF~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE4_ON~</name>~
   ~<description>~ZONE4\_ON~</description>~
 ~</command>~
 ~<command>~
   ~<name>~ZONE4_OFF~</name>~
   ~<description>~ZONE4\_OFF~</description>~
 ~</command>~
</command>
```


Additional information regarding Commands and how they can be configured in a driver can be found here: [DriverWorks Fundamentals: Commands][1]

[1]:	https://snap-one.github.io/docs-driverworks-fundamentals/#commands