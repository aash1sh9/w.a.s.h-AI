<div align="center">

# W.A.S.H AI

### WhatsApp AI Smart Helper

**Turning noisy group chats into structured, actionable intelligence.**

![Status](https://img.shields.io/badge/status-prototype-7CFC00?style=for-the-badge&labelColor=111111)
![Python](https://img.shields.io/badge/Python-Prototype-7CFC00?style=for-the-badge&labelColor=111111)
![OpenAI](https://img.shields.io/badge/OpenAI-API-7CFC00?style=for-the-badge&labelColor=111111)
![Theme](https://img.shields.io/badge/HackBIOS%202K26-Open%20Innovation-7CFC00?style=for-the-badge&labelColor=111111)

</div>

---

## Overview

**W.A.S.H AI** is an AI-powered WhatsApp group intelligence system designed to reduce information overload in busy group chats.

Instead of manually scrolling through hundreds of messages, W.A.S.H AI processes group conversations and converts them into useful and actionable information.

### Core outputs

- Chat summaries
- Important announcements
- Relevant mentions
- Action items and follow-ups

The original prototype was developed during an **OpenAI Hackathon** using a modular AI workflow.

---

## Problem

Important information often gets buried inside long WhatsApp group conversations.

Users commonly face problems like:

- Missing important announcements
- Losing track of deadlines
- Missing relevant mentions
- Forgetting assigned tasks
- Repeatedly scrolling through old messages
- Difficulty identifying what actually matters

W.A.S.H AI solves this by creating an **intelligence layer over WhatsApp conversations**.

---

# Core Features

## 1. Smart Conversation Summary

Generates concise summaries of long WhatsApp conversations.

**Purpose:**

- Quickly understand what happened
- Avoid reading hundreds of messages
- Extract key discussions
- Reduce information overload

---

## 2. Announcement Detector

Identifies important information from group conversations.

**Detects:**

- Announcements
- Deadlines
- Important updates
- Notices
- Relevant official information

---

## 3. Mention Tracker

Tracks relevant mentions from conversations.

**Purpose:**

- Find when a user is mentioned
- Surface important context
- Avoid missing messages directed toward someone
- Improve information discovery

---

## 4. Action Item Extractor

Extracts tasks and responsibilities from conversations.

**Detects:**

- Tasks
- Responsibilities
- Follow-ups
- Pending work
- Actionable items

The extracted information is converted into a structured format.

---

# How W.A.S.H AI Works

```text
WhatsApp / Group Chat
        ↓
   Text Processing
        ↓
   AI Orchestrator
        ↓
 ┌───────────────┬────────────────────┬────────────────┬────────────────────┐
 │               │                    │                │                    │
 ▼               ▼                    ▼                ▼
Summarizer   Announcement        Mention Tracker   Action Item Extractor
               Detector
 │               │                    │                │
 └───────────────┴────────────────────┴────────────────┴────────────────────┘
                                ↓
                       Structured Output
