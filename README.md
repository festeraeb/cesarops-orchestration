# cesarops-orchestration

Public CESARops **orchestration** package: Forge, gate pipeline, mission control, fleet adapters, and shared contracts.

**Not in this repo:** model weights (GGUF/safetensors), mission geodata, full-precision curvelets.

## Intended contents (extract from `wreckhunter2000-1`)

| Monorepo path | Role |
|---|---|
| `forge/cesarops-forge-v2/` | Forge orchestration runtime |
| `core/forge-gate2`, `core/forge-gate3`, `core/forge-gate5` | Gate frameworks |
| `backend/cesarops-mission-control/` | Mission Control |
| `core/cesarops-mission-contract/`, `core/cesarops-inference-contract/` | Shared contracts |
| `tools/cesarops-paddler/`, `cesarops-paddler/` | Paddler routing |
| `backend/cesarops-pingora-edge/`, `cesarops-pingora-edge/` | Edge proxy |
| Fleet SSH / deploy scripts under `scripts/` (ops subset) | Fleet ops |

## Related repos

- [`cesarops-scorecard`](https://github.com/festeraeb/cesarops-scorecard) — public model×task performance
- [`cesarops-inference`](https://github.com/festeraeb/cesarops-inference) — distributed inference program
- [`nauti-inferer`](https://github.com/festeraeb/nauti-inferer) — inference engine
- [`nauticuvs`](https://github.com/festeraeb/nauticuvs) — public detuned curvelets
- [`nauticuvs-full`](https://github.com/festeraeb/nauticuvs-full) — **private** f64 curvelets (gated)
