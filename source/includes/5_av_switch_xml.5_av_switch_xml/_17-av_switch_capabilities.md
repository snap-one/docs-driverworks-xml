
## av switch capabilities

`<capabilities><\capabilities>`


### Parent

[`<devicedata>`][1]


This element contains the driver’s device [capabilities][2]. Capabilities are proxy dependent. Individual capabilities are defined in the [AV Switch section][3] of the DriverWorks Proxy and Protocol Guide.


### Example

Note that the example to the right has been taken from the [Thermostat Proxy Driver Development Template][4].

```xml
<capabilities\>
    <audio_consumer_count>0</audio_consumer_count>
    <audio_provider_count>0</audio_provider_count>
    <can_downclass>False</can_downclass>
    <can_switch>True</can_switch>
    <can_upclass>True</can_upclass>
    <has_audio_sense_control>False</has_audio_sense_control>
<has_discrete_balance_control>False<has_discrete_balance_control>
    <has_discrete_bass_control>False<has_discrete_bass_control>
    <has_discrete_input_select>True</has_discrete_input_select>
    <has_discrete_loudness_control>False<has_discrete_loudness_control>
    <has_discrete_mute_control>True</has_discrete_mute_control>
    <has_discrete_treble_control>False<has_discrete_treble_control>
    <has_discrete_volume_control>True<has_discrete_volume_control>
    <has_toad_input_select>False</has_toad_input_select>
    <has_toggle_loudness_control>False<has_toggle_loudness_control>
    <has_toggle_mute_control>True</has_toggle_mute_control>
    <has_up_down_balance_control>False<has_up_down_balance_control>
    <has_up_down_bass_control>False</has_up_down_bass_control>
    <has_up_down_treble_control>False<has_up_down_treble_control>
    <has_up_down_volume_control>True<has_up_down_volume_control>
    <has_video_sense_control>False</has_video_sense_control>
    <video_consumer_count>0</video_consumer_count>
    <video_provider_count>0</video_provider_count>
    <can_switch_separately>True</can_switch_separately>
    <requires_separate_switching>True<requires_separate_switching>
</capabilities>
```

[1]:	[%60%3Cdevicedata%3E%60]
[2]:	https://snap-one.github.io/docs-driverworks-fundamentals/#capabilities
[3]:	https://snap-one.github.io/docs-driverworks-proxyprotocol/#audio-video-switch-capabilities
[4]:	https://github.com/snap-one/docs-driverworks/tree/master/driver_development_templates/avswitch