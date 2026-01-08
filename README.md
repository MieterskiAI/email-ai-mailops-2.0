# AI MailOps Agent v0.1 — Decision Support System for Operational Email Triage

A human-centered AI agent that helps people regain control over chaotic operational inboxes by providing clear decision context — not automation.

---

## 🧠 Business Context

In many organizations, shared inboxes silently destroy decision quality.  
Important cases get lost, priorities blur, and people start reacting instead of deciding.

This system does **not replace employees**.

It is designed to:
- reduce cognitive overload,
- highlight what really matters,
- and guide operators toward the next safe decision.

---

## 🔁 Before / After

**Before**
- chaotic inbox  
- reactive handling  
- missed critical cases  
- decisions based on stress, not clarity  

**After**
- clear decision context per message  
- structured next-step suggestions  
- operators regain control over their workflow  

---

## 🧭 AI MailOps Agent — Core Idea

This is not an email automation system.  
It is a **Decision Navigation Agent**.

Every incoming message is transformed into a **Decision Context Card** that answers:

> *What should I do now, and why?*

---

## 🗂 Decision Context Card

Each email generates a card with:

| Field | Meaning for the operator |
|------|--------------------------|
| Case Type | Lead / Support / Urgent |
| Business Risk | low / medium / high |
| AI Confidence | high / medium / low |
| Recommended Path | reply / escalate / assign / ask |
| Why this matters | one short sentence |
| What you must decide | one concrete question |
| Agent Voice | human guidance sentence |

---

## 📐 Agent Architecture

This repository separates **how the agent thinks** from **how it is implemented**.

- **Decision & Reasoning Layer**  
  → [`agent_reasoning.md`](./agent_reasoning.md)

- **Implementation Layer**  
  → [`docs/implementation_notes.md`](./docs/implementation_notes.md)

This structure makes the system readable both for business stakeholders and technical teams.

---

## 🗣 Agent Voice — Human Interface

| Mode | Agent says |
|------|-------------|
| Lead | Otrzymałeś lead, któremu warto się przyjrzeć. |
| Support | Czy mógłbyś zajrzeć? Coś jest tutaj nie tak. |
| Urgent | Potrzebujesz więcej informacji, żeby bezpiecznie wykonać następny krok. |
| Uncertain | Nie jestem w stanie niczego zaproponować, nie mam w zwyczaju zgadywać. |

This language is designed to create decision intuition — not pressure.

---

## 🔄 Decision Flow

Incoming Email  
→ Intent & Risk Analysis  
→ **Decision Context Card**  
→ Suggested Next Actions  
→ **Human Decision**

The system never executes actions on its own.

---

## 🤝 Human-in-the-Loop

AI does not decide.  
It removes bad paths and shows the operator where thinking is required.

The human always owns the final responsibility.

---

## 🧩 How the Pipeline Works

1. **Email Trigger** – new message arrives  
2. **Intent & Risk Analysis** – case type, emotional signals, business risk  
3. **Decision Context Card Generation** – decision map is built  
4. **Decision Logging** – organizational memory  
5. **Draft Support** – response draft prepared  
6. **Human Action** – operator reviews and sends

---

## ⚡ Why This Agent Matters

It helps organizations:
- reduce decision fatigue,  
- avoid costly misclassification,  
- improve response quality,  
- and build trust in human-AI cooperation.

---

## 👤 Author

**MieterskiAI**  
Junior AI Process & Decision Support Designer  
Designing human-centered AI systems that help organizations regain control over complex operational processes.
