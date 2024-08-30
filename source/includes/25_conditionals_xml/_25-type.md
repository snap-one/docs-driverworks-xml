## type

`<type></type>`


### Parent

[`<conditional>`][1]


The type element identifies the type of Conditional defined within the `<conditional></conditional>` tag. Currently there are seven types of conditionals that can be included in your driver. They vary in complexity and each are intended to provide a specific programming opportunity. They include:

| Conditional | Description                                                                                                                                                                         |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **List**    | Asks if the current device value is equal to or not equal to the selected item in a list of values defined in the driver. These values can be numbers or strings.                   |
| **String**  | Asks if the current device value provided in string format is equal to or not equal to a string value entered in ComposerPro programming by the integrator.                         |
| **Number**  | Uses the following operators: =, !=, \\\\\\\<, \\\\\\\<=, \\\\\\\>, \\\\\\\>= to compare the current device value with an integer entered in ComposerPro programming by the dealer. |
| **Boolean** | Asks a True/False question based on True/False text provided by the driver conditional configuration.                                                                               |
| **Simple**  | Asks a true or false question.                                                                                                                                                      |
| **Room**    | Provides the ability to initiate programming based on whether or not a room selection is equal to or not equal to a room in the project.                                            |
| **Device**  | Provides the ability to initiate programming based on whether or not a device selection is equal to or not equal to a device in the project.                                        |

### Example

In the example, the Conditional type is SIMPLE

```xml
<conditionals>
			<conditional>
				<id>0</id>
				<name>SIMPLE_LIGHT_ON</name>
				<type>SIMPLE</type>
				<condition_statement>[0-SIMPLE] Light is on</condition_statement>
				<description>[0] NAME is On</description>
			</conditional>
</conditionals>
```

[1]:	https://snap-one.github.io/docs-driverworks-xml/#conditionals-xml-conditional