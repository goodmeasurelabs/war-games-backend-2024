# Retained backend history

The portfolio hosting ledger records this Rails game backend as intentionally retired before the Babe Ruth frontend migration. `war-games-vite` is the independent Pages frontend. This repository is not a static website and must not receive a Pages deploy workflow.

The last GitHub deployment record references commit `1105bdcadbb3cd3abee1b8d85b82626f74b2a0f8` and environment `immense-temple-53760`; the checked-in Fly configuration instead names `war-games-2-0-api`. Neither establishes a currently available service. Keep both facts distinct. No hosted runtime or database was changed, restarted or provisioned.

Reactivating gameplay would require a separate architecture/data/runtime decision and tests with a usable player dataset. The existing empty test suite and historical local /players response are not gameplay validation. Retain repository and data history.

## Evidence for the retained/retired classification

This classification comes from prior migration records, not from an empty test suite or an inferred outage:

- [Platform repository operations at 50b9721](https://github.com/goodmeasurelabs/platform/blob/50b9721ab635031a51351e9f6d79588af00776a5/docs/repository-operations.md) explicitly states that the retired Babe Ruth backend is retained for its history.
- [Platform hosting ledger at d35041a](https://github.com/goodmeasurelabs/platform/blob/d35041a93612c77266abdec6d4617e71105fb5a9/config/hosting.json), the `baberuth.app` record, says the game backend was intentionally retired before migration by prior owner decision.
- [Frontend migration README at d1c9cd0](https://github.com/goodmeasurelabs/war-games-vite/blob/d1c9cd09db2e0fd075df5e1f1ba2bea7f8eb4150/cloudflare/README.md) specifies the retired Heroku API and WebSocket backend. The published frontend bundle still contains that historical Heroku origin.

These are documentary records of a prior decision; the original conversation was not available in this environment. No backend or stored data has been deleted, disabled, restarted or reconfigured by this task.
