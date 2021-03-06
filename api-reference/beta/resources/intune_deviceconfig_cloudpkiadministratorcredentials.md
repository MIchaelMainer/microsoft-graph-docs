﻿# cloudPkiAdministratorCredentials resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Certificate credential info
## Properties
|Property|Type|Description|
|:---|:---|:---|
|adminUserName|String|Admin User Name.|
|adminPassword|String|Admin Password.|
|authenticationCertificate|Binary|The client certificate blob.|
|authenticationCertificatePassword|String|The client certificate password.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.cloudPkiAdministratorCredentials"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.cloudPkiAdministratorCredentials",
  "adminUserName": "String",
  "adminPassword": "String",
  "authenticationCertificate": "binary",
  "authenticationCertificatePassword": "String"
}
```



