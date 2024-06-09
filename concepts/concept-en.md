# Concepts for Open Source Contribution

Understanding the core concepts and terminologies in open source contribution is essential for effective collaboration and contribution. Below are some key concepts:

## Upstream/Downstream

### Upstream

- **Definition:** The original repository or source of the project where the core development happens.
- **Purpose:** Changes and improvements made by contributors are usually pushed to the upstream repository.
- **Example:** If you fork a repository from `https://github.com/original/repo`, the `original/repo` is considered upstream.

### Downstream

- **Definition:** The forked version of the repository that you create and work on.
- **Purpose:** Your local copy or forked repository where you apply your changes before merging them back to the upstream repository.
- **Example:** When you fork `https://github.com/original/repo` to `https://github.com/your-username/repo`, your fork is downstream.

## Issue

### Definition

- **Description:** A means to report bugs, request features, ask questions, or suggest improvements in the project.
- **Purpose:** Helps maintainers keep track of tasks and helps contributors understand what needs to be worked on.
- **Example:** Creating an issue titled "Add dark mode feature" to request a new feature in the project.

## Pull Request (PR)

### Definition

- **Description:** A method to submit contributions to an open source project. A PR lets you propose changes to the codebase, which can then be reviewed, discussed, and merged by the project maintainers.
- **Purpose:** Facilitates collaboration by allowing others to review your changes before they become part of the main project.
- **Example:** After making changes to the code in your fork, you create a PR to propose those changes to be merged into the upstream repository.

### Reviewing and Merging a Pull Request

- **Review**: Project maintainers review the changes, suggest improvements, or ask questions.
- **Approval**: Once the PR is reviewed and approved, it can be merged into the upstream repository.
- **Merge**: The maintainer or the contributor (if allowed) merges the PR.
- **Cleanup**: Delete the branch after merging to keep the repository clean.

## Contribution Cycle

The contribution cycle in an open source project involves the following steps:

1. **Fork the Repository**: Create a copy of the original repository (upstream) to your GitHub account (downstream).
2. **Clone the Repository**: Download the forked repository to your local machine.
3. **Create a Branch**: Make a new branch for the feature or bug fix you want to work on.
4. **Make Changes**: Implement the desired changes in your local branch.
5. **Commit Changes**: Save your changes with a meaningful commit message.
6. **Push Changes**: Upload your branch to your forked repository on GitHub.
7. **Create a Pull Request**: Propose your changes to the upstream repository by creating a PR.
8. **Review Process**: Your PR is reviewed by project maintainers who may request modifications.
9. **Approval and Merge**: Once approved, the PR is merged into the upstream repository.
10. **Cleanup**: Optionally, delete the branch after merging.

## Summary

- **Upstream:** The main repository where the original development occurs.
- **Downstream:** Your forked repository where you apply changes.
- **Issue:** A way to report problems, request features, or ask questions.
- **Pull Request:** A method to propose changes to the codebase and facilitate collaboration through reviews and discussions.
- **Contribution Cycle:** The process of making contributions, from forking the repository to merging changes back into the upstream repository.

Understanding these concepts is fundamental to effectively contributing to open source projects and collaborating with other developers.
