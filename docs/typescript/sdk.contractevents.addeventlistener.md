---
slug: /sdk.contractevents.addeventlistener
title: ContractEvents.addEventListener() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ContractEvents.addEventListener() method

Subscribe to contract events

**Signature:**

```typescript
addEventListener(eventName: keyof TContract["filters"] | string, listener: (event: Record<string, any>) => void): void;
```

## Parameters

| Parameter | Type                                          | Description                                         |
| --------- | --------------------------------------------- | --------------------------------------------------- |
| eventName | keyof TContract\["filters"\] &#124; string    | the event name as defined in the contract           |
| listener  | (event: Record&lt;string, any&gt;) =&gt; void | the receiver that will be called on every new event |

**Returns:**

void

## Remarks

Add a listener for a particular contract event

## Example

```javascript
contract.events.addListener("TokensMinted", (event) => {
  console.log(event);
});
```
