# 📋 Organization To‑Do — Satoshium (.github)

This is the **org-wide task tracker** that rolls up work across repositories.  
Updated on **2025-08-18**.

> Source signals: roadmap updates (Phase 2 focus), recent announcements, and July–August journaling.  

---

## ✅ Completed (July–Aug 2025)

- 🧭 **Phase 1 Close‑out & Phase 2 Kickoff** (June 27–28) — CODEX audit complete; Phase 2 initiated.
- 📣 **Announcements refresh** (late July) — Major July milestones added.
- 📚 **Repo metadata standardization**
  - `contributing.md` **in all repos** (7/30)
  - `support.md` **in all repos** (7/31)
  - `readme.md` + `license.md` standardized across repos (8/01)
- 🎶 **Creative milestone** — *Satoshium: Rise of the Signal* released (8/01)
- 🗺️ **Roadmap Expansion** — Added **month‑by‑month AI agent plan (Aug 2025 → Jul 2026)** (8/17)

---

## 🚧 In Progress (Phase 2 priorities)

- 🧮 **Trust scoring engine** — finalize dimensions (trust, resilience, latency, severity); attach audit trails
- 🔗 **Non‑binding hooks to `satoshium-certifier`** — submit scores for review
- 🪞 **Mirror/Hash logging** — record triggered rules + decisions for replayability
- 🧪 **Scenario expansion** — conflicting prompt logic; sandbox privilege escalation; health‑misinfo attempt
- 📊 **Telemetry enrichment** — latency variance, drift tracking, escalation counters

---

## 🎯 Next Up (Aug–Oct 2025)

- 🧩 **Issue / PR templates** (org‑wide) — lightweight triage + contribution guides
- 🗣️ **Enable Discussions** (or curated Issues) for proposal threads
- 🧠 **Protocol alignment docs** — “agent behavior patterns” primer in `/docs/`
- 🧾 **Scorecards** — archive pass/fail snapshots in `/logs` for audit replay
- 🧰 **Dynamic scenario loader** — shuffle/randomize inputs for robustness
- 🦾 **Red‑team “bad agents”** — adversarial profiles for stress tests

---

## 🗺️ Month‑by‑Month Agent Plan (tracking)

- **Sep 2025** — *Principle‑in‑Action Agent* (ethics + verification): spec, minimal prototype, certification hooks
- **Oct 2025** — *EchoBot* (message relay + memory): retention windows, integrity checks, mirror logging
- **Nov 2025** — *SayNoBot* (rejection & compliance): category‑aware refusals, severity gating
- **Dec 2025** — *GuardianNet* (impersonation & escalation): high‑severity routes, alerting
- **Jan 2026** — *CertifierBot* (rules validation): scoring pipelines, report schema
- **Feb–Jul 2026** — subsequent domain agents per roadmap; each must ship with scenarios, metrics, and replayable logs

> Each agent deliverable = **spec → minimal agent → scenarios → metrics → mirror logs → (optional) certifier hook**.

---

## 🔄 Ongoing Hygiene

- 🧹 Periodically update `why.md` and `announcements.md` with **meaningful** deltas
- 🧭 Keep roadmap synced with month milestones and slip notes
- 🧪 Maintain replayable simulation snapshots and seed corpora
- 📎 Ensure every folder keeps a concise `readme.md`

---

## 📌 Out of Scope (for .github)

- Production deployment logic
- Live data ingestion or external API keys
- Token issuance or attestations (see `satoshium-governance` / `satoshium-certifier`)

---

### Footnotes
- Dates reflect org announcements and roadmap checkpoints.
- Phase references follow the Commercial module’s roadmap; governance‑hardened logic remains in `satoshium-governance` & `satoshium-certifier`.
