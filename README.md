# 🧠 Agent Engineering Foundations  

Welcome to the open-source home of **Agent Engineering Foundations**. It is a practical, engineering-first introduction to building AI agents that operate in the real world.

This module is designed for **mid-level and senior software engineers** who want to level up into the emerging discipline of **Agent Engineering**: the craft of designing, orchestrating, evaluating, and deploying AI agents that automate workflows and collaborate with humans.

This repository contains:
- Lecture notes & slides  
- Weekly labs  
- Example agents  
- Evaluation templates  
- Capstone guidelines  
- Certification materials  

Everything is developed **in the open**, because the future of AI agents deserves a community-driven foundation.

---

# 🌍 Two Schools of Agent Engineering

In this module, we explore the foundations of agentic systems through **two parallel archetypes**:

## 1. 🟩 Agents as AI Automation  
*Back-office, workflow-first, system-to-system agents*

- Execute structured tasks  
- Run multi-step workflows  
- Interact with APIs, databases, and file systems  
- Perform backend automation  
- Often event-driven, not user-facing  
- Examples: analytics agents, research pipelines, video automation, newsletter automations

## 2. 🟦 Agents as Autonomous Digital Co-Workers  
*User-facing, conversational, multimodal agents*

- Interact with humans directly  
- Speak, listen, see (voice + multimodal)  
- Maintain memory and context  
- Make live decisions & take actions  
- Examples: customer support agents, research copilots, voice assistants, agentic copilots  

**Both share the same underlying engineering principles** — but differ in UX constraints, safety boundaries, and how we evaluate them.

This dual framing gives students the key insight:

> “All agents are orchestrated LLM systems.  
> The difference is WHERE they act and WHO they interact with.”

---

# 📚 Module Structure (5 Weeks • 15 Hours)

Each week introduces one core concept and applies it to both archetypes through two labs.

---

## **Week 1 — Agent Engineering Foundations**  
Theme: *What is an agent? Two schools of agentic design.*

Concepts:
- Automation agents vs digital co-workers  
- Tool use, memory, orchestration  
- Safety boundaries per archetype  
- Why the Agent Engineer role exists  
- Planner–executor loops  

Labs:
- 🟩 Build a research pipeline agent (backend only)  
- 🟦 Build a “Hello Voice Agent” with ASR → reasoning → TTS  

---

## **Week 2 — Orchestration, Tools & MCP**  
Theme: *Tools define capability. MCP defines safety.*

Concepts:
- Tools and permissions  
- MCP as a standardized interface  
- Statefulness vs event-driven pipelines  
- Return types, retry logic, schemas  

Labs:
- 🟩 Add tools (search, file writer, video generation) → automated social media agent  
- 🟦 Add tools to the voice agent (calculator, search, RAG)  

---

## **Week 3 — Reasoning & Test-Time Compute**  
Theme: *Reliable reasoning is the core skill of an Agent Engineer.*

Concepts:
- CoT, self-consistency, reflection  
- Verifier models  
- TTCS budgets  
- Latency requirements for voice agents  

Labs:
- 🟩 Add a verifier to the research pipeline  
- 🟦 Add structured planning & silent reasoning to the voice agent  

---

## **Week 4 — Factuality, RAG & Attribution**  
Theme: *Agents need knowledge. The question is how they use it.*

Concepts:
- RAG vs search  
- Grounding & attribution  
- Faithfulness evaluation  
- Document workflows  

Labs:
- 🟩 Build a RAG-powered research agent with attribution  
- 🟦 Add RAG to the voice agent for context-aware conversations  

---

## **Week 5 — Observability, Governance & Deployment**  
Theme: *An agent you cannot see, log, debug, or control is NOT a product.*

Concepts:
- Observability: traces, spans, metrics  
- Governance & permissions  
- Safety policies  
- Canary vs shadow rollouts  

Labs:
- 🟩 Productionize the automation agent (dashboards, retries, shadow mode)  
- 🟦 Productionize the voice agent (latency dashboards, fallbacks, guardrails)  

---

# 🎓 Capstone Project

Students choose **one** of the two archetypes:

## 1. 🟩 Deep Research Automation Agent  
- Plan → search → retrieve → summarize → verify  
- Markdown + JSON outputs  
- Optional video generation (Nano Banana / Pika)  
- Includes evals + dashboards  

or

## 2. 🟦 Voice-First Digital Co-Worker Agent  
- ASR → reasoning → TTS  
- Tool use + RAG  
- Error handling + safety fallbacks  
- Observability instrumentation  

---

# 🏗️ How This Repo Works

.
├── week01/
├── week02/
├── week03/
├── week04/
├── week05/
├── capstone/
├── agents/
│ ├── automation/
│ └── digital-coworker/
├── evaluations/
└── docs/

Everything here is open source and permissively licensed so that anyone can learn from it, fork it, remix it, or build on top of it.

---

# 🤝 Collaboration

This project is part of a broader initiative to define the emerging discipline of **Agent Engineering**.

Pull requests, improvements, examples, and additional labs are welcome.

Let's build the future of agentic systems in the open.
