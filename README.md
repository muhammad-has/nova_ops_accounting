# Nova Ops Accounting

## Project Overview

An educational data-processing project that transforms operational 
Excel data into structured, reviewable accounting journal entries
using Python and pandas.


## Objectives

- Inspect and validate operational Excel data.
- Clean and standardize transaction records.
- Classify transactions using documented accounting rules.
- Generate journal enteries for purchases, local sales, cash receipts,
  cash movements, and other posting
- Reconcile generated entries with the source data
- Test accounting and data-quality rules.


## Data Source

The project uses and operational Excel workbook containing
transactions sheets and reference sheets.

Original business data is stored locally and excluded from Git.

## Technology Stack

- Python
- pandas 
- openpyxl
- JupyterLab
- Git

## Project Status

phase 1: Environment setup and source-data exploration.

## Accounting Controls

Generated journal enteries must be balanced, traceable to source
recoeds, and reconciled to independntly calculated source totals.

## Git Workflow

All repository changes must be made on a dedicated branch.
Direct changes to `main` are not allowed.

### Workflow

1. Create a branch for each feature, fix, documentation update,
    or other change.
2. Make the changes on that branch.
3. Review the diff and run the relevant tests or checks.
4. Commit the verified changes.
5. Push the branch to GitHub.
6. Open a Pull Request targeting `main`.
7. Review and approve the changes before merging.
8. Verify that `main` is up to date after merging.

### Branch Naming

- `feat/`: new features
- `fix/`: bug fixes
- `docs/`: documentation changes
- `test/`: tests
- `refactor/`: code restructuring

#### Data Protection

Real business data, credentials, virtual environments, and generated
outputs must not be commited to the repository.
