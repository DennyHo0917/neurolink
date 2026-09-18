[**NeuroLink API Reference**](../README.md)

---

[NeuroLink API Reference](../README.md) / CostEstimate

# Type Alias: CostEstimate

> **CostEstimate** = `object`

Defined in: [types/providers.ts:1837](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1837)

Cost estimation data

## Properties

### estimatedCost

> **estimatedCost**: `number`

Defined in: [types/providers.ts:1839](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1839)

Estimated cost in USD

---

### currency

> **currency**: `string`

Defined in: [types/providers.ts:1841](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1841)

Currency code

---

### breakdown

> **breakdown**: `object`

Defined in: [types/providers.ts:1843](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1843)

Cost breakdown

#### instanceCost

> **instanceCost**: `number`

Instance hours cost

#### requestCost

> **requestCost**: `number`

Request-based cost

#### totalHours

> **totalHours**: `number`

Total processing hours

---

### period?

> `optional` **period?**: `object`

Defined in: [types/providers.ts:1852](https://github.com/juspay/neurolink/blob/release/src/lib/types/providers.ts#L1852)

Time period for estimate

#### start

> **start**: `string`

#### end

> **end**: `string`
