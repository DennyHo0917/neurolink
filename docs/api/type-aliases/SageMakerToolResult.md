[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / SageMakerToolResult

# Type Alias: SageMakerToolResult

> **SageMakerToolResult** = `object`

Defined in: [types/providers.ts:1609](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1609)

Tool result information

## Properties

### toolCallId

> **toolCallId**: `string`

Defined in: [types/providers.ts:1611](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1611)

Tool call identifier

---

### toolName

> **toolName**: `string`

Defined in: [types/providers.ts:1613](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1613)

Tool name

---

### result

> **result**: `unknown`

Defined in: [types/providers.ts:1615](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1615)

Tool result data

---

### status

> **status**: `"success"` \| `"error"`

Defined in: [types/providers.ts:1617](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1617)

Execution status

---

### error?

> `optional` **error?**: `string`

Defined in: [types/providers.ts:1619](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1619)

Error message if status is error
