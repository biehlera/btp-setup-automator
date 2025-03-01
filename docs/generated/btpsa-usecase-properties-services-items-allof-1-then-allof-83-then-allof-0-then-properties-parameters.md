## parameters Type

`object` ([Details](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters.md))

# parameters Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                  |
| :-------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [businessSystemId](#businesssystemid)         | `string`  | Optional | cannot be null | [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-businesssystemid.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/businessSystemId")         |
| [enableTenantDeletion](#enabletenantdeletion) | `boolean` | Optional | cannot be null | [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-enabletenantdeletion.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/enableTenantDeletion") |
| [globalTenantId](#globaltenantid)             | `string`  | Optional | cannot be null | [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-globaltenantid.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/globalTenantId")             |
| [logSys](#logsys)                             | `string`  | Optional | cannot be null | [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-logsys.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/logSys")                             |
| [writePermissions](#writepermissions)         | `array`   | Optional | cannot be null | [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-writepermissions.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/writePermissions")         |

## businessSystemId

Name to be displayed in SAP Master Data Orchestration UI. If not provided, a random UUID will be assigned.

`businessSystemId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-businesssystemid.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/businessSystemId")

### businessSystemId Type

`string`

### businessSystemId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^.{1,60}$
```

[try pattern](https://regexr.com/?expression=%5E.%7B1%2C60%7D%24 "try regular expression with regexr.com")

## enableTenantDeletion

Boolean flag to be set to true for confirming deletion of last service instance for the tenant.

`enableTenantDeletion`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-enabletenantdeletion.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/enableTenantDeletion")

### enableTenantDeletion Type

`boolean`

## globalTenantId

A name for the last significant writer (client) following the Globally Unique Tenant ID (GTID) specification.

`globalTenantId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-globaltenantid.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/globalTenantId")

### globalTenantId Type

`string`

### globalTenantId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9-._~]{1,40}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9-._~%5D%7B1%2C40%7D%24 "try regular expression with regexr.com")

## logSys

The logical system.

`logSys`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-logsys.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/logSys")

### logSys Type

`string`

### logSys Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^.{1,10}$
```

[try pattern](https://regexr.com/?expression=%5E.%7B1%2C10%7D%24 "try regular expression with regexr.com")

## writePermissions

Array of entities the service instance has write permission for

`writePermissions`

*   is optional

*   Type: `object[]` ([Details](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-writepermissions-items.md))

*   cannot be null

*   defined in: [JSON Schema for BTPSA use case definitions](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-writepermissions.md "undefined#/properties/services/items/allOf/1/then/allOf/83/then/allOf/0/then/properties/parameters/properties/writePermissions")

### writePermissions Type

`object[]` ([Details](btpsa-usecase-properties-services-items-allof-1-then-allof-83-then-allof-0-then-properties-parameters-properties-writepermissions-items.md))
