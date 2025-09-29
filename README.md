# RDK Central Organization Profile

This repository contains the organization-wide profile and community health files for **RDK Central** - the open source consortium managing the Reference Design Kit (RDK).

## 📁 Repository Structure

```
.github/
├── .github/                   # Templates that inherit to org repositories
│   ├── ISSUE_TEMPLATE/
│   │   ├── 01-bugs.yml        # Bug report template
│   │   ├── 02-features.yml    # Feature request template
│   │   ├── 03-tasks.yml       # Task/enhancement template
│   │   └── config.yml         # Issue template configuration
│   └── CODEOWNERS             # Default code owners for org repos
├── profile/
│   └── README.md              # Organization profile (displayed on GitHub)
├── workflow-templates/
│   ├── rdk-ci.yml            # RDK CI/CD pipeline with BitBake/Yocto support
│   └── rdk-ci.properties.json # Workflow template metadata
├── CODE_OF_CONDUCT.md        # Repository governance guidelines
├── CONTRIBUTING.md           # RDK contribution process and CLA requirements
├── SECURITY.md              # Security reporting guidelines
├── SUPPORT.md               # RDK support resources and membership information
└── pull_request_template.md  # Pull request template
```

## 🌟 Organization Profile

The main organization profile is displayed on the RDK Central GitHub organization page and provides:

- **Accurate RDK Information**: Real content from rdkcentral.com and wiki.rdkcentral.com
- **RDK7 Architecture**: Latest modular, multi-layered design information
- **Component Details**: RDK-V, RDK-B, RDK-C profiles with official descriptions
- **Lightning 3.0 & Firebolt**: Information about the latest UI framework and application platform
- **Community Resources**: Links to official RDK Wiki, forums, and support
- **Membership Information**: Details about joining the 600+ company RDK community

## 📋 Issue Templates

Organization-level templates that inherit to repositories:

- **01-bugs.yml**: Bug report template for RDK issues
- **02-features.yml**: Feature request template for RDK enhancements
- **03-tasks.yml**: Task and development enhancement template
- **config.yml**: Issue template configuration with contact links

## 🔄 GitHub Actions

Pre-configured GitHub Actions workflows specifically for RDK development:

- **RDK CI/CD Pipeline**: Complete BitBake/Yocto build system support
- **TDK Integration**: Test Development Kit automated testing
- **Multi-Profile Support**: RDK-V, RDK-B, RDK-C, Thunder, Lightning
- **Security Scanning**: CVE scanning and license compliance
- **Cross-Platform Builds**: Support for various chipsets and platforms

## 📜 Community Health Files

- **Repository Governance**: Technical governance and maintainer responsibilities
- **Contributing Guidelines**: RDK-specific contribution process with CLA requirements
- **Security Guidelines**: Links to official RDK security reporting process
- **Support Resources**: Official RDK Wiki, forums, and membership information

## 🚀 Using These Templates

### For Repository Maintainers

1. **Issue Templates**: Files in `.github/.github/ISSUE_TEMPLATE/` automatically inherit to org repositories
2. **CODEOWNERS**: Default code ownership rules apply to repositories without their own
3. **Workflow Templates**: Available when creating new workflows in any repo
4. **Community Files**: Organization-level files provide defaults for repositories without their own

### For Contributors

1. Use the appropriate issue template when reporting bugs or requesting features
2. Follow the pull request template for consistent PRs
3. Refer to CONTRIBUTING.md for contribution guidelines
4. Review CODE_OF_CONDUCT.md for community standards

## 🛠️ Customization

Repository-specific customizations:

- Repositories can override these templates with their own versions
- Templates support repository-specific variables
- Workflow templates can be customized per project needs

## 📞 Contact

- **General**: [info@rdkcentral.com](mailto:info@rdkcentral.com)
- **Membership**: [membership@rdkcentral.com](mailto:membership@rdkcentral.com)
- **RDK Support**: [Official Support Portal](https://wiki.rdkcentral.com/display/RDK/RDK+Support)

## 📚 Official RDK Resources

- **[RDK Central Website](https://rdkcentral.com)** - Main website with membership and partnership information
- **[RDK Wiki](https://wiki.rdkcentral.com)** - Primary documentation and development resource
- **[Code Management Facility](https://wiki.rdkcentral.com/display/CMF/CMF+Home)** - Code releases and repositories
- **[RDK Forums](https://wiki.rdkcentral.com/display/FORUMS/FORUMS+Home)** - Community discussions
- **[RDK Support](https://wiki.rdkcentral.com/display/RDK/RDK+Support)** - Official support portal

---

**Part of the RDK Central ecosystem - powering the future of connected devices** 🚀