# Contributing to alexvanwolferen Projects

Thank you for your interest in contributing to our projects! We welcome contributions from the community and are grateful for any help you can provide.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Pull Requests](#pull-requests)
- [Development Guidelines](#development-guidelines)
  - [Coding Standards](#coding-standards)
  - [Commit Messages](#commit-messages)
  - [Testing](#testing)
- [Code Review Process](#code-review-process)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to conduct@alexvanwolferen.com.

## Getting Started

1. **Fork the repository** - Create your own fork of the project
2. **Clone your fork** - `git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git`
3. **Set up the development environment** - Follow the README instructions in the specific repository
4. **Create a branch** - `git checkout -b feature/your-feature-name`

## How to Contribute

### Reporting Bugs

Before creating a bug report, please check existing issues to avoid duplicates. When creating a bug report, include:

- **Clear title** - A descriptive title that summarizes the issue
- **Steps to reproduce** - Detailed steps to reproduce the behavior
- **Expected behavior** - What you expected to happen
- **Actual behavior** - What actually happened
- **Environment details** - OS, .NET version, IDE, etc.
- **Screenshots** - If applicable, add screenshots to help explain the problem
- **Additional context** - Any other relevant information

### Suggesting Features

Feature requests are welcome! When suggesting a feature:

- **Check existing issues** - Ensure the feature hasn't already been requested
- **Describe the problem** - Explain what problem the feature would solve
- **Describe the solution** - Explain how you envision the feature working
- **Consider alternatives** - Describe any alternative solutions you've considered

### Pull Requests

1. **Ensure your PR addresses an issue** - Link to the relevant issue in your PR description
2. **Follow the coding standards** - See [Coding Standards](#coding-standards) below
3. **Write tests** - Add tests for new functionality
4. **Update documentation** - Update README or other docs if needed
5. **Keep PRs focused** - One feature or fix per PR
6. **Write a good description** - Explain what the PR does and why

## Development Guidelines

### Coding Standards

- Follow the [.NET coding conventions](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- Use meaningful variable and method names
- Keep methods small and focused on a single responsibility
- Add XML documentation comments for public APIs
- Use async/await for I/O-bound operations
- Follow SOLID principles

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that don't affect the meaning of the code
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools

**Examples:**
```
feat(api): add endpoint for user authentication
fix(validation): correct email regex pattern
docs: update installation instructions
```

### Testing

- Write unit tests for new functionality
- Ensure all tests pass before submitting a PR
- Aim for meaningful test coverage
- Use descriptive test names that explain what is being tested

## Code Review Process

1. **Automated checks** - Your PR will be automatically checked for build errors and test failures
2. **Maintainer review** - A maintainer will review your code for:
   - Code quality and style
   - Test coverage
   - Documentation
   - Potential issues or improvements
3. **Feedback** - You may receive feedback requesting changes
4. **Approval** - Once approved, your PR will be merged

## Community

- **Be respectful** - Treat everyone with respect and kindness
- **Be patient** - Maintainers are volunteers with limited time
- **Be helpful** - Help others who are getting started
- **Ask questions** - If you're unsure about something, ask!

Thank you for contributing! 🎉
