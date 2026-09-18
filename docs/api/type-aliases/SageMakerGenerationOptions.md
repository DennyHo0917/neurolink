[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / SageMakerGenerationOptions

# Type Alias: SageMakerGenerationOptions

> **SageMakerGenerationOptions** = `object`

Defined in: [types/providers.ts:1681](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1681)

Enhanced generation request options

## Properties

### prompt

> **prompt**: `string`

Defined in: [types/providers.ts:1683](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1683)

Input prompt text

---

### systemPrompt?

> `optional` **systemPrompt?**: `string`

Defined in: [types/providers.ts:1685](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1685)

System prompt for context

---

### maxTokens?

> `optional` **maxTokens?**: `number`

Defined in: [types/providers.ts:1687](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1687)

Maximum tokens to generate

---

### temperature?

> `optional` **temperature?**: `number`

Defined in: [types/providers.ts:1689](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1689)

Temperature for randomness (0-1)

---

### topP?

> `optional` **topP?**: `number`

Defined in: [types/providers.ts:1691](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1691)

Top-p nucleus sampling (0-1)

---

### topK?

> `optional` **topK?**: `number`

Defined in: [types/providers.ts:1693](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1693)

Top-k sampling

---

### stopSequences?

> `optional` **stopSequences?**: `string`[]

Defined in: [types/providers.ts:1695](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1695)

Stop sequences to end generation

---

### stream?

> `optional` **stream?**: `boolean`

Defined in: [types/providers.ts:1697](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1697)

Enable streaming response

---

### tools?

> `optional` **tools?**: `object`[]

Defined in: [types/providers.ts:1699](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1699)

Tools available for function calling

#### name

> **name**: `string`

#### description

> **description**: `string`

#### parameters

> **parameters**: `Record`\<`string`, `unknown`\>

---

### toolChoice?

> `optional` **toolChoice?**: `"auto"` \| `"none"` \| \{ `type`: `"tool"`; `name`: `string`; \}

Defined in: [types/providers.ts:1705](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1705)

Tool choice mode
