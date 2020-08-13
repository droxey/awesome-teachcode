# Autograders

<!-- omit in toc -->
## Table of Contents {docsify-ignore}

- [Goal](#goal)
- [Setup](#setup)
- [Components](#components)

## Goal

Give students the same feedback upon assignment submission that they'd typically receive when pushing a commit in the workplace as a junior software engineer.

## Setup

- When creating a Programming Assignment on Gradescope, make sure not to ignore the `.git` directory. This directory is is used to determine statistics about the submission.

## Components

In addition to ensuring that the code successfully builds and executes, instructors may consider integrating the following tests into their workflow:

### Linters

- Commit message format
- Language and framework based linters

### Test Runners

- Run any tests found in files or directories that contain `test`.
- Run a coverage test based on the project's stack.

### Tests for All Submissions

In addition to instructor-written and student-written tests within the codebase, all submissions should report the following best practice tests to students:

- How many commits were made on the project.
- Make sure a `README` file exists and has a minimum of 300 words.

### Autograder Script

**Instructors must write code that performs the following tasks when autograding**:

- Initializes and executes each component mentioned above (linter, test runner, etc.)
- Constructs a `results.json` file that is delivered to students upon grading. This JSON output should contain **an easy to read summary** of the results of all components listed above.
- Written in Python using [gradescope/autograder-utils](https://github.com/gradescope/autograder-utils).
