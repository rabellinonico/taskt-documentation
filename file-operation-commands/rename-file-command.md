<!--TITLE: Rename File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Rename File Command


## What does this command do?
This command renames a file at a specified destination


## When would I want to use this command?
Use this command to rename an existing file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the source file|Enter or Select the path to the file.|C:\temp\myfile.txt or [vTextFilePath]||
|Please indicate the new file name (with extension)|Specify the new file name including the extension.|newfile.txt or newfile.png|Changing the file extension will not automatically convert files.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: RenameFileCommand
Parent Namespace: taskt.Core.Automation.Commands
