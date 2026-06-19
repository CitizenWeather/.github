# CitizenWeather Organization Guide

Welcome to the CitizenWeather organization! This document provides guidance on how our organization is structured and how to work within it.

## Organization Structure

### Teams

- **@citizenweather/maintainers** — Core project maintainers
- **@citizenweather/contributors** — Active contributors
- **@citizenweather/triagers** — Issue and PR triagers
- **@citizenweather/security** — Security team

## Repository Organization

### Repository Categories

#### 🔧 Core Projects
Main projects that make up the CitizenWeather platform.

#### 📦 Libraries
Reusable libraries and packages for CitizenWeather ecosystem.

#### 📚 Documentation
Documentation, guides, and learning resources.

#### 🤖 Automation
Automation scripts, CI/CD tools, and DevOps resources.

#### ✨ Examples
Example projects and code samples.

#### 🗂️ Configuration
Organization-wide configuration (this repository).

## Development Workflow

### Branch Naming Conventions

- `main` — Stable, production-ready code
- `develop` — Integration branch for features
- `feature/description` — New features
- `bugfix/description` — Bug fixes
- `hotfix/description` — Urgent production fixes
- `docs/description` — Documentation updates
- `refactor/description` — Code refactoring

### Commit Message Conventions

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): description

[optional body]

[optional footer]
```

**Types**:
- `feat` — New feature
- `fix` — Bug fix
- `docs` — Documentation
- `style` — Code style (formatting, missing semicolons, etc.)
- `refactor` — Code refactoring
- `perf` — Performance improvement
- `test` — Tests
- `ci` — CI/CD changes
- `chore` — Other changes (dependencies, tooling)

**Example**:
```
feat(auth): add JWT token refresh endpoint

Implements automatic token refresh to improve security
and user experience.

Closes #123
```

## Code Review Process

### Pull Request Review

1. **Automated Checks** — Tests, linters, and security scans must pass
2. **Code Review** — At least one maintainer reviews the code
3. **Feedback** — Address any feedback or suggestions
4. **Approval** — Once approved, PR can be merged
5. **Merge** — Squash and merge for clean history

### Review Expectations

- Reviews should be constructive and respectful
- Focus on code quality, not personal style
- Suggest improvements when possible
- Acknowledge good work and learning opportunities

## Release Process

### Version Numbering

We follow [Semantic Versioning](https://semver.org/):

- `MAJOR.MINOR.PATCH` (e.g., `1.2.3`)
- `MAJOR` — Breaking changes
- `MINOR` — New features (backward compatible)
- `PATCH` — Bug fixes

### Release Steps

1. Update version in package.json or setup.py
2. Update CHANGELOG.md
3. Create a release tag
4. Generate release notes
5. Publish release artifacts
6. Announce release

## Communication

### Where to Ask Questions

- **GitHub Issues** — Bug reports and feature requests
- **GitHub Discussions** — Questions, ideas, and general discussion
- **Security Issues** — security@citizenweather.org (private)
- **Code of Conduct Issues** — conduct@citizenweather.org (private)

### Meetings and Synchronous Communication

- Regular team meetings (schedule TBD)
- Office hours for contributors
- Community calls (monthly)

## Getting Help

### Resources

- [Contributing Guidelines](./CONTRIBUTING.md)
- [Code of Conduct](./CODE_OF_CONDUCT.md)
- [Security Policy](./SECURITY.md)
- [Documentation](https://docs.citizenweather.org)

### Asking for Help

Don't hesitate to ask! The best place depends on your question:

- **How do I...?** → GitHub Discussions or Docs
- **This doesn't work** → GitHub Issues
- **I have an idea** → GitHub Discussions or Feature Request
- **Security concern** → security@citizenweather.org

## Maintainer Responsibilities

Maintainers are responsible for:

- Reviewing pull requests promptly
- Triaging and labeling issues
- Keeping documentation current
- Maintaining code quality
- Supporting contributors
- Making architectural decisions
- Releasing new versions
- Communicating with the community

## Standards and Best Practices

### Code Quality

- Write clean, readable code
- Follow project style guides
- Add tests for new features
- Keep functions focused and small
- Use meaningful variable names

### Documentation

- Document public APIs
- Include usage examples
- Keep README current
- Update CHANGELOG
- Comment complex logic

### Security

- Never commit secrets
- Keep dependencies updated
- Run security scans
- Follow secure coding practices
- Report vulnerabilities privately

### Performance

- Consider performance implications
- Profile before optimizing
- Document performance-critical code
- Monitor in production

## Community Guidelines

### Respect

- Treat all community members with respect
- Listen to different perspectives
- Be patient with newcomers
- Provide constructive feedback

### Inclusivity

- Welcome contributors from all backgrounds
- Use inclusive language
- Support diverse perspectives
- Create a welcoming environment

### Collaboration

- Share knowledge and expertise
- Help newer contributors
- Review code thoughtfully
- Celebrate successes

## Recognition

We believe in recognizing contributions:

- Release notes mention contributors
- Recognition in project README
- Community spotlights
- Thank you messages

## Changes to This Guide

This organization guide may be updated as we grow. Changes will be:

1. Discussed in an issue
2. Reviewed by the maintainers team
3. Merged via pull request
4. Announced to the community

---

Thank you for being part of the CitizenWeather community! 🌍
