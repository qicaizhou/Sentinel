# API call to get response

save response as api_response.json, then it can be used when creating custom table.

# create a DCE

create a empty DCE, it doesn't matter.

DCE name: DCE4QicaiDemo

# create custom table and DCR

LAW > table > create custom table(DCR based). During this process, we also create a DCR. In this time, the DCR is empty. 

Now a custom table and DCR are created.

table name: adx_ccp_demo_qicai_CL
dcr name: adx_ccp_demo_dcr

=======================================

# get json format content of DCR
Azure portal > DCR > custom DCR > json view, save as dcr.json

# get json format schema of the custom table
via API call https://learn.microsoft.com/en-us/rest/api/loganalytics/tables/get?view=rest-loganalytics-2023-09-01&tabs=HTTP, save as table_schema.json


# data connector definition
data connector UI

Refer: https://learn.microsoft.com/en-us/azure/sentinel/data-connector-ui-definitions-reference 





