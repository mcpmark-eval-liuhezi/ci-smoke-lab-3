# ci-smoke-lab-3

Scratch lab for demonstrating a full GitHub Actions CI round-trip

## Purpose

This repository is a disposable scratch lab for the internal tooling audit. It is used to demonstrate that a full CI round-trip works end to end: a push to the default branch triggers the `smoke.yml` workflow, the run completes, and a small README change is carried through a pull request back into the default branch. It is safe to delete after the audit.
