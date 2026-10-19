# Experiment scripts

This directory will hold locally runnable POSIX scripts shared with workflows.

Planned tooling:

- `fetch-lab.sh`: read the declared Lab release from `experiment.toml` and fetch it into `vendor/lab/`.
- Local validation and optional experiment tests.
- Packaging and deployment helpers.

These scripts and the version manifest are separate backlog tasks. No dependency
fetch or bootstrap command is available yet. Experiments must use their own
fetched Lab dependency rather than depend on a sibling checkout.
