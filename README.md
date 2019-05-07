# ![LOGO](logo.png) KeyVaultManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the KeyVaultManagementClient API (version 2018-02-14-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/keyvault-secrets/2018-02-14-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:15+03:00

## API Description

The Azure management API provides a RESTful set of web services that interact with Azure Key Vault.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### The List operation gets information about the secrets in a vault.  NOTE: This API is intended for internal use in ARM deployments. Users should use the data-plane REST service for interaction with vault secrets.

*Tags:* `Secrets`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the vault belongs.
* `vaultName` - _required_ - The name of the vault.
* `$top` - _optional_ - Maximum number of results to return.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified secret.  NOTE: This API is intended for internal use in ARM deployments. Users should use the data-plane REST service for interaction with vault secrets.

*Tags:* `Secrets`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the vault belongs.
* `vaultName` - _required_ - The name of the vault.
* `secretName` - _required_ - The name of the secret.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update a secret in the specified subscription.  NOTE: This API is intended for internal use in ARM deployments.  Users should use the data-plane REST service for interaction with vault secrets.

*Tags:* `Secrets`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the vault belongs.
* `vaultName` - _required_ - Name of the vault
* `secretName` - _required_ - Name of the secret
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a secret in a key vault in the specified subscription.  NOTE: This API is intended for internal use in ARM deployments. Users should use the data-plane REST service for interaction with vault secrets.

*Tags:* `Secrets`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the vault belongs.
* `vaultName` - _required_ - Name of the vault
* `secretName` - _required_ - Name of the secret
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-keyvault-secrets-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
