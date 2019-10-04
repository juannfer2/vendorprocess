# Stage 2 - Attachment Processing


## Description 

The functions of this stage are:
- Processes the path that contains the wanted files, searches all .csv files and identify how many files are to process and extracts its name.
- Processes the information inside each file. The bot organizes the information for each file and related with each PO number inside it, with a hierarchical structure.

## Inputs


The following table lists the input variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| strStageName | Control the log messages|
| strSubProcessName | Control the log messages|
| strPathAttachments | Control where are the temporal folder with Attachments|
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
| lstAttachmentFiles | Save the name of each file|
| dtErrorReport | Datatable with the errors and exception information|
| strTempAttachmentFile | name of the file to process|
| dtAttachmentTableTemp | DataTable that contains all information of the processed file|
| dtUniquePO | DataTable that contains all PO numbers of the processed file|



## Considerations

In order to perform a test of this stage is necessary to accomplish with the next list of requirements:

- A file to process 
