
## capabilities

`<capabilities><\capabilities>
`

This element contains the driver’s device [capabilities][1]. Capabilities are device dependent.


### Example

Note that the example to the right has been taken from a TV driver.

```xml
<capabilities>
    <audio_consumer_count>1</audio_consumer_count>
    <audio_provider_count>1</audio_provider_count>
    <has_audio>True</has_audio>
    <has_discrete_balance_control>False</has_discrete_balance_control>
    <has_discrete_bass_control>False</has_discrete_bass_control>
    <has_discrete_channel_select>True</has_discrete_channel_select>
    <has_discrete_input_select>True</has_discrete_input_select>
    <has_discrete_loudness_control>False</has_discrete_loudness_control>
    <has_discrete_mute_control>True</has_discrete_mute_control>
    <has_discrete_treble_control>False</has_discrete_treble_control>
    <has_discrete_volume_control>True</has_discrete_volume_control>
    <has_toad_input_select>False</has_toad_input_select>
    <video_consumer_count>5</video_consumer_count>
    <video_provider_count>0</video_provider_count>
    <has_channel_up_down>True</has_channel_up_down>
    <has_toggle_loudness_control>False</has_toggle_loudness_control>
    <has_toggle_mute_control>True</has_toggle_mute_control>
    <has_up_down_balance_control>False</has_up_down_balance_control>
    <has_up_down_bass_control>False</has_up_down_bass_control>
    <has_up_down_treble_control>False</has_up_down_treble_control>
    <has_up_down_volume_control>True</has_up_down_volume_control>
    <requires_channel_after_input>False</requires_channel_after_input>
  </capabilities>
```


[1]:	https://control4.github.io/docs-driverworks-fundamentals/#capabilities