# Stage 2 - Sales Order Processing


## Description 

The functions of this stage are:
- Open NetSuite HomePage
- Search PO number in NetSuite
- open the Sales Order Page, from the corresponding Purchase Order Page and then activate the Edit mode

## Inputs


The following table lists the input variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| strStageName | Control the log messages|
| strSubProcessName | Control the log messages|
| strPONumber | Control the PO number to search|




## Outputs


The following table lists the output variables that this process stage has, to perform an independent testing and better support.

| Name | Description |
| --- | ----------- |
| isError | Flag to indicate if there is an error |
| strErrorMessage | Print the type of error happened |
| strErrorDescription | Save the exception messages |
| NoResultExistOut | Flag where is not a PO in NetSUite|


## Considerations

In order to perform a test of this stage is necessary to accomplish with the next list of requirements:

- A file to process 
