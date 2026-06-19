# New Repository Checklist

Use this checklist when setting up a new repository in the CitizenWeather organization.

## 📋 Initial Setup

- [ ] Create repository in organization
- [ ] Set appropriate visibility (public/private)
- [ ] Add description and topics
- [ ] Set repository as template (if applicable)
- [ ] Add link to organization in README

## 📝 Documentation

- [ ] Create comprehensive README.md
- [ ] Add installation instructions
- [ ] Include usage examples
- [ ] Document API or CLI if applicable
- [ ] Create CONTRIBUTING.md (can reference `.github/CONTRIBUTING.md`)
- [ ] Add LICENSE file (reference `.github/LICENSE`)
- [ ] Create CHANGELOG.md

## 🛡️ Security

- [ ] Add `.github/SECURITY.md` link to security policy
- [ ] Enable branch protection on main
- [ ] Require code reviews before merge
- [ ] Require status checks to pass
- [ ] Dismiss stale reviews when new commits pushed
- [ ] Require branches to be up to date

## 🔄 Workflows and Automation

- [ ] Copy relevant workflows from `.github/workflows/`
- [ ] Set up CodeQL scanning
- [ ] Configure Dependabot
- [ ] Set up CI/CD pipeline
- [ ] Configure auto-formatting/linting
- [ ] Set up test coverage reporting
- [ ] Configure badge generation

## 📂 Directory Structure

- [ ] `/src` — Source code
- [ ] `/tests` — Test files
- [ ] `/docs` — Documentation
- [ ] `/examples` — Example usage
- [ ] `/scripts` — Utility scripts

## 🏷️ Labels

Create standard labels:

- `bug` — Something isn't working
- `enhancement` — New feature or improvement
- `documentation` — Documentation updates
- `good first issue` — Good for newcomers
- `help wanted` — Need assistance
- `question` — Question or discussion
- `wontfix` — Won't be fixed
- `blocked` — Blocked by something
- `dependencies` — Dependency updates
- `stale` — Inactive for extended period

## 👥 Permissions and Teams

- [ ] Add maintainers team with admin access
- [ ] Add contributors team with write access
- [ ] Add appropriate teams for code owners
- [ ] Create CODEOWNERS file (if applicable)

## 📚 Issue and PR Templates

- [ ] Copy issue templates from `.github/ISSUE_TEMPLATE/`
- [ ] Copy PR template from `.github/pull_request_template.md`
- [ ] Customize templates for project-specific needs

## 🔧 Project Configuration

- [ ] Add `package.json` or equivalent (with proper metadata)
- [ ] Add `.gitignore` file
- [ ] Add `.editorconfig` file
- [ ] Add `.prettierrc` or linting config
- [ ] Add testing configuration

## 🚀 First Release Prep

- [ ] Write initial CHANGELOG entry
- [ ] Set version (0.1.0 or 1.0.0)
- [ ] Create release notes
- [ ] Tag first release
- [ ] Publish to registry if applicable

## 📢 Launch Checklist

- [ ] Announcement in discussions
- [ ] Update organization README
- [ ] Add to project list/documentation
- [ ] Share with team
- [ ] Request feedback from community

## 🔗 Integration

- [ ] Add to organization GitHub Pages site
- [ ] Link from related projects
- [ ] Add to README of related projects
- [ ] Update any central documentation

## 👀 Ongoing Maintenance

- [ ] Monitor for issues and PRs daily/weekly
- [ ] Keep dependencies updated
- [ ] Review and address security alerts
- [ ] Update documentation as needed
- [ ] Celebrate contributor achievements
- [ ] Plan releases and milestones

## 💡 Tips

- Start with a solid README — it's your project's first impression
- Write tests from day one — saves time in the long run
- Use consistent naming conventions
- Document decisions in ADRs (Architecture Decision Records)
- Keep the community engaged with regular updates
- Don't be afraid to ask for help
- Celebrate contributions and thank your community

---

**Questions?** Check [CONTRIBUTING.md](./CONTRIBUTING.md) or open a discussion.
