# Requirements

This directory holds requirement and user story documents. Each requirement is a single markdown file with a stable ID, e.g. REQ-001.

## Adding a new requirement

Create a file named REQ-NNN-short-title.md with an id, title, and status in the frontmatter, followed by a description and a Covered by test cases section.

## Linking test cases and requirements

Traceability is kept visible from both sides:

- Each requirement file lists the test cases that verify it, under a Covered by test cases section, linked by relative path.
- Each test case's frontmatter includes a requirements field listing the requirement IDs it verifies, and the test case body links back to the requirement file.

When a new test case is added for an existing requirement, update both files so the links stay in sync.
