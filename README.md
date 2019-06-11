# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2017-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-eaSubscriptionMigration_API/2017-10-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:19+03:00

## API Description

Apis for customer in enterprise agreement migrate to new pricing model or rollback to legacy pricing model.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### list date to migrate to new pricing model.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

### Enterprise Agreement Customer opted to use new pricing model.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

### Enterprise Agreement Customer roll back to use legacy pricing model.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-ea-subscription-migration-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
