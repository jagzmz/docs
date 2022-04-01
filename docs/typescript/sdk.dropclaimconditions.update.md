---
slug: /sdk.dropclaimconditions.update
title: DropClaimConditions.update() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## DropClaimConditions.update() method

Update a single claim condition with new data.

**Signature:**

```typescript
update(index: number, claimConditionInput: ClaimConditionInput): Promise<TransactionResult>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  index | number | the index of the claim condition to update, as given by the index from the result of <code>getAll()</code> |
|  claimConditionInput | [ClaimConditionInput](./sdk.claimconditioninput.md) | the new data to update, previous data will be retained |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;