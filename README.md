# fastapi-spec-testing

Final project for Software Testing, 2026 Fall.

**Author:** Yi-Hsun Chiu (314551044)
**Category:** Open Source Testing Contribution, with the AI-Assisted Software Testing theme

## Overview

This project adds tests to an open-source FastAPI project using its API specification, and compares three ways of generating tests:

1. **Schemathesis**, which generates test requests automatically from the OpenAPI specification
2. **Hand-written pytest tests**, with expected values derived from the requirements
3. **LLM-generated tests**

The comparison looks at bugs found, coverage, mutation score, assertion echo (expected values copied from the program's own output), and time and cost.

## Target project

To be decided. See issue #1.

## Tools

Schemathesis, pytest, coverage.py, mutmut, GitHub Actions

## Progress

Tasks are tracked in [Issues](../../issues).
