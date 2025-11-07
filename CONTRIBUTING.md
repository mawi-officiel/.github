# 🤝 Contributing to MAWI MAN Projects

Welcome to the MAWI MAN ecosystem! We appreciate your interest in contributing to our projects. This document provides guidelines and instructions for contributing to any repository under the MAWI MAN organization.

## 🎯 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## 🚀 Getting Started

### Prerequisites

- Git installed on your machine
- Node.js (if applicable to the project)
- A GitHub account
- Basic understanding of the project's technology stack

### Setting Up Your Development Environment

1. **Fork the repository** to your GitHub account
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   cd REPOSITORY_NAME
   ```
3. **Add the original repository** as upstream:
   ```bash
   git remote add upstream https://github.com/mawi-officiel/REPOSITORY_NAME.git
   ```
4. **Install dependencies** (if applicable):
   ```bash
   npm install
   # or
   yarn install
   ```

## 📋 How to Contribute

### 🐛 Reporting Bugs

1. **Search existing issues** to avoid duplicates
2. **Use the bug report template** when creating a new issue
3. **Provide detailed information** including:
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details
   - Screenshots (if applicable)

### ✨ Suggesting Features

1. **Check existing feature requests** to avoid duplicates
2. **Use the feature request template**
3. **Clearly describe** the feature and its benefits
4. **Provide mockups or examples** if possible

### 🔄 Submitting Pull Requests

1. **Create a new branch** for your feature/fix:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

2. **Make your changes** following our coding standards

3. **Test your changes** thoroughly

4. **Commit your changes** with clear, descriptive messages:
   ```bash
   git commit -m "feat: add new feature description"
   # or
   git commit -m "fix: resolve issue with specific component"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** using our PR template

## 📏 Coding Standards

### General Guidelines

- **Follow existing code style** and conventions
- **Write clear, self-documenting code**
- **Add comments** for complex logic
- **Use meaningful variable and function names**
- **Keep functions small and focused**

### Commit Message Format

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```
feat(auth): add user authentication system
fix(ui): resolve button alignment issue
docs(readme): update installation instructions
```

## 🧪 Testing

- **Write tests** for new features and bug fixes
- **Ensure all tests pass** before submitting PR
- **Maintain or improve code coverage**
- **Test across different environments** when applicable

## 📚 Documentation

- **Update documentation** for any changes
- **Add inline comments** for complex code
- **Update README** if necessary
- **Include examples** for new features

## 🔍 Code Review Process

1. **Automated checks** must pass (CI/CD, linting, tests)
2. **Code review** by maintainers
3. **Address feedback** promptly
4. **Approval and merge** by project maintainers

## 🏷️ Issue and PR Labels

- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements or additions to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed
- `needs-review`: Requires review from maintainers
- `priority-high`: High priority item
- `priority-low`: Low priority item

## 🤔 Questions and Support

If you have questions about contributing:

1. **Check existing documentation** and issues
2. **Create a discussion** in the repository
3. **Contact us** at [ayoub@mawiman.com](mailto:ayoub@mawiman.com)

## 🙏 Recognition

All contributors will be recognized in our project documentation and release notes. We appreciate every contribution, no matter how small!

## 📄 License

By contributing to MAWI MAN projects, you agree that your contributions will be licensed under the same license as the project.

---

**Thank you for contributing to MAWI MAN projects!**

**© MAWI MAN (Ayoub Alarjani)** — All Rights Reserved