<!--TITLE: Send Keystrokes Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send Keystrokes Command


## What does this command do?
Sends keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send keystroke inputs to a window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Window name|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad**||
|Please Enter text to send|Enter the text that should be sent to the specified window.|**Hello, World!** or **[vEntryText]**|This command supports sending variables within brackets [vVariable]|
|Please Indicate if Text is Encrypted|Indicate if the text in 'TextToSend' is Encrypted.|||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SendKeysCommand
Parent Namespace: taskt.Core.Automation.Commands
