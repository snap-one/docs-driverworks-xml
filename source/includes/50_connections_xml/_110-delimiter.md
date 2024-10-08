## delimiter

`<keep_connection></keep_connection>`


### Parent

[`<connection>`][1]


The delimiter XML element, is used to specify how a network driver should break up incoming packets. NOTE: If delimiter XML is specified, data will not be sent UNTIL the delimiter is reached. If no delimiter specified, data is sent on timeout.


### Example
In the example, a single serial connection is defined using the class name of TCP. Its delimiter xml element is set to `0d`


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
		</connection>
</connections>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#connections-xml-connection