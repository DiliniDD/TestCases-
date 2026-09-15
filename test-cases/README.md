# Test Cases

This directory contains QA test cases for the project, migrated from AIO Tests and maintained here going forward.

## Structure

Test cases are grouped into folders by feature or module, e.g. login, checkout. Each test case is a single markdown file named TC-NNN-short-title.md.

## Adding a new test case

1. Copy TEMPLATE.md into the relevant module folder.
2. Rename it to TC-next-number-short-title.md.
3. Fill in the frontmatter and body.

## Frontmatter fields

- id: test case identifier, keep the original AIO id where applicable
- title: short descriptive title
- priority: high, medium, or low
- module: feature area the test case belongs to
- automated: true or false
- tags: free-form labels for filtering, e.g. smoke, regression

## Tracking execution

Test execution results, pass or fail per release, are tracked via GitHub Issues or Projects, not by editing the test case files directly.
