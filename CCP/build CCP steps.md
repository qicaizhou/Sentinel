# 1.Raise an API call to get a sample response

Save response as api_response.json, then it can be used when creating custom table.

# 2.Create a DCE

Create an empty DCE, it doesn't matter.


# 3.Create a custom table and DCR

LAW > table > create custom table(DCR based). During this process, a DCR also is created.

# 4.Get DCR properties
Azure portal > DCR > custom DCR > json view

# 5.Get custom table schema properties
Via API call https://learn.microsoft.com/en-us/rest/api/loganalytics/tables/get?view=rest-loganalytics-2023-09-01&tabs=HTTP


# 6.Create the data connector UI definition
Refer: https://learn.microsoft.com/en-us/azure/sentinel/data-connector-ui-definitions-reference 

# 7.Build a ARM template
Refer: https://learn.microsoft.com/en-us/azure/sentinel/create-codeless-connector#example-arm-template 

# 8.Deploy a custom template





