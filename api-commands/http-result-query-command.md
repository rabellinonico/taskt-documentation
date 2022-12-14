<!--TITLE: HTTP Result Query Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# HTTP Result Query Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select variable containing HTML|Select or provide a variable from the variable list|**vSomeVariable**||
|XPath Query|Enter the XPath Query and the item will be extracted.|@//*[@id="aso_search_form_anchor"]/div/input|You can use Chrome Dev Tools to click an element and copy the XPath.|
|Apply Query Result To Variable|Data not specified|Data not specified|Data not specified|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: HTTPQueryResultCommand
Parent Namespace: taskt.Core.Automation.Commands
