Step1: Visit and logon

https://learn.microsoft.com/en-us/rest/api/hybridcompute/machine-extensions/create-or-update?view=rest-hybridcompute-2024-07-10&tabs=HTTP#code-try-0

Step2: Type the required fields and body as instructed.


```json
{
   "name": "MicrosoftDnsAgent",
   "type": "Microsoft.HybridCompute/machines/extensions",
   "location": "japaneast", //replace wth region of arc vm
   "properties": {
       "autoUpgradeMinorVersion": true,
       "publisher": "Microsoft.Sentinel.AzureMonitorAgentExtensions",
       "type": "MicrosoftDnsAgent",
       "typeHandlerVersion": "1.4.6",
   }
}
```


```json
{
   "location": "southeastasia", //replace wth region of arc vm
   "properties": {
       "autoUpgradeMinorVersion": true,
       "publisher": "Microsoft.Sentinel.AzureMonitorAgentExtensions",
       "type": "AzureMonitorLinuxAgent",
       "typeHandlerVersion": "1.33.1",
   }
}

```
