---
slug: /sdk.nftcollection.burn
title: NFTCollection.burn() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## NFTCollection.burn() method

Burn a single NFT

**Signature:**

```typescript
burn(tokenId: BigNumberish): Promise<TransactionResult>;
```

## Parameters

| Parameter | Type         | Description          |
| --------- | ------------ | -------------------- |
| tokenId   | BigNumberish | the token Id to burn |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

## Example

```javascript
const result = await contract.burn(tokenId);
```
