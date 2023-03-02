---
slug: /sdk.marketplacev3englishauctions.buyoutauction
title: MarketplaceV3EnglishAuctions.buyoutAuction() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# MarketplaceV3EnglishAuctions.buyoutAuction() method

Buyout an english auction

## Example

```javascript
// The auction ID you want to buy
const auctionId = 0;

await contract.englishAuctions.buyoutAuction(auctionId);
```

**Signature:**

```typescript
buyoutAuction(auctionId: BigNumberish): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type         | Description    |
| --------- | ------------ | -------------- |
| auctionId | BigNumberish | the auction id |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

the transaction result

## Remarks

Buy a specific auction from the marketplace.