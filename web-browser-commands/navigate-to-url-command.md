<!--TITLE: Navigate to URL Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Navigate to URL Command


## What does this command do?
This command allows you to navigate a Selenium web browser session to a given URL or resource.


## When would I want to use this command?
Use this command when you want to navigate an existing Selenium instance to a known URL or web resource


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Browser** command|**myInstance** or **seleniumInstance**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Please Enter the URL to navigate to|Enter the destination URL that you want the selenium instance to navigate to|https://mycompany.com/orders||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserNavigateURLCommand
Parent Namespace: taskt.Core.Automation.Commands
