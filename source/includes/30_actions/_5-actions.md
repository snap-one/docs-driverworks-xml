## actions

`<actions></actions>`


### Parent

[`<config>`][1]


The actions element contains the driver’s XML that defines the Actions displayed under the Properties tab of Composer Pro. It is the root element for all Actions. In the example, and action named “Add and Connect Relays” is defined under the `<actions>\</actions>` XML.


### Example

```xml
<actions>
			<action>
				<name>Add and Connect Relays</name>
				<command>AddRelays</command>
				<params>
					<param>
						<name>Outlet</name>
					<type>CUSTOM_SELECT:GetPropertiesForAction</type>
					</param>
				</params>
			</action>
</actions>
```



[1]:	https://verbose-telegram-5004f902.pages.github.io/#common-xml-config