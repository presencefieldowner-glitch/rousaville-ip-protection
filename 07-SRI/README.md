# 07-SRI (Extensible Sensory/Resonance Layer)

Real implementation: `RealityStateOS/008_REALITY_TAPE/src/sensorIntake.ts` — a `SignalSource` contract plus two concrete software-signal sources (`ManualSignalSource`, `ClockTickSource`). Real hardware sensor access (cameras, microphones, environmental sensors) requires OS/driver-level integration this sandbox cannot provide — see that module's README for the same honesty principle `002_KERNEL/KERNEL_RFC.md` established for Kernel memory/process isolation.

Minimal precursor inside the Kernel AI: `002_KERNEL/LakeTiticaca/laketiticaca/observation.py`.

Note: the separate `presencefieldowner-glitch/presence-resonance` repository's `packages/resonance` is a naming echo only (genealogy pattern-matching, unrelated subject matter, unimplemented stub) — see `RT-IP-RCOREX-MAPPING-002` Section 6.3. It is not evidence of SRI implementation.

Status: minimal implementation (software signals only); real hardware intake and the full `008_REALITY_TAPE` sensor-ingestion module are documented as planned.
