# 🛠️ Installation Guide

Welcome to Satoshium. This guide walks you through setting up and installing the tools, dependencies, and environments required to contribute to or interact with Satoshium repositories.

---

## 📦 Prerequisites

Before proceeding, ensure you have the following installed on your machine:

- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)
- [Node.js + npm](https://nodejs.org/)
- [Poetry](https://python-poetry.org/docs/#installation) (for Python dependency management)
- [VSCode](https://code.visualstudio.com/) or preferred code editor

---

## 🧰 Initial Setup

Clone the desired repository:

```bash
git clone git@github.com:satoshiumai/<repo-name>.git
cd <repo-name>
```

Install Python dependencies using Poetry:

```bash
poetry install
```

Install Node dependencies (if UI or interface repo):

```bash
npm install
```

---

## 🧪 Testing the Setup

To ensure everything is working, run:

```bash
poetry run pytest
```

Or for JavaScript/TypeScript:

```bash
npm run test
```

---

## 🔁 Keeping Dependencies Updated

To update Python dependencies:

```bash
poetry update
```

To update Node dependencies:

```bash
npm update
```

---

## 📁 Repository Conventions

Each repo may have unique folder structures, but the general expectation is:

```
/docs/          → Documentation
/src/           → Core source code
/tests/         → Unit and integration tests
/scripts/       → Utilities and helpers
/logs/          → Optional logs from internal agents
```

---

## 🔐 Security Notes

- Always review `.env.example` and never commit sensitive credentials.
- Use SSH keys for secure GitHub access.

---

## 🧾 Additional Help

If you encounter installation issues, visit the [Support Documentation](support.md) or reach out through the Issues tab.

---

Happy building with Satoshium!
