# Transaction Playground

A lightweight playground repository for testing and validating transaction workflows.

## Overview

This repository serves as a testing ground for transaction validation workflows and CI/CD processes. It includes automated validation checks to ensure transaction state integrity.

## Repository Structure

- `state.txt` - Contains transaction state versions and validation data
- `.github/workflows/ci.yml` - CI workflow for automated transaction validation

## CI Workflow

The repository includes a GitHub Actions workflow that:
- Runs on pull requests and pushes to the main branch
- Validates the presence and integrity of the transaction state file
- Ensures transaction consistency across changes

## Usage

This playground can be used to:
- Test transaction validation logic
- Experiment with CI/CD workflows
- Practice version control with state management

## License

This is a playground repository for educational and testing purposes.
