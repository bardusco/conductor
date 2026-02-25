# Spec: 100% Regression Test Parity with cppfront

## Goal
Ensure that the Conductor repository passes a full regression test suite that mirrors the behavior of the upstream `cppfront` project, despite the grammar superset introduced by Conductor.

## Requirements
- All existing `cppfront` tests must run unchanged and succeed.
- Any additional features or grammar extensions introduced by Conductor must have corresponding tests that verify they do not break existing behavior.
- Test coverage must be ≥ 95 % for the core `cppfront` front‑end components.
- The CI pipeline must automatically run these tests on every push.

## Success Criteria
- `make test` (or the project's test command) exits with status 0.
- No test failures are reported.
- Coverage report shows ≥ 95 % for the target modules.
- CI status badge shows green.
