<!--TITLE: Export To PDF Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Export To PDF Command


## What does this command do?
This command allows you to export a Word document to a PDF.


## When would I want to use this command?
Use this command when you want to save a document to a PDF.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please indicate the path of the new pdf|Enter or Select the path to the file.|C:\temp\myfile.pdf or [vWordPDFFilePath]||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: WordExportToPDFCommand
Parent Namespace: taskt.Core.Automation.Commands
