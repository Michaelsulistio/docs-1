---
slug: /sdk.marketplaceauction
title: MarketplaceAuction class
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# MarketplaceAuction class

Handles auction listings

**Signature:**

```typescript
export declare class MarketplaceAuction
```

## Constructors

| Constructor                                                                          | Modifiers | Description                                                            |
| ------------------------------------------------------------------------------------ | --------- | ---------------------------------------------------------------------- |
| [(constructor)(contractWrapper, storage)](./sdk.marketplaceauction._constructor_.md) |           | Constructs a new instance of the <code>MarketplaceAuction</code> class |

## Properties

| Property                                       | Modifiers | Type                                                                   | Description |
| ---------------------------------------------- | --------- | ---------------------------------------------------------------------- | ----------- |
| [encoder](./sdk.marketplaceauction.encoder.md) |           | [ContractEncoder](./sdk.contractencoder.md)&lt;MarketplaceContract&gt; |             |

## Methods

| Method                                                                        | Modifiers | Description                                                                 |
| ----------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------- |
| [buyoutListing(listingId)](./sdk.marketplaceauction.buyoutlisting.md)         |           | Buyout Auction                                                              |
| [cancelListing(listingId)](./sdk.marketplaceauction.cancellisting.md)         |           | Cancel Auction Listing                                                      |
| [closeListing(listingId, closeFor)](./sdk.marketplaceauction.closelisting.md) |           | Close the Auction for the buyer or the seller                               |
| [createListing(listing)](./sdk.marketplaceauction.createlisting.md)           |           | Create Auction                                                              |
| [executeSale(listingId)](./sdk.marketplaceauction.executesale.md)             |           | Execute the Auction Sale                                                    |
| [getAddress()](./sdk.marketplaceauction.getaddress.md)                        |           |                                                                             |
| [getBidBufferBps()](./sdk.marketplaceauction.getbidbufferbps.md)              |           | Get the buffer in basis points between offers                               |
| [getListing(listingId)](./sdk.marketplaceauction.getlisting.md)               |           | Get an Auction listing by id                                                |
| [getMinimumNextBid(listingId)](./sdk.marketplaceauction.getminimumnextbid.md) |           | returns the minimum bid a user can place to outbid the previous highest bid |
| [getWinner(listingId)](./sdk.marketplaceauction.getwinner.md)                 |           | Get Auction Winner                                                          |
| [getWinningBid(listingId)](./sdk.marketplaceauction.getwinningbid.md)         |           | Get Highest Bid                                                             |
| [makeBid(listingId, pricePerToken)](./sdk.marketplaceauction.makebid.md)      |           | Bid On Auction                                                              |
| [updateListing(listing)](./sdk.marketplaceauction.updatelisting.md)           |           | Update an Auction listing with new metadata                                 |