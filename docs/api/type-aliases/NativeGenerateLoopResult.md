[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / NativeGenerateLoopResult

# Type Alias: NativeGenerateLoopResult

> **NativeGenerateLoopResult** = `object`

Defined in: [types/generate.ts:1833](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1833)

## Properties

### text

> **text**: `string`

Defined in: [types/generate.ts:1834](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1834)

---

### reasoning?

> `optional` **reasoning?**: `string`

Defined in: [types/generate.ts:1836](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1836)

Joined reasoning content parts from the final step, when the vendor sent any.

---

### finishReason

> **finishReason**: `string`

Defined in: [types/generate.ts:1837](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1837)

---

### rawFinishReason?

> `optional` **rawFinishReason?**: `string`

Defined in: [types/generate.ts:1838](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1838)

---

### inputTokens

> **inputTokens**: `number`

Defined in: [types/generate.ts:1839](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1839)

---

### outputTokens

> **outputTokens**: `number`

Defined in: [types/generate.ts:1840](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1840)

---

### cacheReadTokens

> **cacheReadTokens**: `number`

Defined in: [types/generate.ts:1841](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1841)

---

### cacheWriteTokens

> **cacheWriteTokens**: `number`

Defined in: [types/generate.ts:1842](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1842)

---

### toolsUsed

> **toolsUsed**: `string`[]

Defined in: [types/generate.ts:1843](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1843)

---

### steps

> **steps**: `number`

Defined in: [types/generate.ts:1844](https://github.com/juspay/neurolink/blob/release/src/lib/types/generate.ts#L1844)
