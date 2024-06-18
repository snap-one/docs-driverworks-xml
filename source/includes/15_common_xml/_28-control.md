## control

`<control></control>`


### Parent

[`<devicedata>`][1]


This element is used to define the underlying framework used by the device. Current options include av\_gen or lua\_gen. Typically, AV devices use av_gen while non-AV devices use lua\_gen.


### Examples

```xml
<control>lua_gen</control>
```

```xml
<control>av_gen</control>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#devicedata