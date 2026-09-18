[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / InvokeEndpointParams

# Type Alias: InvokeEndpointParams

> **InvokeEndpointParams** = `object`

Defined in: [types/providers.ts:1522](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1522)

Parameters for SageMaker endpoint invocation

## Properties

### EndpointName

> **EndpointName**: `string`

Defined in: [types/providers.ts:1524](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1524)

Endpoint name to invoke

---

### Body

> **Body**: `string` \| `Uint8Array`

Defined in: [types/providers.ts:1526](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1526)

Request body as string or Uint8Array

---

### ContentType?

> `optional` **ContentType?**: `string`

Defined in: [types/providers.ts:1528](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1528)

Content type of the request

---

### Accept?

> `optional` **Accept?**: `string`

Defined in: [types/providers.ts:1530](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1530)

Accept header for response format

---

### CustomAttributes?

> `optional` **CustomAttributes?**: `string`

Defined in: [types/providers.ts:1532](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1532)

Custom attributes for the request

---

### TargetModel?

> `optional` **TargetModel?**: `string`

Defined in: [types/providers.ts:1534](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1534)

Target model for multi-model endpoints

---

### TargetVariant?

> `optional` **TargetVariant?**: `string`

Defined in: [types/providers.ts:1536](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1536)

Target variant for A/B testing

---

### InferenceId?

> `optional` **InferenceId?**: `string`

Defined in: [types/providers.ts:1538](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1538)

Inference ID for request tracking

---

### abortSignal?

> `optional` **abortSignal?**: `AbortSignal`

Defined in: [types/providers.ts:1548](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1548)

Cancels the in-flight HTTP request, not just the loop around it.

Named in camelCase deliberately: every other field here mirrors an AWS
`InvokeEndpointCommandInput` member and keeps its PascalCase, whereas this
one is a transport option handed to `client.send()` as
`@smithy/types` `HttpHandlerOptions` — it is never part of the command
payload, and spelling it differently keeps that boundary visible.
