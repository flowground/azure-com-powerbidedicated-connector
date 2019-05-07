# ![LOGO](logo.png) PowerBIDedicated **flow**ground Connector

## Description

A generated **flow**ground connector for the PowerBIDedicated API (version 2017-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/powerbidedicated/2017-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:37+03:00

## API Description

PowerBI Dedicated Web API provides a RESTful set of web services that enables users to create, retrieve, update, and delete Power BI dedicated capacities

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available PowerBIDedicated REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The client API version.

### Lists all the Dedicated capacities for the given subscription.

*Tags:* `Capacities`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Check the name availability in the target location.

*Tags:* `Capacities`

#### Input Parameters
* `location` - _required_ - The region name which the operation will lookup into.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists eligible SKUs for PowerBI Dedicated resource provider.

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the Dedicated capacities for the given resource group.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified Dedicated capacity.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets details about the specified dedicated capacity.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the dedicated capacity. It must be a minimum of 3 characters, and a maximum of 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates the current state of the specified Dedicated capacity.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Provisions the specified Dedicated capacity based on the configuration specified in the request.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be a minimum of 3 characters, and a maximum of 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Resumes operation of the specified Dedicated capacity instance.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists eligible SKUs for a PowerBI Dedicated resource.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Suspends operation of the specified dedicated capacity instance.

*Tags:* `Capacities`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given PowerBIDedicated capacity is part. This name must be at least 1 character in length, and no more than 90.
* `dedicatedCapacityName` - _required_ - The name of the Dedicated capacity. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-powerbidedicated-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
