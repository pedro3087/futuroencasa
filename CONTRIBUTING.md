# Contributing to FuturoEnCasa

Thank you for your interest in contributing to FuturoEnCasa! To ensure a smooth and collaborative process, we have established a set of guidelines for contributing to the project. Please take a moment to review them.

## How to Contribute

We welcome contributions in various forms, including bug reports, feature requests, documentation improvements, and code contributions.

### Reporting Issues

If you encounter a bug, have a feature idea, or find an issue with the documentation, please open an issue on our GitHub repository.

- **Search for existing issues:** Before creating a new issue, please check if a similar one already exists.
- **Provide clear details:** When creating an issue, provide a clear and descriptive title and a detailed description of the problem or suggestion. For bug reports, include steps to reproduce the issue.

### Working on Issues

If you want to work on an existing issue, please follow these steps:

1.  **Claim the issue:** Leave a comment on the issue to let others know you are working on it.
2.  **Create a new branch:** Create a new branch from `main` for your changes. Use a descriptive branch name, such as `feat/add-user-auth` or `fix/login-bug`.
    ```bash
    git checkout -b your-branch-name
    ```
3.  **Make your changes:** Implement your changes and commit them with clear and descriptive messages.

### Commit Message Guidelines

We follow a convention for commit messages to maintain a clear and organized history. Please reference the relevant issue in your commit messages.

- **Reference issues:** Use `(refs #issue-number)` at the end of your commit message to link it to an issue.
  - `git commit -m "feat: Add initial user authentication UI (refs #42)"`

- **Closing issues:** If your commit or pull request resolves an issue, use keywords like `closes`, `fixes`, or `resolves` to automatically close the issue upon merging.
  - `git commit -m "fix: Correct validation on login form. Fixes #35"`

### Submitting Pull Requests

Once your changes are ready, submit a pull request (PR) to the `main` branch.

1.  **Push your branch:**
    ```bash
    git push origin your-branch-name
    ```
2.  **Create a pull request:** Go to the repository on GitHub and create a new pull request.
3.  **Link the PR to the issue:** In the PR description, mention the issue it resolves (e.g., `Fixes #35`). This will link the PR to the issue and close it automatically when the PR is merged.
4.  **Wait for review:** Your PR will be reviewed by the maintainers. Be prepared to make changes based on the feedback.

By following these guidelines, you help us maintain a high-quality and well-documented project. Thank you for your contributions! 