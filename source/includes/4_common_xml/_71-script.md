## script

`<script></script>`


##### Parent

[`<config>`][1]


This element 


| Attributes | Description |
| --- | --- |
| file | Main scripting file used by the driver. Typically driver.lua |
| encryption | A value of 1 if the driver should be [encrypted][2]. A value of 0 if the driver should not be encrypted. | 
| jit | A value of 1 if the driver should be loaded using [luajit][3].  A value of 0 if the driver should be loaded using PUC.|



### Example

```xml
 <script file="driver.lua" encryption="2" jit="1"></script>
```

[1]:	https://control4.github.io/docs-driverworks-xml/#config
[2]:	https://control4.github.io/docs-driverworks-fundamentals/#squishlua-and-driver-encryption
[3]:	https://control4.github.io/docs-driverworks-fundamentals/#control4-os-3-and-luajit