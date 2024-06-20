
# XML and Device Drivers


The purpose of this guide is to assist with defining the XML portion of a device or protocol driver. 

Inside of a  device driver, protocol code is written in XML and Lua which is an embedded scripting language delivered with the DriverWorks SDK. The resulting file is referred to as the “Protocol Driver”. When combined with the Proxy Driver, it provides the foundation needed to implement a 2-way device driver in the Control4 OS.

In addition to a Common XML section, the guide is organized by Proxy. You will find the Common section has XML element definitions that make up the foundation of a well formed XML component of a protocol driver. Each Proxy specific section contains XML element definitions that are most commonly found in a device class driver as well as other XML elements that you may find useful in your driver development efforts.