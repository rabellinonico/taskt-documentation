<!--TITLE: Activate Sheet Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Activate Sheet Command


## What does this command do?
This command allows you to activate a specific worksheet in a workbook


## When would I want to use this command?
Use this command when you want to switch to a specific worksheet


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **excelInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Indicate the name of the sheet within the Workbook to activate|Specify the name of the actual sheet|Sheet1, mySheetName, [vSheet]||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExcelActivateSheetCommand
Parent Namespace: taskt.Core.Automation.Commands
