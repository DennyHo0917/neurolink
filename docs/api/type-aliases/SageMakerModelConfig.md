[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / SageMakerModelConfig

# Type Alias: SageMakerModelConfig

> **SageMakerModelConfig** = `object`

Defined in: [types/providers.ts:1425](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1425)

Model-specific configuration for SageMaker endpoints

## Properties

### endpointName

> **endpointName**: `string`

Defined in: [types/providers.ts:1427](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1427)

SageMaker endpoint name

---

### modelType?

> `optional` **modelType?**: `"llama"` \| `"mistral"` \| `"claude"` \| `"huggingface"` \| `"jumpstart"` \| `"custom"`

Defined in: [types/providers.ts:1429](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1429)

Model type for request/response formatting

---

### contentType?

> `optional` **contentType?**: `string`

Defined in: [types/providers.ts:1437](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1437)

Content type for requests

---

### accept?

> `optional` **accept?**: `string`

Defined in: [types/providers.ts:1439](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1439)

Accept header for responses

---

### customAttributes?

> `optional` **customAttributes?**: `string`

Defined in: [types/providers.ts:1441](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1441)

Custom attributes for the endpoint

---

### inputFormat?

> `optional` **inputFormat?**: `"huggingface"` \| `"jumpstart"` \| `"custom"`

Defined in: [types/providers.ts:1443](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1443)

Input format specification

---

### outputFormat?

> `optional` **outputFormat?**: `"huggingface"` \| `"jumpstart"` \| `"custom"`

Defined in: [types/providers.ts:1445](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1445)

Output format specification

---

### maxTokens?

> `optional` **maxTokens?**: `number`

Defined in: [types/providers.ts:1447](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1447)

Maximum tokens for generation

---

### temperature?

> `optional` **temperature?**: `number`

Defined in: [types/providers.ts:1449](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1449)

Temperature parameter

---

### topP?

> `optional` **topP?**: `number`

Defined in: [types/providers.ts:1451](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1451)

Top-p parameter

---

### stopSequences?

> `optional` **stopSequences?**: `string`[]

Defined in: [types/providers.ts:1453](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1453)

Stop sequences

---

### initialConcurrency?

> `optional` **initialConcurrency?**: `number`

Defined in: [types/providers.ts:1455](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1455)

Initial concurrency for batch processing

---

### maxConcurrency?

> `optional` **maxConcurrency?**: `number`

Defined in: [types/providers.ts:1457](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1457)

Maximum concurrency for batch processing

---

### minConcurrency?

> `optional` **minConcurrency?**: `number`

Defined in: [types/providers.ts:1459](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1459)

Minimum concurrency for batch processing

---

### maxConcurrentDetectionTests?

> `optional` **maxConcurrentDetectionTests?**: `number`

Defined in: [types/providers.ts:1461](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1461)

Maximum concurrent detection tests
