# Autonomous-E-Commerce-Support-Chat-App

An production-ready, real-time customer support chat application engineered entirely through autonomous AI orchestration using **Google Antigravity**. The entire development lifecycle—from spec definition to QA testing—was driven by an autonomous team of specialised agents (`@pm`, `@engineer`, `@qa`, and `@devops`).

### 🚀 The Antigravity Agentic Lifecycle
This project serves as a live demonstration of multi-agent collaboration and advanced skill engineering:
* **Multi-Agent Orchestration (`agents.md`):** Directed cross-functional AI agents natively within the Antigravity IDE to execute discrete project phases (PM scoping ➔ Engineering ➔ QA validation ➔ DevOps deployment).
* **Skill Engineering & Routing (`skills.md`):** Authored version-controlled runtime procedures with YAML frontmatter triggers, scaling the agent team's capabilities seamlessly without context rot.
* **Macro Handover Workflows:** Chained custom slash commands to automate sequential handoffs across the entire autonomous pipeline.

## ✨ Features
*Real-Time Bi-Directional Messaging:** Engineered using lightweight, high-performance Server-Sent Events (SSE) for instant, low-latency dispatch.
  **Dual User Portals:**
  **Customer Storefront (`/`):** An embedded floating widget on the *NexusGear* storefront featuring intelligent pre-chat order validation.
  * **Support Agent Console (`/agent`):** A multi-conversation management queue equipped with a customer order context pane, instant canned quick replies, and ticket state progression (`Active`, `Resolved`).
* **Simulated Concierge AI:** An automated smart responder that handles common shopper queries (order tracking, return policies, shipping rates) when live agents are occupied.
* **100% Native, Zero-Dependency Architecture:** Zero third-party module bloat. Runs cleanly on standard Node.js using an atomic file store (`data/conversations.json`) for local persistence.


## 🛠️ Core Tech Stack & Tools
* **Orchestration:** Google Antigravity IDE/CLI • Agentic AI Architectures • Skill-Driven Routing
* **Backend:** Node.js (Native Modules) • Server-Sent Events (SSE)
* **Frontend:** HTML5 • CSS3 (Floating Widget UI / Agent Console)
* **Persistence:** Local JSON Datastore

## Running the Application
```bash
cd app_build
node server.js

- Customer Storefront: `http://localhost:3000/`
- Support Agent Console: `http://localhost:3000/agent`
