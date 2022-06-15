
## proxy

`<proxy></proxy>`


### Parent

[`<proxies>`][1]


This element is used to define a proxy used by the driver.

| Attributes | Description |
| --- | --- |
| \<proxybindingid\> | Binding id value |
| \<name\> | Model name |
| \<primary\> | Indicates if the proxy is the primary proxy used by the driver “True” or “False” |


### Example

```xml
<proxies qty="1">
    <proxy proxybindingid="5001" name="Control4 TV" primary="True">tv</proxy>
</proxies>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#proxies