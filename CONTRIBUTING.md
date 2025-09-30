# Contributing to PicoRuby

Thank you for your interest in contributing to this project! We appreciate your time and effort.

## Getting Started

1. Fork the repository
2. Clone your fork locally
3. Create a new branch for your changes
4. Make your changes and commit them
5. Push to your fork and submit a pull request

## Pull Request Guidelines

### Coding Style

Please follow these guidelines to maintain consistency across the codebase:

#### General Formatting

- **Remove trailing spaces**: Ensure no trailing whitespace at the end of lines
- **Indentation and line breaks**: Follow the same indentation style and line break conventions used in existing files of the same type
  - Check similar files in the project to match the established patterns
  - Consistency within the codebase is important

#### Comments

- **Language**: Write comments in English using ASCII characters only
- **No emojis**: Do not use emoji in comments
- **Exception**: Box-drawing characters and similar decorative glyphs (non-ASCII) are acceptable for visual formatting

Example of acceptable comment formatting:
```C
// Good: Simple English comment
// Good: Using box-drawing characters
// ┌─────────────────┐
// │ Section Header  │
// └─────────────────┘

// Bad: Using emoji 🚀
// Bad: バグフィスク <- Non-English comments
```

### Before Submitting

- Add tests for new features or bug fixes as much as possible
- Update documentation if necessary
- Make sure all tests pass locally

### Commit Messages

- Write clear, concise commit messages
- Use the present tense ("Add feature" not "Added feature")
- Reference issues and pull requests where appropriate

### Merge Policy

We follow these guidelines when merging pull requests:

- **Single commit PRs**: If your PR contains a single commit (or you've squashed your commits into one), we will use **Rebase merge** to maintain a linear history
- **Multiple commit PRs**: If your PR contains multiple commits, we will typically use **Squash merge** to combine them into a single commit
  - In some cases, maintainers may use Rebase merge at their discretion if the commit history is well-organized and meaningful

This approach helps us maintain a clean and readable commit history on the main branch.

## Reporting Issues

- Use the issue tracker to report bugs or suggest features
- Search existing issues before creating a new one
- Provide as much detail as possible (steps to reproduce, environment, etc.)

## Code of Conduct

Please be respectful and constructive in all interactions.

## Questions?

Feel free to open an issue for any questions about contributing.

Thank you for contributing!
