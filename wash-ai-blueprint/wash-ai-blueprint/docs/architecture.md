# System Architecture

## Architecture Overview

W.A.S.H AI follows a modular processing pipeline.

```text
Chat Input
   ↓
Input Parser / Cleaner
   ↓
AI Orchestrator
   ↓
┌───────────────────────────────┐
│ Specialized AI Modules       │
│ • Summarizer                  │
│ • Announcement Detector      │
│ • Mention Tracker            │
│ • Action Item Extractor      │
└───────────────────────────────┘
   ↓
Structured Results
   ↓
UI / Notification / Export Layer
```

## Component Responsibilities

### 1. Input Layer
Accepts WhatsApp/group-chat text and prepares it for processing.

### 2. Text Processing
- Cleans raw chat text
- Preserves message context
- Prepares relevant content for AI modules

### 3. AI Orchestration
Routes processed conversation data to specialized modules.

### 4. Specialized Modules
Each module solves a focused problem instead of asking one generic prompt to do everything.

### 5. Structured Output Layer
Returns summaries, announcements, mentions, and action items in a predictable format that can later power a dashboard, bot, or notification system.

## Design Principle
**One conversation → multiple focused AI analyses → one structured intelligence layer.**
