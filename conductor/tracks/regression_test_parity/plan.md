# Plan: 100% Regression Test Parity with cppfront

## Tasks
- [ ] Clone the upstream `cppfront` repository as a submodule or separate checkout.
- [ ] Integrate Conductor's grammar superset into the cppfront build configuration.
- [ ] Ensure existing `cppfront` test suite runs without modification.
- [ ] Add tests for Conductor‑specific extensions.
- [ ] Run coverage analysis (e.g., `lcov` or `llvm-cov`) and enforce ≥ 95 % coverage for core modules.
- [ ] Update CI pipeline (`.github/workflows/ci.yml`) to execute the full test suite and upload coverage reports.
- [ ] Verify CI badge turns green on the repository README.
- [ ] Document the test setup and coverage thresholds in `README.md`.
