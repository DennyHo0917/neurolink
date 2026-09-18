[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / SageMakerErrorInfo

# Type Alias: SageMakerErrorInfo

> **SageMakerErrorInfo** = `object`

Defined in: [types/providers.ts:1745](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1745)

SageMaker-specific error information

## Properties

### code

> **code**: [`SageMakerErrorCode`](SageMakerErrorCode.md)

Defined in: [types/providers.ts:1747](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1747)

Error code

---

### message

> **message**: `string`

Defined in: [types/providers.ts:1749](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1749)

Human-readable error message

---

### statusCode?

> `optional` **statusCode?**: `number`

Defined in: [types/providers.ts:1751](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1751)

HTTP status code if applicable

---

### cause?

> `optional` **cause?**: `Error`

Defined in: [types/providers.ts:1753](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1753)

Original error from AWS SDK

---

### endpoint?

> `optional` **endpoint?**: `string`

Defined in: [types/providers.ts:1755](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1755)

Endpoint name where error occurred

---

### requestId?

> `optional` **requestId?**: `string`

Defined in: [types/providers.ts:1757](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1757)

Request ID for debugging

---

### retryable?

> `optional` **retryable?**: `boolean`

Defined in: [types/providers.ts:1759](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1759)

Retry suggestion
