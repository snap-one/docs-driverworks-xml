
# XML and Device Drivers

The purpose of this guide is to assist with define the XML portion of a device or protocol driver. When this driver is added to a Control4 Automation system, device control is dictated by the functions defined in the protocol by the device manufacturer. User Interaction with the device is accomplished through system programming such as button presses and events. The UI is provided by one or possibly several of the proxies. In most instances of driver development, the driver developer will be creating a protocol driver.

Simply put, Protocols contain the definition for a specific device (the device you’re creating a driver for) and they are composed of functionality that is unique to that specific device.

Protocols are important as two similar devices may have the same functionality but utilize a very different command syntax. A protocol driver provides the device-specific information needed to communicate with the Control4 system.  Inside of your device driver, protocol code is written in XML and Lua which is an embedded scripting language delivered with the DriverWorks SDK. The resulting file is referred to as the “Protocol Driver”. When combined with the Proxy Driver, it provides the foundation needed to implement a 2-way device driver in the Control4 OS.

In addition to a Common XML section, the guide is organized by Proxy. You will find the Common section has XML element definitions that make up the foundation of a well formed XML component of a protocol driver. Each Proxy specific section contains XML element definitions that are most commonly found in a device class driver as well as other XML elements that you may find useful in your driver development efforts.