# AI Agents Intensive Course with Google

This online course was crafted by Google’s ML researchers and engineers to help developers explore the foundations and practical applications of AI agents. You’ll learn the core components:

- models  
- tools  
- orchestration  
- memory  
- evaluation  

You’ll discover how agents move beyond LLM prototypes to become production-ready systems.

Each day blends conceptual deep dives with hands-on examples, codelabs, and live discussions. By the end, you’ll be ready to build, evaluate, and deploy agents that solve real-world problems.

This page serves as the central hub for all course materials, updates, and resources.

---

## How the Course Works

The course is designed to be flexible and interactive, allowing you to learn at your own pace while benefiting from live sessions and community engagement.

- **Daily Content Release**  
  New assignments will be posted each day on this Kaggle course page — your primary source for all course materials.

- **Assignment Notifications (Fast Follow)**  
  Given the large number of participants, links to all assignment materials (whitepapers, codelabs, podcast episodes, etc.) will also be shared on the Kaggle Discord and sent via follow-up email shortly after being posted.

- **Support & Discussion**  
  Join the discussion on our dedicated Discord channels to connect with other learners, ask questions, and get support from Google researchers and engineers who will be monitoring the channels throughout the week.

- **Daily Livestreams**  
  Join Kanchana Patlolla and Anant Nawalgaria live each day starting Monday, November 10th at  
  11 AM PT / 8 PM CET / 12:30 AM IST on Kaggle’s YouTube channel.  
  They will be joined by special guests from Google, NVIDIA, Cohere and more. After each session, recordings will be shared on Discord.

- **Course Completion**  
  To get the most out of this intensive, we recommend completing all course materials — whitepapers, podcasts, and codelabs — before starting the capstone project.  
  Assignments are provided **for learning**, so submissions are not required and you can complete them at your own pace.

- **Capstone Project**  
  On the final day, you’ll have the chance to apply everything you’ve learned by building your own AI agent. By participating in the capstone project, you will earn a badge on Kaggle.

- **Community**  
  The community should remain positive and supportive. Please follow Kaggle’s community guidelines.

---

## Setup Instructions

To ensure you are ready for the course, please complete these essential setup steps:

1. **Kaggle account**
   - Sign up for a Kaggle account and learn how Notebooks work.  
   - Make sure to **phone verify** your account — it’s necessary for the course’s codelabs.

2. **AI Studio account**
   - Sign up for an AI Studio account and ensure you can generate an API key.

3. **Kaggle Discord**
   - Sign up for a Discord account and join the Kaggle Discord server.  
   - Channels dedicated to this event:
     - `#5dgai-announcements` — official course announcements and livestream recordings.  
     - `#5dgai-introductions` — introduce yourself and meet other participants from around the world.  
     - `#5dgai-question-forum` — forum-style channel for questions and assignment discussions.  
     - `#5dgai-general-chat` — general channel to discuss course materials and network with other participants.
   - To post on other channels on the Kaggle Discord you need to link your Kaggle account to Discord:  
     `https://kaggle.com/discord/confirmation`.

---

## Day 1 — Introduction to Agents

Today’s whitepaper introduces AI agents. It:

- presents a taxonomy of agent capabilities;
- emphasizes the need for an **Agent Ops** discipline for reliability and governance;
- discusses the importance of interoperability and security through identity and constrained policies.

In today’s codelabs you will:

- build your first AI agent and your first **multi-agent system** using the **Agent Development Kit (ADK)** powered by Gemini;
- give your agent the ability to use **Google Search** to answer questions with up-to-date information;
- explore how to create teams of specialized agents and different architectural patterns.

### Day 1 Assignments

1. Complete **Unit 1 – “Introduction to Agents”**:
   - Listen to the summary podcast episode for this unit, created by NotebookLM.  
   - Read the **“Introduction to Agents” whitepaper**.  
   - Complete these codelabs on Kaggle:
     - *Build your first agent using Gemini and ADK.*  
     - *Build your first multi-agent systems using ADK.*
   - Make sure you **phone verify your Kaggle account** before starting; it’s required for the codelabs.
   - Use the troubleshooting guide for common codelab problems.
   - For an interactive conversation, try adding the whitepapers to **NotebookLM**.

---

## Day 2 — Agent Tools & Interoperability with MCP

Today’s whitepaper focuses on:

- external tools and functions that allow an agent to perform actions or retrieve real-time data beyond its training set;
- best practices for designing effective tools;
- **Model Context Protocol (MCP)** — its architectural components, communication layer, risks, and enterprise readiness gaps.

In today’s codelabs you will:

- create custom tools for your agents by turning your own Python functions into actions;
- use MCP and implement **long-running operations** where an agent can pause tool calls while waiting for human approval, then resume.

