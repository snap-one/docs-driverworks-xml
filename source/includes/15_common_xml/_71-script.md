## script

`<script></script>`


##### Parent

[`<config>`][1]


This element


| Attributes | Description                                                                                                            |
| ---------- | ---------------------------------------------------------------------------------------------------------------------- |
| file       | Main scripting file used by the driver. Typically driver.lua                                                           |
| encryption | A value of 2 if the driver should be [encrypted][2] by Driver Packager using the current public key encryption (.c4z drivers only). A value of 0 if the driver should not be encrypted. A value of 1 indicates the legacy encryption scheme used by older drivers. |
| jit        | A value of 1 if the driver should be loaded using [luajit][3].  A value of 0 if the driver should be loaded using PUC. |



### Example

```xml
 <script file="driver.lua" encryption="2" jit="1"></script>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#common-xml-config
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#understanding-c4z-drivers-squishlua-and-driver-encryption
[3]:	https://snap-one.github.io/docs-driverworks-fundamentals/#driverworks-and-luajit-control4-os-3-and-luajit