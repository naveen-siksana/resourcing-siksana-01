# Tests

This directory contains all test suites for the Resourcing Financials Management System.

## Test Structure

### Unit Tests (`unit/`)
Tests for individual components, functions, and classes in isolation.

**Subdirectories:**
- `financials/` - Unit tests for financial modules
- `resourcing/` - Unit tests for resourcing modules
- `utils/` - Unit tests for utility functions

### Integration Tests (`integration/`)
Tests for interactions between multiple components and systems.

**Subdirectories:**
- `api/` - API endpoint integration tests
- `database/` - Database interaction tests

### End-to-End Tests (`e2e/`)
Tests for complete user workflows and scenarios.

**Subdirectories:**
- `workflows/` - Complete business workflow tests
- `scenarios/` - Real-world usage scenario tests

## Running Tests

```bash
# Run all tests
npm test

# Run unit tests only
npm run test:unit

# Run integration tests
npm run test:integration

# Run e2e tests
npm run test:e2e

# Run with coverage
npm run test:coverage
```

## Writing Tests

- Follow the existing test patterns in the repository
- Ensure good test coverage for new features
- Write meaningful test descriptions
- Use appropriate test fixtures and mocks
- Keep tests independent and idempotent
