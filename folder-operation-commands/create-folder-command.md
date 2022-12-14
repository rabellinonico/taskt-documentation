<!--TITLE: Create Folder Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Create Folder Command


## What does this command do?
This command creates a folder in a specified destination


## When would I want to use this command?
Use this command to create a folder in a specific location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the name of the new folder|Enter the name of the new folder.|myFolderName or [vFolderName]||
|Please indicate the directory for the new folder|Enter or Select the path to the directory.|C:\temp\myfolder or [vTextFolderPath]||
|Delete folder if it already exists|Specify whether the folder should be deleted first if it is already found to exist.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: CreateFolderCommand
Parent Namespace: taskt.Core.Automation.Commands
