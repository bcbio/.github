# Contributing Guidelines

Thank you for contributing!

We welcome contributions to improve existing reports, add new ones, or create new repositories for different data types.

---

## Improving Existing Reports

- Enhance current report templates by:
  - Improving the text or comments for clarity and accuracy.
  - Adding a new section (when needed). Make sure to test it using appropriate test data.
- Always verify your changes with test data before submitting a pull request.

---

## Adding a New Template Report

- Use the same structure as existing reports to maintain consistency.
- For test datasets, use those from:
  - [nf-core test data](https://github.com/nf-core/test-datasets)
  - [nf-core modules](https://github.com/nf-core/modules/blob/master/tests/config/test_data.config)
  - [bcbioR test-data](https://github.com/bcbio/bcbioR-test-data) repository
- Include a Method section in the report:
  - Link to the tools used.
  - Include the relevant R or Python session information.
- Once complete:
  - Add the new report to the README file and include a badge.
  - Apply code style linting:
    - For R: Use the styleR package.
    - For Python: Use your preferred linting tool (e.g., black, flake8).

---

## Adding a New Repository for Reports

If you want to create a set of reports for a new type of dataset:

- Open an issue in the GitHub meta-repo: [bcbio/.github](https://github.com/bcbio/.github/issues).
- Describe the type of data and the reports you want to build.
- We’ll collaborate with you to make it happen!

---

Thank you again for helping improve the project! ❤️
