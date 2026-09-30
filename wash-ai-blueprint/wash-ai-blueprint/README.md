# W.A.S.H AI

> **WhatsApp AI Smart Helper** — turning noisy group chats into structured, actionable intelligence.

W.A.S.H AI is a multi-agent WhatsApp group intelligence system originally prototyped during an OpenAI hackathon. It is designed to help users understand long group conversations without manually scrolling through hundreds of messages.

## Problem
WhatsApp groups often contain important announcements, deadlines, mentions, decisions, and action items mixed with casual conversation. Important information gets buried and users spend time searching through long chats.

## Proposed Solution
W.A.S.H AI processes group-chat text and routes it through specialized AI modules that produce structured outputs.

### Core modules already built in the prototype
1. **Conversation Summarizer** — generates concise summaries of long chats.
2. **Announcement Detector** — identifies important announcements and key updates.
3. **Mention Tracker** — finds relevant user/name mentions in conversations.
4. **Action Item Extractor** — extracts tasks, responsibilities, and follow-ups.

## High-Level Flow

```text
WhatsApp / Group Chat Messages
            ↓
      Text Processing
            ↓
      Multi-Agent Layer
   ┌────────┼─────────┬──────────┐
   ↓        ↓         ↓          ↓
Summary  Announcements Mentions  Action Items
   └────────┴─────────┴──────────┘
            ↓
      Structured Output
```

## Current Technical Approach
- **Python** — core prototype logic
- **OpenAI API** — LLM intelligence for the AI modules
- **Prompt Engineering** — task-specific prompts and structured outputs
- **Multi-Agent Workflow** — specialized agents for separate information-extraction tasks

## Repository Purpose
This repository is currently the **project blueprint / technical documentation** for W.A.S.H AI. It records what has already been built, how the system works, and how the prototype can evolve into a production-ready product.

## Documentation
- [System Architecture](docs/architecture.md)
- [Built Features](docs/features.md)
- [Product Scope](docs/product-scope.md)
- [Roadmap](docs/roadmap.md)
- [HackBIOS 2K26 Pitch Notes](docs/hackbios-pitch.md)

## Team
**sYndiCate**

- **Aashish Raj** — Team Leader
- **Ketan Kumar Upadhyay**

## HackBIOS 2K26
- **Theme:** Open Innovation
- **Problem Statement Title:** AI-Powered WhatsApp Group Intelligence & Information Management System
- **Project:** W.A.S.H AI

## Status
**Prototype / Blueprint stage**

The OpenAI hackathon prototype demonstrated the core multi-agent information-processing concept. The next phase focuses on improving integration, persistence, user experience, and production readiness.
