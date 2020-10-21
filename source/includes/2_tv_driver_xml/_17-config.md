
## config

`<config><config>`

This element is the root of the driver’s config section. This section contains numerous attributes as defined below.


| Attributes | Description |
| --- | --- |
| \<power_management_method | |
| \<power_command_delay | |
| \<power_delay\> | |
| \<power_command_needed\> |  |
| \<serialsettings\> | |
| \<irsection\> | |

### Example

```xml
<config>
    <power_management_method>DiscreteCodes</power_management_method>
    <power_command_delay>0</power_command_delay>
    <power_delay>0</power_delay>
    <power_command_needed>False</power_command_needed>
    <serialsettings>9600 8 none 1 none 232</serialsettings>
    <irsection>
      <ircodes>
        <ircode>
          <id>10</id>
          <name>NUMBER_0</name>
          <transmit>PULSE</transmit>
          <repeatcount>3</repeatcount>
          <delayafter>0</delayafter>
          <pattern>0000 0066 0000 000d 0061 0018 0030 0018 0018 0018 0018 0018 0030 0018 0018 0018 0017 0018 0018 0018 0030 0018 0018 0018 0018 0018 0018 0018 0018 042e</pattern>
          <altpattern />
        </ircode>
        <ircode>
          <id>11</id>
          <name>NUMBER_1</name>
          <transmit>PULSE</transmit>
          <repeatcount>3</repeatcount>
          <delayafter>0</delayafter>
          <pattern>0000 0066 0000 000d 0061 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0018 0030 0018 0018 0018 0018 0018 0018 0018 0018 045b</pattern>
          <altpattern />
        </ircode>
</config>
```

