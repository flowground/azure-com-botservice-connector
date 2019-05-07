# ![LOGO](logo.png) Azure Bot Service **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Bot Service API (version 2018-07-12).

Generated from: https://api.apis.guru/v2/specs/azure.com/botservice/2018-07-12/swagger.json<br/>
Generated at: 2019-05-07T17:37:42+03:00

## API Description

Azure Bot Service is a platform for creating smart conversational agents.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Check whether an Enterprise Channel name is available.

*Tags:* `Enterprise Channel`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Check whether a bot name is available.

*Tags:* `Bot`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available BotService operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Returns all the resources of a particular type belonging to a subscription.

*Tags:* `Bot`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Lists the available Service Providers for creating Connection Settings

*Tags:* `ListServiceProviders`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns all the resources of a particular type belonging to a resource group

*Tags:* `Bot`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes a Bot Service from the resource group.

*Tags:* `Bot`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns a BotService specified by the parameters.

*Tags:* `Bot`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates a Bot Service

*Tags:* `Bot`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Creates a Bot Service. Bot Service is a resource group wide resource type.

*Tags:* `Bot`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Deletes a Connection Setting registration for a Bot Service

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `connectionName` - _required_ - The name of the Bot Service Connection Setting resource
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Get a Connection Setting registration for a Bot Service

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `connectionName` - _required_ - The name of the Bot Service Connection Setting resource
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates a Connection Setting registration for a Bot Service

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `connectionName` - _required_ - The name of the Bot Service Connection Setting resource
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Register a new Auth Connection for a Bot Service

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `connectionName` - _required_ - The name of the Bot Service Connection Setting resource
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Get a Connection Setting registration for a Bot Service

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `connectionName` - _required_ - The name of the Bot Service Connection Setting resource
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns all the Channel registrations of a particular BotService resource

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes a Channel registration from a Bot Service

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `channelName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns a BotService Channel registration specified by the parameters.

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `channelName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates a Channel registration for a Bot Service

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `channelName` - _required_ - The name of the Channel resource.
    Possible values: FacebookChannel, EmailChannel, KikChannel, TelegramChannel, SlackChannel, MsTeamsChannel, SkypeChannel, WebChatChannel, DirectLineChannel, SmsChannel.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Creates a Channel registration for a Bot Service

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `channelName` - _required_ - The name of the Channel resource.
    Possible values: FacebookChannel, EmailChannel, KikChannel, TelegramChannel, SlackChannel, MsTeamsChannel, SkypeChannel, WebChatChannel, DirectLineChannel, SmsChannel.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Lists a Channel registration for a Bot Service including secrets

*Tags:* `Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `channelName` - _required_ - The name of the Channel resource.
    Possible values: FacebookChannel, EmailChannel, KikChannel, TelegramChannel, SlackChannel, MsTeamsChannel, SkypeChannel, WebChatChannel, DirectLineChannel, SmsChannel.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns all the Connection Settings registered to a particular BotService resource

*Tags:* `BotConnection`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Returns all the resources of a particular type belonging to a resource group.

*Tags:* `Enterprise Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes an Enterprise Channel from the resource group

*Tags:* `Enterprise Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns an Enterprise Channel specified by the parameters.

*Tags:* `Enterprise Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates an Enterprise Channel.

*Tags:* `Enterprise Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

### Creates an Enterprise Channel.

*Tags:* `Enterprise Channel`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Bot resource group in the user subscription.
* `resourceName` - _required_ - The name of the Bot resource.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Azure Subscription ID.

## License

**flow**ground :- Telekom iPaaS / azure-com-botservice-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
