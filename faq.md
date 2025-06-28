
# ❓ Frequently Asked Questions (FAQ)

This file addresses common questions about the Satoshium project and its GitHub repository structure.  
It serves both new contributors and curious observers of our decentralized AI infrastructure effort.

---

## 🤖 What is Satoshium?

Satoshium is a decentralized intelligence infrastructure governed by Bitcoin.  
It is composed of multiple coordinated repositories, agents, and protocols intended to enable censorship-resistant, logic-driven AI systems built on cryptographic rules.

---

## 🧱 Why are there so many repositories?

Satoshium emphasizes **modular architecture**.  
Each repo plays a distinct role—examples include:

- `satoshium-core`: Base constants, schemas, and internal logic
- `satoshium-specs`: Specifications and standards for agents, models, and logic
- `satoshium-ui`: Frontend user interfaces
- `satoshium-agents`: Internal system agents like `system-maintainer`, `audit-helper`, etc.
- `satoshium-scenarios`, `satoshium-certifier`, etc.: Future-stage repos focused on simulation and verification

This design allows for auditability, composability, and collaborative scaling.

---

## 🔐 How is trust enforced?

Satoshium operates under a principle of **protocol over command**.

- Internal agents follow signed rules, not instructions.
- CODEX audits define the minimum compliance threshold.
- Contributors are encouraged to preserve the principles of decentralization and transparency.

All commits are verifiable, and logs are optionally stored in `/logs/`.

---

## 🧪 How can I test or simulate agents?

Use the `satoshium-demos`, `satoshium-simulations`, or `satoshium-agent-lab` repositories.  
Each contains test scaffolds, simulations, or execution environments.  
Check each repo's `/docs/` folder and README for detailed walkthroughs.

---

## 🙋 How can I contribute?

Please review the following:

- [CODE OF CONDUCT](../code-of-conduct.md)
- [CONTRIBUTING GUIDE](../contributing.md)
- [COMMUNITY GUIDELINES](../community.md)

Fork, propose, test, and help us build a better intelligence infrastructure.

---

## 📩 Still have questions?

Open an issue or reach out via discussions in the `satoshium-interface` repo.

---

## 🔁 File Update Cycle

This FAQ is updated as new contributors join and new questions arise.  
Feel free to submit PRs with suggested clarifications or additions.

