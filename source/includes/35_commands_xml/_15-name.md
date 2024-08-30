## name

`<name></name>`


### Parent

[`<command>`][1]


The name element serves two purposes with regard to Command XML. First, it is used to name a command defined within the XML and that name is displayed in the Device Specific Programming in Composer Pro.

Secondly, the contents defined in the name element of the Command XML is used by the LUA function ExecuteCommand. This function must be defined in the driver’s LUA code. The first parameter that the ExecuteCommand function requires is the value defined in the name XML element. The function is then handled however needed within the ExecuteCommand Code.


### Example
In the example, a Command named SelectFavorite has been defined. SelectFavorite will be displayed in the Device Specific Programming in Composer Pro. Additionally, it will be passed as the first parameter in the LUA ExecuteCommand function defined in the driver’s LUA code.


```xml
<command>
			<name>SelectFavorite</name>
			<description>Select Favorite PARAM1 in PARAM2</description>
			<sort_order>1</sort_order>
			<params>
				<param>
					<name>Favorite</name>
					<type>CUSTOM_SELECT:GetFavoritesForProgramming</type>
			    </param>
            </params>
</command>
```





[1]:	https://snap-one.github.io/docs-driverworks-xml/#commands-xml-command