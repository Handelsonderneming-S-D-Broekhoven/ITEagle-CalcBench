# ITEagle-CalcBench

ITEagle CalcBench is a repository of deployable diagnostic and test script files for graphing calculators. Scripts from this repository are transferred to supported calculators and executed on-device to verify functionality during testing, refurbishment, and resale preparation.

## Repository layout

This repository is organized primarily by manufacturer, platform, and calculator model so new script sets can be added without restructuring the project.

```text
manufacturers/
  casio/
    add-in/
      fx-cg50/
  hp/
    hp-ppl/
      prime-g2/
  numworks/
    python/
      numworks/
  texas-instruments/
    lua/
      ti-nspire-cx-ii/
    ti-basic/
      ti-84-plus-ce/
shared/
docs/
deployment/
test-assets/
legacy/
```

## Folder responsibilities

- `manufacturers/` contains calculator-specific script sets grouped by manufacturer, then by execution platform, then by model.
- `shared/` contains reusable resources that can be shared across multiple script sets.
- `docs/` contains process documentation, transfer notes, and repository conventions.
- `deployment/` contains helper material for packaging, transferring, and launching scripts on calculators.
- `test-assets/` contains static assets used during diagnostics, such as reference data sets, sample inputs, or expected outputs.
- `legacy/` contains archived or superseded scripts retained for historical reference.

No actual test scripts are included yet; this commit establishes the initial repository structure and documentation only.
