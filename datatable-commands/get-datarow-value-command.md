<!--TITLE: Get DataRow Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get DataRow Value Command


## What does this command do?
This command allows you to get a DataRow Value from a DataTable


## When would I want to use this command?
Use this command when you want to add a datarow to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataRow Name|Enter a existing DataRow to get Values from.|**myData**||
|Select value by Index or Column Name|Select whether the DataRow value should be found by index or column name|Select from **Index** or **Column Name**||
|Please enter the index of the DataRow Value|Enter a valid DataRow index value|0 or [vIndex]||
|Assign to Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: GetDataRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
