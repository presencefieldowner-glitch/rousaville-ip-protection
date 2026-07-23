# 06-NHI (Extensible Natural/Human Interface Layer)

Real, bound implementation: `RealityStateOS/011_INTERFACE/src/restApi.ts` (real HTTP server, RFC-0005 profile endpoints) and `src/cli.ts` (real command dispatcher, `cli_commands.md` subset).

Prototype-stage precursor inside the Kernel AI: `002_KERNEL/LakeTiticaca/laketiticaca/api.py`, `rest.py`, `grpc.py`, `websocket.py`, `cli.py`, `dashboard.py`.

**Not implemented:** GraphQL, WebSocket, Mobile, Desktop, XR surfaces — see `RealityStateOS/011_INTERFACE/src/plannedSurfaces.ts` for the explicit, honest status of each.

Status: partially implemented (REST + CLI real and tested; remaining surfaces documented as planned).
