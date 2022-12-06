<!--TITLE: Get Folders Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Get Folders Command


## What does this command do?
This command returns a list of folder directories from a specified location


## When would I want to use this command?
Use this command to return a list of folder directories from a specific location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the source folder|Enter or Select the path to the folder.|C:\temp\myfolder or [vTextFolderPath]||
|Assign to Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: GetFoldersCommand
Parent Namespace: taskt.Core.Automation.Commands
