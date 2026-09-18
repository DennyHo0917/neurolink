[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / SageMakerStreamingToolCall

# Type Alias: SageMakerStreamingToolCall

> **SageMakerStreamingToolCall** = `object`

Defined in: [types/providers.ts:1625](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1625)

Streaming tool call information (Phase 2.3)

## Properties

### id

> **id**: `string`

Defined in: [types/providers.ts:1627](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1627)

Tool call identifier

---

### name?

> `optional` **name?**: `string`

Defined in: [types/providers.ts:1629](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1629)

Tool/function name

---

### arguments?

> `optional` **arguments?**: `string`

Defined in: [types/providers.ts:1631](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1631)

Partial or complete arguments as JSON string

---

### type

> **type**: `"function"`

Defined in: [types/providers.ts:1633](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1633)

Tool call type

---

### complete?

> `optional` **complete?**: `boolean`

Defined in: [types/providers.ts:1635](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1635)

Indicates if this tool call is complete

---

### argumentsDelta?

> `optional` **argumentsDelta?**: `string`

Defined in: [types/providers.ts:1637](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1637)

Delta text for incremental argument building