### Day 2 Assignments

Complete **Unit 2 – “Agent Tools & Interoperability with Model Context Protocol (MCP)”**:

- Listen to the summary podcast episode for this unit, created by NotebookLM.  
- Read the **“Agent Tools & Interoperability with Model Context Protocol (MCP)” whitepaper**.  
- Complete these codelabs on Kaggle:
  - *Explore new ways to add tools to extend what your agents can do.*  
  - *Explore best practices for tools, including using MCP and long-running operations.*  
- For an interactive conversation, add the whitepapers to NotebookLM.

---

## Day 3 — Context Engineering: Sessions & Memory

This whitepaper explores **context engineering** as the practice of dynamically assembling and managing information within an agent’s context window to create **stateful** and personalized AI experiences.

Key concepts:

- **Sessions** — the container for a single, immediate conversation’s history;  
- **Memory** — the long-term persistence mechanism across sessions.

In the codelabs you will:

- make agents stateful by managing conversation history through context engineering in ADK;
- implement working memory within a session so your agent can remember context and have coherent multi-turn conversations;
- give your agent **long-term memory** that persists across different sessions.

### Day 3 Assignment

Complete **Unit 3 – “Context Engineering: Sessions & Memory”**:

- Listen to the summary podcast episode for this unit, created by NotebookLM.  
- Read the **“Context Engineering: Sessions & Memory” whitepaper**.  
- Complete these codelabs on Kaggle:
  - *Build stateful agents and perform context engineering.*  
  - *Explore how to use memory with your agent.*  
- Optionally, add the whitepapers to NotebookLM for interactive exploration.

---

## Day 4 — Agent Quality

This whitepaper addresses the challenge of assuring quality in AI agents by introducing a **holistic evaluation framework**.

Key ideas:

- **Observability** with three pillars:
  - **Logs** — the diary;  
  - **Traces** — the narrative;  
  - **Metrics** — the health report.  
- Continuous feedback loops using:
  - LLM-as-a-Judge;  
  - Human-in-the-Loop (HITL) evaluation.

In today’s codelabs you will:

- use logs, traces, and metrics to obtain full visibility into your agent’s decision-making process;
- debug failures and understand why your agent behaves the way it does;
- evaluate your agents to score response quality and tool usage.

### Day 4 Assignment

Complete **Unit 4 – “Agent Quality”**:

- Listen to the summary podcast episode for this unit, created by NotebookLM.  
- Read the **Agent Quality whitepaper**.  
- Complete these codelabs on Kaggle:
  - *Implement observability to help you debug your agents.*  
  - *Evaluate your agents.*

---

## Day 5 — Prototype to Production

This whitepaper provides a technical guide to the operational lifecycle of AI agents, focusing on:

- deployment;  
- scaling;  
- productionization.

It explores the challenges of transitioning agentic systems from prototypes to enterprise-grade solutions, with special attention to the **Agent2Agent (A2A) Protocol**.

In today’s codelabs you will:

- build systems of multiple, independent agents that communicate and collaborate using **A2A Protocol**;
- take your agent from your local machine to a **production-ready, scalable service** by deploying it to **Vertex AI Agent Engine** on Google Cloud.

### Final Assignment

Complete **Unit 5 – “Prototype to Production”**:

- Listen to the summary podcast episode for this unit.  
- Read the **“Prototype to Production” whitepaper**.  
- Complete these codelabs on Kaggle:
  - *Explore how to use A2A Protocol to have agents interact with each other.*  
  - *[Optional] Deploy your agent to Agent Engine on Google Cloud.*

---

## Final Reminders and Announcements

**Congrats on completing the 5-day AI Agents Intensive course!**

- 🎯 **Capstone Project**  
  You’ll create an AI agents project showcasing a use case that leverages some of the key capabilities learned throughout this course.  
  The **top 12 winners** will receive Kaggle swag and have their work featured on Kaggle’s social media platforms.  
  More details about the Capstone Project, including evaluation and submission process, will be shared by email.  
  Participation is **optional**.

- ⭐ **Kaggle badge and certificate**  
  Participants in the Capstone Project are eligible to earn a **badge and certificate** on their Kaggle profile.  
  These will be added to all eligible profiles by the **end of December 2025**.

- 👀 **Kaggle Learn Guide**  
  The content is being transitioned into a convenient **Kaggle Learn Guide**.  
  The updated resource will be shared as soon as it is ready.

- 🤖 **GEAR (Gemini Enterprise Agent Ready)**  
  If you’d like to continue building on what you learned in the Agents Intensive, Google’s upcoming **Gemini Enterprise Agent Ready (GEAR)** initiative offers a deeper dive into learning, building and deploying AI agents.  
  GEAR launches in early **2026**.
