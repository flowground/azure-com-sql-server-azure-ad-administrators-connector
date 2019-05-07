# ![LOGO](logo.png) Azure SQL Database API spec **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database API spec API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-serverAzureADAdministrators/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:11+03:00

## API Description

The Azure SQL Database management API provides a RESTful set of web services that interact with Azure SQL Database services to manage your external server administrators.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of server Administrators.

*Tags:* `ServerAdministrators`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Deletes an existing server Active Directory Administrator.

*Tags:* `ServerAdministrators`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `administratorName` - _required_ - Name of the server administrator resource.
    Possible values: activeDirectory.

### Returns an server Administrator.

*Tags:* `ServerAdministrators`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `administratorName` - _required_ - Name of the server administrator resource.
    Possible values: activeDirectory.

### Creates a new Server Active Directory Administrator or updates an existing server Active Directory Administrator.

*Tags:* `ServerAdministrators`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `administratorName` - _required_ - Name of the server administrator resource.
    Possible values: activeDirectory.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-server-azure-ad-administrators-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
