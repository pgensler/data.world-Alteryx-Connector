# data.world-Alteryx-Connector
Connect to the data.world API with Alteryx to integrate data into your own analysis

In order to use this macro, the `.yxmc` file supplied here needs to be placed in your macro folder, which can be configured in Alteryx via:
Options->User Settings->Macros

Please note that this macro is intended for querying datasources directly on data.world with SQL or dwSQL to import into an ALteryx Workflow. Currently, it does not allow import of files which cannot be directly queried on data.world

# API Reference

Please refer to the API documentation and the SQL reference if you have issues with your query:
https://dwapi.api-docs.io/v0/intro

https://docs.data.world/tutorials/dwsql/#sql-on-dataworld

# Debugging the HTTP request from Alteryx
Fiddler 4 is the easiest way to see the response generated from the download tool if you wish to see what headers are being sent to data.world. You can download it here: https://www.telerik.com/download/fiddler


Pull requests are welcome, so do not hesitate if you would like to request changes to the macro.


