# 🚀 Laravel CI/CD Deployment with GitHub Actions

This repository demonstrates a **production-ready CI/CD pipeline** for deploying a **Laravel application** using **GitHub Actions** and **secure SSH-based automation**.

Designed by a **DevOps Engineer** for real-world backend deployments.

---

## ✨ Features

- 🚀 Automatic deployment on code push
- 🌍 Separate **staging** and **production** environments
- 🔐 Secure SSH authentication
- 🔄 Git-based server sync
- 🧩 Clean & maintainable pipeline structure

---

## 🚦 Branch Strategy

| Branch | Environment |
|------|------------|
| `staging` | 🧪 Staging |
| `main` | 🚀 Production |

---

## 🔄 Deployment Flow

```text
Push Code
   ↓
GitHub Actions Trigger
   ↓
SSH into Server
   ↓
Git Pull / Clone
   ↓
Application Updated
   ↓
🎉 Deployment Complete

🔐 Required GitHub Secrets (Example)

PROD_HOST

PROD_USER

PROD_SSH_KEY

STAGING_HOST

STAGING_USER

STAGING_SSH_KEY

GH_USERNAME

GH_PAT

⚠️ All secrets are stored securely in GitHub Secrets.
