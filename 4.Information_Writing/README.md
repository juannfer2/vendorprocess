# Stage 4 - Information Writing


## Description 

Function that wait that the Sales Order Page fully load, with the items table to identify if the items table is multipage, and select the “View All” option

## Inputs


The following table lists the input variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| strStageName | Control the log messages|
| strSubProcessName | Control the log messages|
| strColumnName | Column selected to write information|
| strRowNumber | Row number where the information will be written|
| strValue | Value that will be written on the selected row and column|


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
