
## proxies

`<proxies></proxies>`

This element lists the number proxies used by the driver. One or more proxies may be listed.


| Attributes | Description |
| --- | --- |
| \<qty\> | Number of proxies used by the driver |
| \<proxy\> | Name of the primary proxy |
| \<proxybindingid\> | Binding id value |
| \<name\> | Model name |
| \<primary\> | Indicates if the proxy is the primary proxy used by the driver “True” or “False” |


### Example

```xml
<proxies qty="1">
    <proxy proxybindingid="5001" name="Sony BRAVIA" primary="True">tv</proxy>
</proxies>
```


