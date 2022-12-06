<!--TITLE: Modify Variable Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Modify Variable Command


## What does this command do?
This command allows you to trim a string


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a variable or text to modify|Select or provide a variable from the variable list|**vSomeVariable**||
|Select the case type|Indicate if only so many characters should be kept|-1 to keep remainder, 1 for 1 position after start index, etc.||
|Please select the variable to receive the changes|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ModifyVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/09/22 03:57 


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)