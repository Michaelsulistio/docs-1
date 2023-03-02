---
slug: /sdk.tokenerc20history.getallholderbalances
title: TokenERC20History.getAllHolderBalances() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# TokenERC20History.getAllHolderBalances() method

Get all holder balances

## Example

```javascript
const allHolderBalances = await contract.history.getAllHolderBalances();
```

**Signature:**

```typescript
getAllHolderBalances(): Promise<TokenHolderBalance[]>;
```

**Returns:**

Promise&lt;[TokenHolderBalance](./sdk.tokenholderbalance.md)\[\]&gt;

- A JSON object of all token holders and their corresponding balances

## Remarks

Lets you get all token holders and their corresponding balances