---
slug: /react.usecontracttype
title: useContractType() function
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## useContractType() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Use this to get the contract type for a (built-in or custom) contract.

**Signature:**

```typescript
declare function useContractType(contractAddress?: string): react_query.UseQueryResult<"split" | "custom" | "nft-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | undefined, unknown>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contractAddress | string | <i>(Optional)</i> the address of the deployed contract |

**Returns:**

react\_query.UseQueryResult&lt;"split" \| "custom" \| "nft-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| undefined, unknown&gt;

a response object that includes the contract type of the contract

## Example


```javascript
const { data: contractType, isLoading, error } = useContractType("{{contract_address}}");
```