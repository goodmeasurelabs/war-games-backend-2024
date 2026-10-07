# Retained backend history

The portfolio hosting ledger records this Rails game backend as intentionally retired before the Babe Ruth frontend migration. `war-games-vite` is the independent Pages frontend. This repository is not a static website and must not receive a Pages deploy workflow.

The last GitHub deployment record references commit `1105bdcadbb3cd3abee1b8d85b82626f74b2a0f8` and environment `immense-temple-53760`; the checked-in Fly configuration instead names `war-games-2-0-api`. Neither establishes a currently available service. Keep both facts distinct. No hosted runtime or database was changed, restarted or provisioned.

Reactivating gameplay would require a separate architecture/data/runtime decision and tests with a usable player dataset. The existing empty test suite and historical local /players response are not gameplay validation. Retain repository and data history.
