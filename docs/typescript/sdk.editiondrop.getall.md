---
slug: /sdk.editiondrop.getall
title: EditionDrop.getAll() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## EditionDrop.getAll() method

Get All NFTs

**Signature:**

```typescript
getAll(queryParams?: QueryAllParams): Promise<EditionMetadata[]>;
```

## Parameters

| Parameter   | Type                                      | Description                                                             |
| ----------- | ----------------------------------------- | ----------------------------------------------------------------------- |
| queryParams | [QueryAllParams](./sdk.queryallparams.md) | <i>(Optional)</i> optional filtering to only fetch a subset of results. |

**Returns:**

Promise&lt;[EditionMetadata](./sdk.editionmetadata.md)\[\]&gt;

The NFT metadata for all NFTs queried.

## Remarks

Get all the data associated with every NFT in this contract.

By default, returns the first 100 NFTs, use queryParams to fetch more.