# Stage 5 - Generate Daily Report


## Description 

Function that generate “metrics.txt” and “Error_Report.csv” files using information of previous stages. 

## Inputs


The following table lists the input variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| strStageName | Control the log messages|
| strSubProcessName | Control the log messages|
| strCountMailsOut | Mails Processed Counter|
| strCountMailsWithoutAttach | Mails without attachment Counter|
| strCountMailsOut | Mails Processed Counter|
| intCountDailyBilling | Daily Billing files Counter|
| intCountOpenOrder | Open order files Counter|
| intCountPOFound | PO found in NetSuite Counter|
| intCountPONoFound | PO not found in Netsuite Counter|
| dicProperties | dictionary with in/Out paths and mails to send the final reprot |
| strMetrics | Body of the mail that sends in the end of the process |



## Outputs


The following table lists the output variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| isError | Flag to indicate if there is an error |
| strErrorMessage | Print the type of error happened |
| strErrorDescription | Save the exception messages |


## Considerations

In order to perform a test of this stage is necessary to accomplish with the next list of requirements:

- A file to process 
