# 🤖 OpenRely (.github) Operating Protocols & Guidelines

> This document defines the operational protocols and engineering guidelines (AGENTS.md) for the `OpenRely/.github` special repository. All AI Agents operating in this repository must strictly adhere to these rules.

---

## 🚫 1. Strict Workspace Boundary

- 🔒 **Single Repository Scope**: All code modifications, documentation updates, branch checkouts, and PR activities are strictly restricted to the `OpenRely/.github` repository.
- ⛔ **No Unauthorized Cross-Repo Edits**: Agents must never touch or modify sibling repositories without explicit user instruction.

---

## 🏛️ 2. Repository Responsibilities

This repository acts as the GitHub Special Repository (`.github`) for the entire OpenRely organization:
1. **Organization Profile**: Maintains `profile/README.md` as the public landing page on `github.com/OpenRely`.
2. **Default Community Templates**: Manages `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md` inherited by all OpenRely repositories.
3. **Governance & Standards**: Enforces `SECURITY.md`, `CODE_OF_CONDUCT.md`, and reusable CI/CD workflows.

---

## 📌 3. Git Conventions & Commit Disciplines

### 3.1 Atomic Commits (Commit per Feature)
- Each commit must represent a single logical unit of change.
- Never batch unrelated features, style fixes, and workflow scripts into one monolithic commit.

### 3.2 Conventional Commits Format
All commit messages must follow standard Conventional Commits:
`<type>(<scope>): <subject>`

- `feat`: New feature or template addition
- `fix`: Bug fix in workflow or template syntax
- `docs`: Documentation updates (README, Profile, Guidelines)
- `ci`: GitHub Actions workflow changes
- `chore`: Governance or maintenance updates

### 3.3 Branch & PR Workflow
- Branch naming: `feat/<issue-or-topic>`, `fix/<topic>`, `docs/<topic>`
- PR target: `dev` branch for active integration, fast-forwarding to `main` for releases.
