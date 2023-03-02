---
slug: /sdk.contractroyalty.setdefaultroyaltyinfo
title: ContractRoyalty.setDefaultRoyaltyInfo() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ContractRoyalty.setDefaultRoyaltyInfo() method

Set the royalty recipient and fee

## Example

```javascript
await contract.roles.setDefaultRoyaltyInfo({
  seller_fee_basis_points: 100, // 1% royalty fee
  fee_recipient: "0x...", // the fee recipient
});
```

**Signature:**

```typescript
setDefaultRoyaltyInfo(royaltyData: z.input<typeof CommonRoyaltySchema>): Promise<TransactionResult<z.output<typeof CommonRoyaltySchema>>>;
```

## Parameters

| Parameter   | Type                                      | Description                   |
| ----------- | ----------------------------------------- | ----------------------------- |
| royaltyData | z.input&lt;typeof CommonRoyaltySchema&gt; | the royalty recipient and fee |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&lt;z.output&lt;typeof CommonRoyaltySchema&gt;&gt;&gt;