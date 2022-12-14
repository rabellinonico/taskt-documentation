<!--TITLE: Save Document As Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Save Document As Command


## What does this command do?
This command allows you to save an Word document.


## When would I want to use this command?
Use this command when you want to save a document to a file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please indicate the path of the file|Enter or Select the path to the file.|C:\temp\myfile.docx or [vWordFilePath]||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: WordSaveAsCommand
Parent Namespace: taskt.Core.Automation.Commands
