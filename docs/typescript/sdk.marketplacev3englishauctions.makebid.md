---
slug: /sdk.marketplacev3englishauctions.makebid
title: MarketplaceV3EnglishAuctions.makeBid() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# MarketplaceV3EnglishAuctions.makeBid() method

Bid on an english auction

## Example

```javascript
// The auction ID of the asset you want to bid on
const auctionId = 0;
// The total amount you are willing to bid for auctioned tokens
const bidAmount = 1;

await contract.englishAuctions.makeBid(auctionId, bidAmount);
```

**Signature:**

```typescript
makeBid(auctionId: BigNumberish, bidAmount: Price): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type                    | Description                       |
| --------- | ----------------------- | --------------------------------- |
| auctionId | BigNumberish            | the auction id                    |
| bidAmount | [Price](./sdk.price.md) | the amount you are willing to bid |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

the transaction result

## Remarks

Make a bid on an auction