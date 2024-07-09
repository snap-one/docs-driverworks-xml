
# Connections XML

`<connections></connections>`

Every driver within the Control4 system publishes the connections capabilities that are available for the device being controlled. These connections are utilized to create the bindings within the Control4 system. The connections to the device you are creating a driver for can be implemented using serial (RS-232) or Internet (TCP/IP) protocols.

The Connections XML defines all of the supported connections for the device. In addition to the network/communication bindings, your DriverWorks driver will have all of the other bindings necessary for your device  as long as they are correctly defined in the <connections>  XML. 

For more information regarding Connections, please see: [Connections][1]

[1]:	https://snap-one.github.io/docs-driverworks-fundamentals/#connections