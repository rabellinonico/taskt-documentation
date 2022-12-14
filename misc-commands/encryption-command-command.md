<!--TITLE: Encryption Command Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Encryption Command Command


## What does this command do?
This command handles text encryption


## When would I want to use this command?
Use this command when you want to store some data encrypted


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select Encryption Action|Select an action to take|Select from **Encrypt**, **Decrypt**||
|Supply the data or variable (ex. {someVariable})|Select or provide a variable or json array value|**Test** or **{var}**||
|Provide a Pass Phrase|Select or provide a variable or json array value|**Test** or **{var}**||
|Please select the variable to receive the encrypted data|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: EncryptionCommand
Parent Namespace: taskt.Core.Automation.Commands
