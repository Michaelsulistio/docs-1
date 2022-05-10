---
slug: /sdk.erc721owned.tokenids
title: Erc721Owned.tokenIds() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## Erc721Owned.tokenIds() method

Get all token ids of NFTs owned by a specific wallet.

**Signature:**

```typescript
tokenIds(walletAddress?: string): Promise<BigNumber[]>;
```

## Parameters

| Parameter     | Type   | Description                                                                     |
| ------------- | ------ | ------------------------------------------------------------------------------- |
| walletAddress | string | <i>(Optional)</i> the wallet address to query, defaults to the connected wallet |

**Returns:**

Promise&lt;BigNumber\[\]&gt;