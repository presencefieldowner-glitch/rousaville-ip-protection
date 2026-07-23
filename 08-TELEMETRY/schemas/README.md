# Event Schemas

Real implementation: `RealityStateOS/003_FOUNDATION/CoreTypes/src/event.ts` — hash-chained, Ed25519-signed `Event<T>` envelope (`eventId`, `topic`, `schemaVersion`, `occurredAt`, `prevHash`, `payload`, `signatureHex`), implementing RFC-0002 §5.

Status: implemented, tested.
