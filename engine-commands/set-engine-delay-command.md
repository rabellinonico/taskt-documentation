<!--TITLE: Set Engine Delay Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Engine Delay Command


## What does this command do?
This command allows you to set delays between execution of commands in a running instance.


## When would I want to use this command?
Use this command when you want to change the execution speed between commands.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Set Delay between commands (in milliseconds).|Enter a specific amount of time in milliseconds (ex. to specify 8 seconds, one would enter 8000) or specify a variable containing a value.|**250** or **[vVariableSpeed]**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SetEngineDelayCommand
Parent Namespace: taskt.Core.Automation.Commands
