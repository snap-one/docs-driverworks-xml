
## capabilities

`<capabilities><\capabilities>`


### Parent

[`<devicedata>`][1]


This element contains the driver’s device [capabilities][2]. Capabilities are proxy dependent. Individual capabilities are defined in the [Thermostat section][3] of the DriverWorks Proxy and Protocol Guide.


### Example

Note that the example to the right has been taken from the [Thermostat Proxy Driver Development Template][4].

```xml
 <can_heat>true</can_heat>
    <can_cool>true</can_cool>
    <has_single_setpoint>false</has_single_setpoint>
    <can_do_auto>false</can_do_auto>
    <can_calibrate>true</can_calibrate>
    <can_lock_buttons>true</can_lock_buttons>
    <can_change_scale>true</can_change_scale>
    <setpoint_heat_min_f>38</setpoint_heat_min_f>
    <setpoint_heat_min_c>4</setpoint_heat_min_c>
    <setpoint_heat_max_f>89</setpoint_heat_max_f>
    <setpoint_heat_max_c>31</setpoint_heat_max_c>
    <setpoint_heat_resolution_f>1</setpoint_heat_resolution_f>
    <setpoint_heat_resolution_c>1</setpoint_heat_resolution_c>
    <setpoint_cool_min_f>42</setpoint_cool_min_f>
    <setpoint_cool_min_c>6</setpoint_cool_min_c>
    <setpoint_cool_max_f>90</setpoint_cool_max_f>
    <setpoint_cool_max_c>32</setpoint_cool_max_c>
    <setpoint_cool_resolution_f>1</setpoint_cool_resolution_f>
    <setpoint_cool_resolution_c>1</setpoint_cool_resolution_c>
    <setpoint_single_min_f>42</setpoint_single_min_f>
    <setpoint_single_min_c>6</setpoint_single_min_c>
    <setpoint_single_max_f>90</setpoint_single_max_f>
    <setpoint_single_max_c>32</setpoint_single_max_c>
    <hvac_modes>Off,Heat,Cool</hvac_modes>
    <fan_modes>Auto,Low,Medium,High</fan_modes>
    <hold_modes>Off,2 Hours,Until Next,Permanent</hold_modes>
    <hvac_states>Off,Heat,Cool,Heating,Stage 1 Cool</hvac_states>
    <fan_states>Off,On,Low,Med,Circulate</fan_states>
    <has_vacation_mode>false</has_vacation_mode>
    <has_remote_sensor>false</has_remote_sensor>
    <has_outdoor_temperature>true</has_outdoor_temperature>
    <has_connection_status>true</has_connection_status>
    <can_inc_dec_setpoints>false</can_inc_dec_setpoints>
    <current_temperature_resolution_f>1</current_temperature_resolution_f>
    <current_temperature_resolution_c>1</current_temperature_resolution_c>
    <outdoor_temperature_resolution_f>1</outdoor_temperature_resolution_f>
    <outdoor_temperature_resolution_c>1</outdoor_temperature_resolution_c>
    <can_humidify>true</can_humidify>
    <has_humidity>true</has_humidity>
    <humidity_modes>Off,Humidify,Dehumidify,Auto</humidity_modes>
    <humidity_states>Off,Humidifying,Dehumidifying</humidity_states>
    <setpoint_humidify_min>0</setpoint_humidify_min>
    <setpoint_humidify_max>100</setpoint_humidify_max>
    <setpoint_humidify_resolution>1</setpoint_humidify_resolution>
    <can_dehumidify>true</can_dehumidify>
    <setpoint_dehumidify_min>0</setpoint_dehumidify_min>
    <setpoint_dehumidify_max>100</setpoint_dehumidify_max>
    <setpoint_dehumidify_resolution>1</setpoint_dehumidify_resolution>
    <has_extras>false</has_extras>
    <scheduling>true</scheduling>
    <schedule_default>
      <schedule_day_info Entries="6" DefaultHeat="200" DefaultCool="278">
        <schedule_entry Name="Wake" Time="360" Enabled="True" />
        <schedule_entry Name="Leave" Time="480" Enabled="True" />
        <schedule_entry Name="Return" Time="1080" Enabled="True" />
        <schedule_entry Name="Sleep" Time="1320" Enabled="True" />
        <schedule_entry Name="Custom 1" Time="1380" Enabled="False" />
        <schedule_entry Name="Custom 2" Time="1380" Enabled="False" />
      </schedule_day_info>
    </schedule_default>
    <can_preset>true</can_preset>
    <can_preset_schedule>true</can_preset_schedule>
  </capabilities>
```


[1]:	[%60%3Cdevicedata%3E%60]
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#capabilities
[3]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#thermostat-capabilities
[4]:	https://github.com/snap-one/docs-driverworks/tree/master/driver_development_templates/thermostat