<!--TITLE: Parse JSON Item Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Parse JSON Item Command


## What does this command do?
This command allows you to parse a JSON object into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the value or variable requiring extraction (ex. [vSomeVariable])|Select or provide a variable or text value|**Hello** or **vSomeVariable**||
|Specify a JSON extractor|Input a JSON token extractor|Select from Before Text, After Text, Between Text||
|Please select the variable to receive the extracted json|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ParseJsonCommand
Parent Namespace: taskt.Core.Automation.Commands
