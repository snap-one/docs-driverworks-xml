
## proxies

`<proxies></proxies>`


### Parent

`<devicedata>`


This element lists the number proxies used by the driver. One or more proxies may be defined. Proxies are defined within the \<proxies\> element in the \<proxy\> element.


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
    <proxy proxybindingid="5001" name="Control4 TV" primary="True">tv</proxy>
</proxies>
```


