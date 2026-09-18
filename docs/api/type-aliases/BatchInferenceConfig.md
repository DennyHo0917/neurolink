[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / BatchInferenceConfig

# Type Alias: BatchInferenceConfig

> **BatchInferenceConfig** = `object`

Defined in: [types/providers.ts:1765](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1765)

Batch inference job configuration

## Properties

### inputS3Uri

> **inputS3Uri**: `string`

Defined in: [types/providers.ts:1767](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1767)

Input S3 location

---

### outputS3Uri

> **outputS3Uri**: `string`

Defined in: [types/providers.ts:1769](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1769)

Output S3 location

---

### modelName

> **modelName**: `string`

Defined in: [types/providers.ts:1771](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1771)

SageMaker model name

---

### instanceType

> **instanceType**: `string`

Defined in: [types/providers.ts:1773](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1773)

Instance type for batch job

---

### instanceCount

> **instanceCount**: `number`

Defined in: [types/providers.ts:1775](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1775)

Instance count for batch job

---

### maxPayloadInMB?

> `optional` **maxPayloadInMB?**: `number`

Defined in: [types/providers.ts:1777](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1777)

Maximum payload size in MB

---

### batchStrategy?

> `optional` **batchStrategy?**: `"MultiRecord"` \| `"SingleRecord"`

Defined in: [types/providers.ts:1779](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1779)

Batch strategy
