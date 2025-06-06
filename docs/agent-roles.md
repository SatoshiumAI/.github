# 🧠 Satoshium Agent Roles

Satoshium defines four modular agent roles that work independently or together to support decentralized, cryptographically constrained intelligence. These roles are permissioned by logic — not identity — and exist to carry out bounded functions under trustless verification.

Each role plays a distinct part in the agent lifecycle, from input validation to final output.

---

## 🔧 1. Executor Agent

**Function**:  
Carries out specific actions or tasks based on pre-approved logic.

**Use Cases**:
- Responding to user prompts
- Executing on-chain events or transactions
- Triggering automated workflows

**Constraints**:
- Cannot operate outside its assigned scope or role
- Cannot act without Guard verification
- May include cooldowns, rate limits, and time locks

**Example**:  
A publishing agent that posts a signed message to Nostr if a Bitcoin address receives a threshold payment.

---

## 🛡️ 2. Guard Agent

**Function**:  
Validates the inputs, scope, and legality of Executor agent actions before they proceed.

**Use Cases**:
- Preventing overreach or unauthorized tasks
- Checking message integrity, inputs, or time window
- Blocking agents from violating logic constraints

**Constraints**:
- Cannot approve tasks on its own — only verify or deny
- Must reference verifiable logic or policy layers

**Example**:  
A Guard agent that rejects a file write operation if the agent’s assigned permissions do not include I/O access.

---

## 🔗 3. Messenger Agent

**Function**:  
Securely transmits information between agents or from agents to users, protocols, or external systems.

**Use Cases**:
- Posting verified output to Nostr, IPFS, or HTTP endpoints
- Sending logs or status signals to multi-agent environments
- Relaying proposals, requests, or reports

**Constraints**:
- Cannot alter content (must transmit only what is signed/authorized)
- Must encrypt and/or sign messages as required by the receiving protocol

**Example**:  
A Messenger agent that relays a timestamped report from a Governance agent to an off-chain dashboard.

---

## 🧭 4. Governance Agent

**Function**:  
Monitors agent performance, manages lifecycle state, and enforces protocol upgrades or forks.

**Use Cases**:
- Triggering version updates or constraints across agent clusters
- Coordinating quorum votes or multi-signature events
- Signaling critical errors or conditions for pause/self-destruction

**Constraints**:
- Cannot execute user-facing actions directly
- Must rely on voting logic, policy references, or external consensus

**Example**:  
A Governance agent that pauses a rogue Executor agent after three Guard denials in under one hour.

---

## 🔄 Role Interactions (Example Flow)

1. **User Input →**  
2. **Executor proposes action →**  
3. **Guard validates logic, scope, and timing →**  
4. **Messenger relays signed output →**  
5. **Governance logs execution or intervenes if constraints are violated**

---

## 🌱 Future Roles (Exploratory)

- **Observer Agents** – Passive listeners that watch blockchain events or external APIs  
- **Bridge Agents** – Specialized Messengers that sync state between Bitcoin and non-Bitcoin environments  
- **Oracle Guards** – Validate data coming from oracles using multi-source attestation

---

## 🔐 Role Integrity

All Satoshium agents must adhere to:
- Signed logic constraints (e.g., Git commit hashes, IPFS policy objects)
- Permission boundaries assigned at initialization
- Accountability through timestamped logs or on-chain checkpoints

> Agents do not improvise.  
> They verify, execute, or pause. Nothing more.

---

