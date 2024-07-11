## grow

`<grow></grow>`


### Parent

[`<connection>`][1]


The grow XML element is used to define the number of bytes to increaase the size of receive buffers by when the original receiver buffer is overflowed.

### Example
In the example, a single serial connection is defined using the class name of TCP. Its grow xml element is set to 255 bytes of increase.


```

 <connections>
		<connection>
			<id>1</id>
			<facing>6</facing>
			<connectionname>Serial RS-232</connectionname>
			<type>1</type>
			<consumer>True</consumer>
			<audiosource>False</audiosource>
			<videosource>False</videosource>
			<linelevel>False</linelevel>
			<classes>
				<class>
					<classname>TCP</classname>
                    <ports>
                      <port>
                        <number>8750</number>
                      </port>
                    </ports>
				</class>
			</classes>
            <auto_connect>True</auto_connect>
            <monitor_connection>True</monitor_connection>
            <keep_connection>True</keep_connection>
            <delimiter>0d</delimiter> 
            <grow>255</grow> 
		</connection>
</connections>
```





[1]:	https://verbose-telegram-5004f902.pages.github.io/#connections-xml-connection