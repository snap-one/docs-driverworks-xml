
# XML Data Hierarchy

```
<devicedata>
	<copyright></copyright>
	<creator></creator>
	<name></name>
	<version></version>
	<manufacturer></manufacturer>
	<model></model>
	<created></created>
	<modified></modified>
	<small></small>
	<large></large>
	<control></control>
	<controlmethod></controlmethod>
	<auto_update></auto_update>
	<driver></driver>
	<user_defined></user_defined>
	<combo></combo>
	<capabilities></capabilities>
 <notification_attachment_provider><notification_attachment_provider>
	<notification_attachments>
		<attachment>
			<id></id>
			<type></type>
			<description></description>
			<source></source>
		</attachment>
	</notification_attachments>
	<config>
		<power_command_needed></power_command_needed>
		<documentation/>
		<script/>
		<actions>
			<action>
				<name></name>
				<command></command>
				<params>
					<param>
						<name></name>
				        <type></type>
                        <variabletype><variabletype\>
                        <minimum></minimum\>
                        <maximum></maximum\>
                        <items>
							<item></item>
						</items>
                        <multiselect></multiselect\>
						<search><search/>
                        <password></password\>
					</param>
				</params>
                <sort_order\>4\</sort_order\>
			</action>
        <actions\>
		<commands>
			<command>
				<name></name>
				<description></description>
				<sort_order></sort_order>
				<params>
					<param>
						<name></name>
						<type></type>
                        <variabletype><varibaletype/>
						<items><items/>
						  <item><item/>
						<minimum></minimum>
						<maximum></maximum>
					</param>
				</params>
			</command>
        </commands>
		<conditionals>
			<conditional>
				<id></id>
				<name></name>
				<type></type>
				<condition_statement><condition_statement>
				<description></description>
                <truetext><truetext/>
                <falsetext><falsetext/>
                <minimum><minimum/>
                <maximum><maximum/>
                <items><items/>
				  <item><item/>
			</conditional>
		</conditionals>
		<properties>
			<property>
				<name></name>
				<type></type>
				<readonly><readonly/>
                <tooltip><tooltip/>
				<default></default>
                <minimum><minimum/>
                <maximum><maximum/>
                <items><items/>
			      <item><item/>
			</property>
		<properties/>
	</config>
	<composer_categories>
      <category></category>
	</composer_categories>
	<events>
<!--		<event>
			<id>1</id>
			<name>Test Static Event</name>
			<description>When the NAME Static Event changes</description>
			<sort_order>1</sort_order>
		</event>
		<event>
			<id>2</id>
			<name>Test Event 1</name>
			<description>When the NAME Event 1 changes</description>
			<sort_order>2</sort_order>
		</event>
		<event>
			<id>3</id>
			<name>Test Event 2</name>
			<description>When the NAME Event 2 changes</description>
			<sort_order>3</sort_order>
		</event>
		<event>
			<id>4</id>
			<name>Test Event 3</name>
			<description>When the NAME Event 3 changes</description>
			<sort_order>4</sort_order>
		</event>
		<event>
			<id>5</id>
			<name>Test Event 4</name>
			<description>When the NAME Event 4 changes</description>
			<sort_order>5</sort_order>
		</event>
		<event>
			<id>6</id>
			<name>Test Event 5</name>
			<description>When the NAME Event 5 changes</description>
			<sort_order>6</sort_order>
		</event>
		<event>
			<id>7</id>
			<name>Test Event 10</name>
			<description>When the NAME Event 10 changes</description>
			<sort_order>7</sort_order>
		</event>
		<event>
			<id>8</id>
			<name>Test Event 11</name>
			<description>When the NAME Event 11 changes</description>
			<sort_order>8</sort_order>
		</event>
		<event>
			<id>9</id>
			<name>Test Event 12</name>
			<description>When the NAME Event 12 changes</description>
			<sort_order>9</sort_order>
		</event>
		<event>
			<id>10</id>
			<name>Test Event 13</name>
			<description>When the NAME Event 13 changes</description>
			<sort_order>10</sort_order>
		</event>
		<event>
			<id>11</id>
			<name>Test Event 20</name>
			<description>When the NAME Event 20 changes</description>
			<sort_order>11</sort_order>
		</event>
		<event>
			<id>12</id>
			<name>Test Event 211</name>
			<description>When the NAME Event 21 changes</description>
			<sort_order>12</sort_order>
		</event>
-->	
	</events>
	<connections>
<!--
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
					<classname>RS_232</classname>
				</class>
			</classes>
		</connection>
-->
<!--
		<connection>
			<id>5001</id>
			<facing>6</facing>
			<connectionname>POOL</connectionname>
			<type>2</type>
			<consumer>false</consumer>
			<audiosource>false</audiosource>
			<videosource>false</videosource>
			<linelevel>false</linelevel>
			<classes>
				<class>
					<classname>POOL</classname>
				</class>
			</classes>
		</connection>
-->
<!--	    <connection>
	      <id>5001</id>
	      <facing>6</facing>
	      <connectionname>Thermostat</connectionname>
	      <type>2</type>
	      <consumer>False</consumer>
	      <audiosource>False</audiosource>
	      <videosource>False</videosource>
	      <linelevel>False</linelevel>
	      <classes>
	        <class>
	          <classname>THERMOSTAT</classname>
	        </class>
	      </classes>
	      <hidden>True</hidden>
	    </connection>
-->
	</connections>
</devicedata>
```
