<!--TITLE: Automation Commands -->
<!-- SUBTITLE: an overview of available commands in taskt. -->
## Automation Commands
| Command Group   	| Command Name 	|  Command Description	|
| ---                | ---           | ---                   |
|Dictionary Commands|[Add Dictionary Item](/dictionary-commands/add-dictionary-item-command.md)|This command Adds a key and value to a existing Dictionary|
|Loop Commands|[Begin Loop](/loop-commands/begin-loop-command.md)|This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false|
|Loop Commands|[Begin Multi Loop](/loop-commands/begin-multi-loop-command.md)|This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false|
|Dictionary Commands|[Create Dictionary](/dictionary-commands/create-dictionary-command.md)|This command created a DataTable with the column names provided|
|If Commands|[Begin Multi If](/if-commands/begin-multi-if-command.md)|This command allows you to evaluate a logical statement to determine if the statement is true.|
|Folder Operation Commands|[Create Folder](/folder-operation-commands/create-folder-command.md)|This command creates a folder in a specified destination|
|Folder Operation Commands|[Delete Folder](/folder-operation-commands/delete-folder-command.md)|This command deletes a folder from a specified destination|
|Excel Commands|[Split Range By Column](/excel-commands/split-range-by-column-command.md)|This command gets text from a specified Excel Range and splits it into separate ranges by column.|
|Excel Commands|[Write Row](/excel-commands/write-row-command.md)|This command writes a DataRow to an excel sheet starting from the given cell address.|
|File Operation Commands|[File Extraction](/file-operation-commands/file-extraction-command.md)||
|DataTable Commands|[Get DataRow](/datatable-commands/get-datarow-command.md)|This command allows you to get a DataRow from a DataTable|
|DataTable Commands|[Get DataRow Count](/datatable-commands/get-datarow-count-command.md)|This command allows you to get the datarow count of a DataTable|
|DataTable Commands|[Get DataRow Value](/datatable-commands/get-datarow-value-command.md)|This command allows you to get a DataRow Value from a DataTable|
|File Operation Commands|[Get Files](/file-operation-commands/get-files-command.md)|This command returns a list of file paths from a specified location|
|Folder Operation Commands|[Get Folders](/folder-operation-commands/get-folders-command.md)|This command returns a list of folder directories from a specified location|
|Data Commands|[Get List Count](/data-commands/get-list-count-command.md)|This command allows you to get the item count of a List|
|Data Commands|[Get List Item](/data-commands/get-list-item-command.md)|This command allows you to get an item from a List|
|Folder Operation Commands|[Move/Copy Folder](/folder-operation-commands/move-copy-folder-command.md)|This command moves a folder to a specified destination|
|Loop Commands|[Next Loop](/loop-commands/next-loop-command.md)|This command enables user to break and exit from the current loop|
|Outlook Commands|[Delete Outlook Emails](/outlook-commands/delete-outlook-emails-command.md)|This command allows you to delete emails with outlook|
|Outlook Commands|[Send Outlook Email](/outlook-commands/send-outlook-email-command.md)|This command allows you to send emails with outlook|
|Regex Commands|[Get Regex Matches](/regex-commands/get-regex-matches-command.md)|This command allows you to loop through an Excel Dataset|
|Dictionary Commands|[Get Dictionary Item](/dictionary-commands/get-dictionary-item-command.md)|This command allows you to loop through an Excel Dataset|
|DataTable Commands|[Add DataRow](/datatable-commands/add-datarow-command.md)|This command allows you to add a datarow to a DataTable|
|Variable Commands|[New Variable](/variable-commands/new-variable-command.md)|This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.|
|If Commands|[Begin If](/if-commands/begin-if-command.md)|This command allows you to evaluate a logical statement to determine if the statement is true.|
|Loop Commands|[Loop Continuously](/loop-commands/loop-continuously-command.md)|This command allows you to repeat actions continuously.  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Excel Dataset](/loop-commands/loop-excel-dataset-command.md)|This command allows you to loop through an Excel Dataset|
|Loop Commands|[Loop List](/loop-commands/loop-list-command.md)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Number Of Times](/loop-commands/loop-number-of-times-command.md)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Window Commands|[Activate Window](/window-commands/activate-window-command.md)|This command activates a window and brings it to the front.|
|Misc Commands|[Get Clipboard Text](/misc-commands/get-clipboard-text-command.md)|This command allows you to get text from the clipboard.|
|Misc Commands|[Set Clipboard Text](/misc-commands/set-clipboard-text-command.md)|This command allows you to set text to the clipboard.|
|DataTable Commands|[Create DataTable](/datatable-commands/create-datatable-command.md)|This command created a DataTable with the column names provided|
|Database Commands|[Execute Database Query](/database-commands/execute-database-query-command.md)|This command allows you to perform a database query and apply the result to a dataset|
|Database Commands|[Define Database Connection](/database-commands/define-database-connection-command.md)|This command allows you to define a connection to an OLEDB data source|
|Error Handling Commands|[Catch Exception](/error-handling-commands/catch-exception-command.md)|This command allows you to define actions that should occur after encountering an error.|
|Data Commands|[Math Calculation](/data-commands/math-calculation-command.md)|This command allows you to perform a math calculation and apply it to a variable.|
|Error Handling Commands|[End Try](/error-handling-commands/end-try-command.md)|This command specifies the end of a try/catch block.|
|Excel Commands|[Append Cell](/excel-commands/append-cell-command.md)|Append input to last row of sheet into the first cell.|
|Excel Commands|[Append Row](/excel-commands/append-row-command.md)|Append to last row of sheet.|
|Excel Commands|[Get Range](/excel-commands/get-range-command.md)|This command gets text from a specified Excel Range.|
|Excel Commands|[Get Range As Datatable](/excel-commands/get-range-as-datatable-command.md)|This command gets text from a specified Excel Range and put it into a DataTable.|
|Dictionary Commands|[Load Dictionary](/dictionary-commands/load-dictionary-command.md)|This command Reads a Config file and stores it into a Dictionary.|
|Excel Commands|[Write Range](/excel-commands/write-range-command.md)|This command writes a datatable to an excel sheet starting from the given cell address.|
|Error Handling Commands|[Finally](/error-handling-commands/finally-command.md)|This command specifies execution that should occur whether or not an error occured|
|Misc Commands|[Encryption Command](/misc-commands/encryption-command-command.md)|This command handles text encryption|
|Outlook Commands|[Forward Outlook Emails](/outlook-commands/forward-outlook-emails-command.md)|This command allows you to forward emails with outlook|
|Outlook Commands|[Get Outlook Emails](/outlook-commands/get-outlook-emails-command.md)|This command allows you to get emails and attachments with outlook|
|Outlook Commands|[Move/Copy Outlook Emails](/outlook-commands/move-copy-outlook-emails-command.md)|This command allows you to move/copy emails with outlook|
|Outlook Commands|[Reply To Outlook Emails](/outlook-commands/reply-to-outlook-emails-command.md)|This command allows you to reply to emails with outlook|
|Data Commands|[Parse JSON Model](/data-commands/parse-json-model-command.md)|This command allows you to parse a JSON object into a list.|
|Remote Commands|[Remote API](/remote-commands/remote-api-command.md)|This command allows you to execute automation against another taskt Client.|
|Remote Commands|[Remote Task](/remote-commands/remote-task-command.md)|This command allows you to execute a task remotely on another taskt instance|
|DataTable Commands|[Filter DataTable](/datatable-commands/filter-datatable-command.md)|This command allows you filter a DataTable into a new Datatable|
|DataTable Commands|[Remove DataRow](/datatable-commands/remove-datarow-command.md)|This command allows you remove specified data rows.|
|Folder Operation Commands|[Rename Folder](/folder-operation-commands/rename-folder-command.md)|This command renames a folder at a specified destination|
|Web Browser Commands|[Switch Browser Frame](/web-browser-commands/switch-browser-frame-command.md)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Engine Commands|[Set Engine Preference](/engine-commands/set-engine-preference-command.md)|This command allows you to set preferences for engine behavior.|
|Error Handling Commands|[Throw Exception](/error-handling-commands/throw-exception-command.md)|This command allows you to throw an exception error.|
|Error Handling Commands|[Try](/error-handling-commands/try-command.md)|This command allows embedding commands and will automatically move to the 'catch' handler|
|Data Commands|[Parse Dataset Row](/data-commands/parse-dataset-row-command.md)|This command allows you to parse a dataset row column into a variable.|
|Engine Commands|[Show Engine Context](/engine-commands/show-engine-context-command.md)|This command allows you to show a message to the user.|
|NLG Commands|[Generate NLG Phrase](/nlg-commands/generate-nlg-phrase-command.md)|This command pauses the script for a set amount of time specified in milliseconds.|
|NLG Commands|[Set NLG Parameter](/nlg-commands/set-nlg-parameter-command.md)|This command allows you to define a NLG parameter|
|IE Browser Commands|[Find Browser](/ie-browser-commands/find-browser-command.md)|This command allows you to find and attach to an existing IE web browser session.|
|System Commands|[OS Variable](/system-commands/os-variable-command.md)|This command allows you to exclusively select a system/environment variable|
|Engine Commands|[Get BotStore Data](/engine-commands/get-botstore-data-command.md)|This command allows you to get data from tasktServer.|
|Window Commands|[Close Window](/window-commands/close-window-command.md)|This command closes an open window.|
|Misc Commands|[Add Code Comment](/misc-commands/add-code-comment-command.md)|This command allows you to add an in-line comment to the script.|
|Misc Commands|[Show Message](/misc-commands/show-message-command.md)|This command allows you to show a message to the user.|
|Data Commands|[Parse JSON Array](/data-commands/parse-json-array-command.md)|This command allows you to parse a JSON Array into a list.|
|NLG Commands|[Create NLG Instance](/nlg-commands/create-nlg-instance-command.md)|This command pauses the script for a set amount of time specified in milliseconds.|
|API Commands|[Execute REST API](/api-commands/execute-rest-api-command.md)|This command allows you to show a message to the user.|
|IE Browser Commands|[Close Browser](/ie-browser-commands/close-browser-command.md)|This command allows you to close the associated IE web browser|
|Web Browser Commands|[Close Browser](/web-browser-commands/close-browser-command.md)|This command allows you to close a Selenium web browser session.|
|IE Browser Commands|[Create Browser](/ie-browser-commands/create-browser-command.md)|This command allows you to create a new IE web browser session.|
|Web Browser Commands|[Get Browser Info](/web-browser-commands/get-browser-info-command.md)|This command allows you to navigate a Selenium web browser session to a given URL or resource.|
|Web Browser Commands|[Switch Browser Window](/web-browser-commands/switch-browser-window-command.md)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Web Browser Commands|[Create Browser](/web-browser-commands/create-browser-command.md)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Window Commands|[Move Window](/window-commands/move-window-command.md)|This command moves a window to a specified location on screen.|
|Window Commands|[Resize Window](/window-commands/resize-window-command.md)|This command resizes a window to a specified size.|
|Programs/Process Commands|[Run Custom Code](/programs-process-commands/run-custom-code-command.md)|This command allows you to run C# code from the input|
|Programs/Process Commands|[Run Script](/programs-process-commands/run-script-command.md)|This command allows you to run a script or program and wait for it to exit before proceeding.|
|IE Browser Commands|[Element Action](/ie-browser-commands/element-action-command.md)|This command allows you to manipulate (get or set) elements within the HTML document of the associated IE web browser.  Features an assisting element capture form|
|Web Browser Commands|[Element Action](/web-browser-commands/element-action-command.md)|This command allows you to close a Selenium web browser session.|
|Web Browser Commands|[Execute Script](/web-browser-commands/execute-script-command.md)|This command allows you to execute a script in a Selenium web browser session.|
|Web Browser Commands|[Navigate Back](/web-browser-commands/navigate-back-command.md)|This command allows you to navigate backwards in a Selenium web browser session.|
|Web Browser Commands|[Navigate Forward](/web-browser-commands/navigate-forward-command.md)|This command allows you to navigate forward a Selenium web browser session.|
|IE Browser Commands|[Navigate to URL](/ie-browser-commands/navigate-to-url-command.md)|This command allows you to navigate a IE web browser session to a given URL or resource.|
|Web Browser Commands|[Navigate to URL](/web-browser-commands/navigate-to-url-command.md)|This command allows you to navigate a Selenium web browser session to a given URL or resource.|
|Web Browser Commands|[Refresh](/web-browser-commands/refresh-command.md)|This command allows you to refresh a Selenium web browser session.|
|Window Commands|[Set Window State](/window-commands/set-window-state-command.md)|This command sets a target window's state.|
|Misc Commands|[Send SMTP Email](/misc-commands/send-smtp-email-command.md)|This command allows you to send email using SMTP protocol.|
|Programs/Process Commands|[Start Process](/programs-process-commands/start-process-command.md)|This command allows you to start a program or a process.|
|System Commands|[Launch Remote Desktop](/system-commands/launch-remote-desktop-command.md)|This command allows you to stop a program or a process.|
|System Commands|[Environment Variable](/system-commands/environment-variable-command.md)|This command allows you to exclusively select a system/environment variable|
|Data Commands|[Modify Variable](/data-commands/modify-variable-command.md)|This command allows you to trim a string|
|System Commands|[System Action](/system-commands/system-action-command.md)|This command allows you to perform an account action|
|Engine Commands|[Stopwatch](/engine-commands/stopwatch-command.md)|This command allows you to stop a program or a process.|
|Programs/Process Commands|[Stop Process](/programs-process-commands/stop-process-command.md)|This command allows you to stop a program or a process.|
|Variable Commands|[Add To Variable](/variable-commands/add-to-variable-command.md)|This command allows you to modify variables.|
|Variable Commands|[Set Variable Index](/variable-commands/set-variable-index-command.md)|This command allows you to modify variables.|
|Window Commands|[Wait For Window To Exist](/window-commands/wait-for-window-to-exist-command.md)|This command waits for a window to exist.|
|Input Commands|[Prompt for HTML Input](/input-commands/prompt-for-html-input-command.md)|Allows the entry of data into a web-enabled form|
|Input Commands|[Send Advanced Keystrokes](/input-commands/send-advanced-keystrokes-command.md)|Sends advanced keystrokes to a targeted window|
|Input Commands|[Send Keystrokes](/input-commands/send-keystrokes-command.md)|Sends keystrokes to a targeted window|
|Input Commands|[Send Mouse Click](/input-commands/send-mouse-click-command.md)|Simulates mouse clicks.|
|Input Commands|[Send Mouse Move](/input-commands/send-mouse-move-command.md)|Simulates mouse movements|
|Misc Commands|[Sequence Command](/misc-commands/sequence-command-command.md)|Command that groups multiple actions|
|Input Commands|[Click UI Item](/input-commands/click-ui-item-command.md)|This command clicks an item in a Thick Application window.|
|Input Commands|[Get UI Item](/input-commands/get-ui-item-command.md)|This command gets text from a Thick Application window|
|Input Commands|[UI Automation](/input-commands/ui-automation-command.md)|Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.|
|Input Commands|[Prompt for Input](/input-commands/prompt-for-input-command.md)|Sends keystrokes to a targeted window|
|Database Commands|[Run Query](/database-commands/run-query-command.md)|This command selects data from a database and applies it against a dataset|
|Data Commands|[Date Calculation](/data-commands/date-calculation-command.md)|This command allows you to build a date and apply it to a variable.|
|Loop Commands|[End Loop](/loop-commands/end-loop-command.md)|This command signifies the exit point of looped (repeated) actions.  Required for all loops.|
|Excel Commands|[Activate Sheet](/excel-commands/activate-sheet-command.md)|This command allows you to activate a specific worksheet in a workbook|
|Excel Commands|[Add Workbook](/excel-commands/add-workbook-command.md)|This command adds a new Excel Workbook.|
|Excel Commands|[Close Excel Application](/excel-commands/close-excel-application-command.md)|This command allows you to close Excel.|
|Excel Commands|[Create Excel Application](/excel-commands/create-excel-application-command.md)|This command opens the Excel Application.|
|Excel Commands|[Create Dataset](/excel-commands/create-dataset-command.md)|This command gets a range of cells and applies them against a dataset|
|Excel Commands|[Delete Cell](/excel-commands/delete-cell-command.md)|This command allows you to delete a specified cell in Excel|
|Excel Commands|[Delete Row](/excel-commands/delete-row-command.md)|This command allows you to delete a specified row in Excel|
|Excel Commands|[Get Cell](/excel-commands/get-cell-command.md)|This command gets text from a specified Excel Cell.|
|Excel Commands|[Get Last Row Index](/excel-commands/get-last-row-index-command.md)|This command allows you to find the last row in a used range in an Excel Workbook.|
|Excel Commands|[Go To Cell](/excel-commands/go-to-cell-command.md)|This command moves to a specific cell.|
|Excel Commands|[Open Workbook](/excel-commands/open-workbook-command.md)|This command opens an Excel Workbook.|
|Excel Commands|[Run Macro](/excel-commands/run-macro-command.md)|This command runs a macro.|
|Excel Commands|[Save Workbook As](/excel-commands/save-workbook-as-command.md)|This command allows you to save an Excel workbook.|
|Excel Commands|[Save Workbook](/excel-commands/save-workbook-command.md)|This command allows you to save an Excel workbook.|
|Excel Commands|[Set Cell](/excel-commands/set-cell-command.md)|This command sets the value of a cell.|
|Loop Commands|[Exit Loop](/loop-commands/exit-loop-command.md)|This command signifies the current loop should exit and resume work past the point of the current loop.|
|Data Commands|[Format Data](/data-commands/format-data-command.md)|This command allows you to apply formatting to a string|
|Data Commands|[Get Word Count](/data-commands/get-word-count-command.md)|This command allows you to parse a JSON object into a list.|
|Data Commands|[Get Word Length](/data-commands/get-word-length-command.md)|This command allows you to retrieve the length of a string or variable.|
|Data Commands|[Log Data](/data-commands/log-data-command.md)|This command logs data to files.|
|Data Commands|[Parse JSON Item](/data-commands/parse-json-item-command.md)|This command allows you to parse a JSON object into a list.|
|Data Commands|[PDF Extraction](/data-commands/pdf-extraction-command.md)||
|Data Commands|[RegEx Extraction](/data-commands/regex-extraction-command.md)|This command allows you to perform advanced string formatting using RegEx.|
|Data Commands|[Replace Text](/data-commands/replace-text-command.md)|This command allows you to replace text|
|Data Commands|[Split Text](/data-commands/split-text-command.md)|This command allows you to split a string|
|Data Commands|[Substring](/data-commands/substring-command.md)|This command allows you to trim a string|
|Data Commands|[Text Extraction](/data-commands/text-extraction-command.md)|This command allows you to perform advanced string extraction.|
|File Operation Commands|[Delete File](/file-operation-commands/delete-file-command.md)|This command deletes a file from a specified destination|
|If Commands|[Else](/if-commands/else-command.md)|This command declares the seperation between the actions based on the 'true' or 'false' condition.|
|If Commands|[End If](/if-commands/end-if-command.md)|This command signifies the exit point of If actions.  Required for all Begin Ifs.|
|Engine Commands|[Error Handling](/engine-commands/error-handling-command.md)|This command specifies what to do  after an error is encountered.|
|API Commands|[Execute DLL](/api-commands/execute-dll-command.md)|This command processes an HTML source object|
|API Commands|[HTTP Result Query](/api-commands/http-result-query-command.md)|This command processes an HTML source object|
|API Commands|[HTTP Request](/api-commands/http-request-command.md)|This command downloads the HTML source of a web page for parsing|
|Image Commands|[Image Recognition](/image-commands/image-recognition-command.md)|This command attempts to find an existing image on screen.|
|File Operation Commands|[Move/Copy File](/file-operation-commands/move-copy-file-command.md)|This command moves a file to a specified destination|
|Image Commands|[Perform OCR](/image-commands/perform-ocr-command.md)|This command allows you to covert an image file into text for parsing.|
|Engine Commands|[Pause Script](/engine-commands/pause-script-command.md)|This command pauses the script for a set amount of time specified in milliseconds.|
|Text File Commands|[Read Text File](/text-file-commands/read-text-file-command.md)|This command reads text data into a variable|
|File Operation Commands|[Rename File](/file-operation-commands/rename-file-command.md)|This command renames a file at a specified destination|
|Task Commands|[Run Task](/task-commands/run-task-command.md)|This command runs tasks.|
|Image Commands|[Take Screenshot](/image-commands/take-screenshot-command.md)|This command takes a screenshot and saves it to a location|
|Engine Commands|[Set Engine Delay](/engine-commands/set-engine-delay-command.md)|This command allows you to set delays between execution of commands in a running instance.|
|Task Commands|[Stop Current Task](/task-commands/stop-current-task-command.md)|This command stops the current task.|
|Engine Commands|[Upload BotStore Data](/engine-commands/upload-botstore-data-command.md)|This command allows you to upload data to a local tasktServer bot store|
|Variable Commands|[Set Variable](/variable-commands/set-variable-command.md)|This command allows you to modify variables.|
|File Operation Commands|[Wait For File](/file-operation-commands/wait-for-file-command.md)|This command waits for a file to exist at a specified destination|
|Word Commands|[Add Document](/word-commands/add-document-command.md)|This command adds a new Word Document.|
|Word Commands|[Append DataTable](/word-commands/append-datatable-command.md)|This command appends a datatable to a word document.|
|Word Commands|[Append Image](/word-commands/append-image-command.md)|This command appends an image to a word document.|
|Word Commands|[Append Text](/word-commands/append-text-command.md)|This command appends text to a word document.|
|Word Commands|[Close Word Application](/word-commands/close-word-application-command.md)|This command allows you to close Word.|
|Word Commands|[Create Word Application](/word-commands/create-word-application-command.md)|This command creates a Word Application.|
|Word Commands|[Export To PDF](/word-commands/export-to-pdf-command.md)|This command allows you to export a Word document to a PDF.|
|Word Commands|[Open Document](/word-commands/open-document-command.md)|This command opens an Word Document.|
|Word Commands|[Read Document](/word-commands/read-document-command.md)|This command allows you to save a Word document.|
|Word Commands|[Replace Text](/word-commands/replace-text-command.md)|This command allows you to replace text in a Word document.|
|Word Commands|[Save Document As](/word-commands/save-document-as-command.md)|This command allows you to save an Word document.|
|Word Commands|[Save Document](/word-commands/save-document-command.md)|This command allows you to save a Word document.|
|DataTable Commands|[Write DataRow Value](/datatable-commands/write-datarow-value-command.md)|This command allows you to write a Value to a DataRow|
|Text File Commands|[Write Text File](/text-file-commands/write-text-file-command.md)|This command writes specified data to a text file|
