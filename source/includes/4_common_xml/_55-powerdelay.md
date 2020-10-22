## power delay

`<power_delay></power_delay>`


### Parent

[`<config>`][1]


This element 


### Example

The example to the right is a \<config\> XML section from a sample TV driver.  If provides numerous example of  XML structure that may be found in a driver written using the TV Proxy.

```xml
<config>
    <power_management_method>DiscreteCodes</power_management_method>
    <power_command_delay>0</power_command_delay>
    <power_delay>0</power_delay>
    <power_command_needed>False</power_command_needed>
    <serialsettings>9600 8 odd 1 none</serialsettings>
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

[1]:	https://control4.github.io/docs-driverworks-xml/#config