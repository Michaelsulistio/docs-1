---
slug: /sdk.marketplacecontractdeploymetadata
title: MarketplaceContractDeployMetadata interface
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# MarketplaceContractDeployMetadata interface

Options for deploying a Marketplace contract

**Signature:**

```typescript
export interface MarketplaceContractDeployMetadata
```

## Properties

| Property                                                                                           | Modifiers | Type                 | Description                                                                |
| -------------------------------------------------------------------------------------------------- | --------- | -------------------- | -------------------------------------------------------------------------- |
| [description?](./sdk.marketplacecontractdeploymetadata.description.md)                             |           | string               | _(Optional)_ Optional description of the contract                          |
| [external_link?](./sdk.marketplacecontractdeploymetadata.external_link.md)                         |           | string               | _(Optional)_ Optional url for the contract                                 |
| [image?](./sdk.marketplacecontractdeploymetadata.image.md)                                         |           | FileOrBufferOrString | _(Optional)_ Optional image for the contract                               |
| [name](./sdk.marketplacecontractdeploymetadata.name.md)                                            |           | string               | name of the contract                                                       |
| [platform_fee_basis_points?](./sdk.marketplacecontractdeploymetadata.platform_fee_basis_points.md) |           | number               | _(Optional)_ The percentage (in basis points) of platform fees             |
| [platform_fee_recipient?](./sdk.marketplacecontractdeploymetadata.platform_fee_recipient.md)       |           | string               | _(Optional)_ The address that will receive the proceeds from platform fees |
| [trusted_forwarders?](./sdk.marketplacecontractdeploymetadata.trusted_forwarders.md)               |           | string\[\]           | _(Optional)_ Custom gasless trusted forwarder addresses                    |