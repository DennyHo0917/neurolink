[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / CredentialValidationResult

# Type Alias: CredentialValidationResult

> **CredentialValidationResult** = `object`

Defined in: [types/providers.ts:349](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L349)

AWS Credential Validation Result

## Properties

### isValid

> **isValid**: `boolean`

Defined in: [types/providers.ts:350](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L350)

---

### credentialSource

> **credentialSource**: `string`

Defined in: [types/providers.ts:351](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L351)

---

### region

> **region**: `string`

Defined in: [types/providers.ts:352](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L352)

---

### hasExpiration

> **hasExpiration**: `boolean`

Defined in: [types/providers.ts:353](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L353)

---

### expirationTime?

> `optional` **expirationTime?**: `Date`

Defined in: [types/providers.ts:354](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L354)

---

### error?

> `optional` **error?**: `string`

Defined in: [types/providers.ts:355](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L355)

---

### debugInfo

> **debugInfo**: `object`

Defined in: [types/providers.ts:356](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L356)

#### accessKeyId

> **accessKeyId**: `string`

#### hasSessionToken

> **hasSessionToken**: `boolean`

#### providerConfig

> **providerConfig**: `Readonly`\<`Required`\<[`AWSCredentialConfig`](AWSCredentialConfig.md)\>\>
