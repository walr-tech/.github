# 🧬 Walr-Tech GitHub Organization

Welcome to **`walr-tech`**, the central GitHub organization for all engineering efforts at Walr. This org contains the source code, infrastructure, and workflows powering our products, platform, and internal tooling.

---

## 🧭 Purpose

This organization is used to:

- Host application code and shared libraries
- Manage infrastructure-as-code using Bicep (and eventually Terraform)
- Run CI/CD pipelines via GitHub Actions
- Organize development teams and enforce code governance

---

## 🏗️ Structure

- **Repositories** follow naming standards and include `CODEOWNERS`, branch protection, and standardized CI/CD workflows
- **Teams** are synced from Azure Entra ID and structured by product domain (e.g. `team-voyager`, `platform-engineering`)
- **Templates** are used for consistent project scaffolding

---

## 🔐 Access & Security

- Access is controlled via Entra ID groups synced to GitHub Teams
- SSO and 2FA are enforced across all members
- Public repositories are disabled by default

---

## 🚀 Environments

Repositories may define the following deployment environments:

- `dev`, `staging`, `production` — each protected via GitHub Actions environment rules

---

## 📥 Onboarding

- Get added via your Entra ID team group
- Join relevant GitHub Teams
- Speak to Platform Engineering about your repository or workflow requirements
- Review the Developer and GitHub Best Practices Wiki
