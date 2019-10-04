# Stage 1 - Email Processing


## Description 

The functions of this stage are:
- Get unread mails from Order Confirmation inbox.
- Filters mails with attachments and selected mails with files that have the wanted structured. The bot saves the wanted files (Open order and DailyBilling) in a temporal folder.

## Inputs


The following table lists the input variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| strStageName | Control the log messages|
| strSubProcessName | Control the log messages|
| listNewCustomerMails | Save the unread mails|
| strErrorMessage | Save the exception messages|
| intCountMailsWithoutAttach | Mails without attachment Counter|


## Outputs


The following table lists the output variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| isError | Flag to indicate if there is an error |
| strErrorMessage | Print the type of error happened |
| strErrorDescription | Save the exception messages |
| dtErrorReport | datatable with the errors and exception information|

## Considerations

In order to perform a test of this stage is necessary to accomplish with the next list of requirements:

- Have an email on the inbox 
- Outlook logged 
