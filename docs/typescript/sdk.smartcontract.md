---
slug: /sdk.smartcontract
title: SmartContract class
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## SmartContract class

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Custom contract dynamic class with feature detection

**Signature:**

```typescript
export declare class SmartContract<TContract extends ThirdwebContract = ThirdwebContract> implements UpdateableNetwork
```

**Implements:** UpdateableNetwork

## Example

```javascript
import { ThirdwebSDK } from "@thirdweb-dev/sdk";

// You can switch out this provider with any wallet or provider setup you like.
const sdk = new ThirdwebSDK(provider);
const contract = sdk.getContract("{{contract_address}}");

// call any function in your contract
await contract.functions.myCustomFunction(params);

// if your contract follows the ERC721 standard, contract.nft will be present
const allNFTs = await contract.nft.query.all();

// if your contract extends IMintableERC721, contract.nft.mint will be present
const tx = await contract.nft.mint.to("0x...", {
  name: "Cool NFT",
  image: readFileSync("some_image.png"),
});
```

## Constructors

| Constructor                                                                                                     | Modifiers | Description                                                                         |
| --------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------- |
| [(constructor)(network, address, abi, storage, options, contractWrapper)](./sdk.smartcontract._constructor_.md) |           | **<i>(BETA)</i>** Constructs a new instance of the <code>SmartContract</code> class |

## Properties

| Property                                                      | Modifiers           | Type                                                                                                     | Description                                                                                                                      |
| ------------------------------------------------------------- | ------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [contractType](./sdk.smartcontract.contracttype.md)           | <code>static</code> | "custom"                                                                                                 | **<i>(BETA)</i>**                                                                                                                |
| [edition](./sdk.smartcontract.edition.md)                     |                     | [Erc1155](./sdk.erc1155.md) &#124; undefined                                                             | **<i>(BETA)</i>** Auto-detects ERC1155 standard functions.                                                                       |
| [estimator](./sdk.smartcontract.estimator.md)                 |                     | [GasCostEstimator](./sdk.gascostestimator.md)&lt;TContract&gt;                                           | **<i>(BETA)</i>**                                                                                                                |
| [events](./sdk.smartcontract.events.md)                       |                     | [ContractEvents](./sdk.contractevents.md)&lt;TContract&gt;                                               | **<i>(BETA)</i>**                                                                                                                |
| [functions](./sdk.smartcontract.functions.md)                 |                     | any                                                                                                      | **<i>(BETA)</i>** Call any function in this contract using the function signature ex: contract.functions.mint(address, quantity) |
| [interceptor](./sdk.smartcontract.interceptor.md)             |                     | ContractInterceptor&lt;TContract&gt;                                                                     | **<i>(BETA)</i>**                                                                                                                |
| [metadata](./sdk.smartcontract.metadata.md)                   |                     | [ContractMetadata](./sdk.contractmetadata.md)&lt;ThirdwebContract, any&gt; &#124; undefined              | **<i>(BETA)</i>**                                                                                                                |
| [nft](./sdk.smartcontract.nft.md)                             |                     | [Erc721](./sdk.erc721.md) &#124; undefined                                                               | **<i>(BETA)</i>** Auto-detects ERC721 standard functions.                                                                        |
| [platformFees](./sdk.smartcontract.platformfees.md)           |                     | [ContractPlatformFee](./sdk.contractplatformfee.md)&lt;IPlatformFee&gt; &#124; undefined                 | **<i>(BETA)</i>**                                                                                                                |
| [publishedMetadata](./sdk.smartcontract.publishedmetadata.md) |                     | ContractPublishedMetadata&lt;TContract&gt;                                                               | **<i>(BETA)</i>**                                                                                                                |
| [roles](./sdk.smartcontract.roles.md)                         |                     | [ContractRoles](./sdk.contractroles.md)&lt;IPermissionsEnumerable, any&gt; &#124; undefined              | **<i>(BETA)</i>**                                                                                                                |
| [royalties](./sdk.smartcontract.royalties.md)                 |                     | [ContractRoyalty](./sdk.contractroyalty.md)&lt;IRoyalty &amp; ThirdwebContract, any&gt; &#124; undefined | **<i>(BETA)</i>**                                                                                                                |
| [sales](./sdk.smartcontract.sales.md)                         |                     | [ContractPrimarySale](./sdk.contractprimarysale.md)&lt;IPrimarySale&gt; &#124; undefined                 | **<i>(BETA)</i>**                                                                                                                |
| [token](./sdk.smartcontract.token.md)                         |                     | [Erc20](./sdk.erc20.md) &#124; undefined                                                                 | **<i>(BETA)</i>** Auto-detects ERC20 standard functions.                                                                         |

## Methods

| Method                                                               | Modifiers | Description       |
| -------------------------------------------------------------------- | --------- | ----------------- |
| [getAddress()](./sdk.smartcontract.getaddress.md)                    |           | **<i>(BETA)</i>** |
| [onNetworkUpdated(network)](./sdk.smartcontract.onnetworkupdated.md) |           | **<i>(BETA)</i>** |