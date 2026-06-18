---
name: "code-testing"
description: "Run PHPUnit tests, generate coverage reports, validate code quality for Laravel projects"
---

# Code Testing Skill

Run PHPUnit tests, generate coverage reports, and validate code quality for Laravel projects.

## Usage
- Run all tests: `run_tests(project_path)`
- Run specific test: `run_tests(project_path, test_file)`
- Run with coverage: `run_tests_with_coverage(project_path)`
- Get test summary: `get_test_summary(project_path)`

## Implementation
Python script at `skills/custom/code_testing_skill.py`.
Uses PHPUnit CLI, parses JUnit XML output.
