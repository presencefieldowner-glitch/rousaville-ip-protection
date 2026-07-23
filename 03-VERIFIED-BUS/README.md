# 03-Verified-Bus

Real implementation: `presencefieldowner-glitch/RealityStateOS/004_VERIFIED_BUS/` — event broker on `003_FOUNDATION/CoreTypes`'s hash-chained, signed `Event<T>` envelope; pluggable consensus (`SingleNodeConsensus` implemented, `RaftConsensus` documented as planned — real multi-node Raft needs an actual cluster this sandbox doesn't have); bus-level telemetry.

Prototype-stage precursor inside the Kernel AI: `002_KERNEL/LakeTiticaca/laketiticaca/event_bus.py`.

Status: single-node prototype, implemented and tested (9/9 tests as of 2026-07-23).
