# Release Notes - v1.1.3 (Official Launch Final) 🚀

This is the final official launch version of `github-finds` (`ghf`). It incorporates all critical Day 0 fixes, registry optimizations, and internal version alignments.

---

## 🚀 What's New in v1.1.3 (Internal Alignment)
- **🔢 Version Sync**: Synchronized internal CLI and API client versions to `1.1.3` to match the official package release.
- **🛡️ Full Feature Set**: Officially transitioned the project from a prototype to a production-ready CLI.

---

## ✅ v1.1.2 (Day 0 Optimization Patch)
- **⚡ Package Slimming**: Optimized the npm package by excluding source code and tests, drastically reducing install size.
- **📦 Clean Installs**: Ensured the package only includes compiled `dist/` directory for correct command execution across all environments.

---

## ✅ v1.1.1 (Registry Fix)
- **🛠️ Registry Metadata**: Fixed critical npm provenance issues by populating repository, bugs, and homepage metadata.

---

## 🌟 What's New in v1.1.0 (Stability & DX)
- **🛡️ Production Stability**: 
  - Integrated `vitest` suite for core logic and utilities.
  - Automated CI/CD pipeline with secure npm publishing.
  - Robust handling for GitHub secondary rate limits and API errors.
- **⚡ Performance**: Added a smart, short-lived file cache to speed up frequent profile and repo lookups.
- **⌨️ Enhanced DX**: 
  - **Shell Autocompletion**: Support for `bash`, `zsh`, and `fish`.
  - **Interactive Pagination**: "Load More" prompts for large lists (followers, repos, etc.).
  - **Project Rebrand**: Officially renamed to `github-finds` (`ghf`).

---

## 🛠️ Core Features (v1.0.0 Foundation)
`ghf` provides a deep, terminal-native way to explore the GitHub ecosystem:

### 👤 Social Discovery
- **Comprehensive Profiles**: View any user's bio, location, followers, and public activity.
- **Relationship Mapping**: Browse followers, following, and organization memberships.
- **Star History**: Explore your own or others' starred repositories.

### 📦 Repository & Code Management
- **Full Repo Access**: List, view (README, commits, branches), create, and delete repositories.
- **Interaction**: Star, unstar, watch, or fork repos directly from the CLI.
- **Languages & Stats**: Get detailed breakdowns of repository language usage.

### 🔀 Workflow & Collaboration
- **Pull Requests**: Create, view, merge, close, and review PRs. View changed files and comments.
- **Issues**: Full lifecycle management—create, close, and comment on issues.
- **Gists**: Manage your snippets—list, view, create, and star Gists.

### ⚡ Automation & Search
- **GitHub Actions**: Monitor workflows, view run logs, and trigger manual dispatches.
- **Global Search**: Powerful search across users, repos, code, issues, and commits.
- **Security**: Quickly list your SSH/GPG keys and verified emails.

---

## 🚀 Getting Started

### Installation
```bash
npm install -g github-finds
```

### Quick Setup
1. **Login**: `ghf auth login` (Requires a Personal Access Token).
2. **Explore**: `ghf user me` or `ghf repo view owner/repo`.
3. **Optimize**: `ghf completion <shell>` to enable autocompletion.

---

## 🤝 Contributing
Contributions are welcome! Check out our [GitHub](https://github.com/anishhs-gh/github-finds).
