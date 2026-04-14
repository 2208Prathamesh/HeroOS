# Contributing to HeroOS 🚀

Thank you for your interest in contributing to HeroOS.

HeroOS is being built as an ambitious operating system and ecosystem project, and every contribution—whether code, documentation, design, or ideas—helps move the project forward.

Please read this guide before contributing.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Branch Naming Convention](#branch-naming-convention)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Coding Standards](#coding-standards)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Bug Reports](#bug-reports)
- [Feature Requests](#feature-requests)
- [Need Help?](#need-help)

---

## Code of Conduct

By participating in this project, you agree to maintain a respectful, professional, and collaborative environment.

Please:

- Be respectful to all contributors
- Give constructive feedback
- Keep discussions professional
- Help maintain a welcoming community

Harassment, toxicity, or disrespectful behavior will not be tolerated.

---

## Ways to Contribute

You can contribute in many ways:

### Code
- Fix bugs
- Add new features
- Improve performance
- Refactor existing code
- Improve security

### Non-Code
- Improve documentation
- Suggest features
- Report bugs
- Design UI/UX improvements
- Write tutorials/examples

---

## Getting Started

### 1. Fork the Repository

Fork the HeroOS repository to your GitHub account.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/heroos.git
cd heroos
```

### 3. Add Upstream Remote

```bash
git remote add upstream https://github.com/HeroOS/heroos.git
```

### 4. Install Dependencies

```bash
npm install
```

### 5. Run Development Server

```bash
npm run dev
```

---

## Development Workflow

1. Sync your fork with upstream
2. Create a new branch
3. Make changes
4. Test your changes
5. Commit with proper messages
6. Push to your fork
7. Open a Pull Request

---

## Branch Naming Convention

Use descriptive branch names:

```bash
feature/short-description
bugfix/short-description
docs/short-description
refactor/short-description
```

### Examples

```bash
feature/login-system
bugfix/navbar-overlap
docs/update-installation-guide
refactor/api-service
```

---

## Commit Message Guidelines

Use structured commit messages:

```bash
type(scope): short description
```

### Examples

```bash
feat(auth): add JWT authentication
fix(ui): resolve sidebar overflow
docs(readme): improve setup instructions
refactor(core): optimize boot process
```

### Allowed Types

- feat
- fix
- docs
- style
- refactor
- perf
- test
- chore

---

## Coding Standards

Please follow these standards:

- Write clean and readable code
- Use meaningful variable/function names
- Keep functions modular and reusable
- Follow existing project architecture
- Avoid unnecessary complexity
- Comment only where necessary

### Before Submitting

Run:

```bash
npm run lint
npm run format
```

Ensure:

- No lint errors
- Code is properly formatted
- Build passes successfully

---

## Pull Request Guidelines

When opening a Pull Request:

### Include

- Clear PR title
- Detailed description of changes
- Related issue reference (if any)
- Screenshots for UI changes (if applicable)

### Requirements

- PR must build successfully
- PR must follow coding standards
- PR should be focused on one change/feature
- Large changes should be discussed first via issue

---

## Bug Reports

When reporting bugs, include:

- Environment / OS / Browser
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots / Logs (if available)

Please use the **bug** label when creating issues.

---

## Feature Requests

When suggesting a feature, include:

- Problem being solved
- Proposed solution
- Alternative solutions considered
- Mockups / References (optional)

Please use the **enhancement** label when creating issues.

---

## Need Help?

If you need assistance:

- Open a GitHub Issue
- Start a GitHub Discussion
- Contact project maintainers

---

## Contributor License

By contributing to HeroOS, you agree that your contributions will be licensed under the same license as the project.

---

## Thank You

Your contributions help shape the future of HeroOS.

Together, we are building something exceptional. ⚡
