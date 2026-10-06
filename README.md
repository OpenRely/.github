# 🏛️ OpenRely · Organization Governance Hub (`.github`)

> **Repository Role**: This is the official **GitHub Special Repository (`.github`)** for the **OpenRely** organization.  
> It centrally hosts the **Organization Profile**, **Default Issue & PR Templates**, **Global Security Policy**, **Code of Conduct**, and **Shared Reusable CI/CD Workflows** across all repositories under `github.com/OpenRely`.

---

## 🌟 Organization-Wide Features

1. **Organization Profile (`profile/README.md`)**:
   - Renders as the official front-page banner on [github.com/OpenRely](https://github.com/OpenRely).
   - Highlights flagship open-source projects, core philosophies, and community entry points.

2. **Default Issue Forms (`.github/ISSUE_TEMPLATE/`)**:
   - Automatically inherited by **all repositories** under OpenRely that do not define custom issue templates:
     - 🪲 `bug_report.yml`: Standardized defect and bug triage form.
     - 💡 `feature_request.yml`: Structured capability and enhancement proposal form.
     - 📖 `documentation.yml`: Community documentation correction and improvement form.
     - ⚙️ `config.yml`: Global configuration directing discussions and security disclosures.

3. **Default Pull Request Template (`.github/PULL_REQUEST_TEMPLATE.md`)**:
   - Automatically pre-fills a 3-tier review template (Why / What / Impact & Verification) for all incoming Pull Requests across the organization.

4. **Community Health & Security**:
   - [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md): Contributor Covenant 2.1 standard.
   - [`SECURITY.md`](./SECURITY.md): Coordinated vulnerability disclosure guidelines.
   - [`LICENSE`](./LICENSE): Apache License 2.0 with Trademark protection disclaimer.

---

## 📁 Repository Layout

```text
.github/
├── README.md                      # Repository overview and documentation
├── AGENTS.md                      # AI Agent operating protocols & guidelines
├── LICENSE                        # Apache License 2.0 with Trademark disclaimer
├── SECURITY.md                    # Organization-wide security vulnerability policy
├── CODE_OF_CONDUCT.md             # Contributor Covenant Code of Conduct v2.1
├── profile/
│   └── README.md                  # Public-facing Organization Profile card
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.yml         # Standard bug report issue form
    │   ├── feature_request.yml    # Standard feature request issue form
    │   ├── documentation.yml      # Documentation improvement issue form
    │   └── config.yml             # Global community links & settings
    ├── PULL_REQUEST_TEMPLATE.md   # Default PR checklist template
    └── workflows/
        ├── markdown-check.yml     # Syntax and reference dead-link check
        └── release.yml            # Automated tag release packager
```
