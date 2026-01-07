# Human-in-the-Loop Sales Email Automation using n8n

This project implements a Human-in-the-Loop AI workflow using n8n, where an AI agent drafts a sales email, a human reviewer approves or rejects it, and the system automatically takes the next action based on the decision.

It demonstrates how AI agents and human judgment can work together in real-world sales automation.

---

## Demo

[![Human in the Loop Demo](Screenshot-2026-01-02-135644.png)](https://youtu.be/YOUR_VIDEO_LINK_HERE)

Click the image above to watch the full workflow demonstration.

---

## Workflow Overview

The workflow is divided into three main stages:

### 1. New Lead Intake
- A lead submits a form
- Lead data is stored in Google Sheets
- The workflow is triggered automatically

### 2. AI Draft + Human Review
- An AI agent generates a personalized sales email
- The email is sent to a human reviewer
- The reviewer can approve or deny the email
- Optional feedback can be provided on denial

### 3. Send or Revise
- If approved, the email is sent to the customer
- If denied, feedback is passed to another AI agent
- The AI rewrites the email based on feedback
- The revised email can be re-reviewed or sent

---

## Key Features

- Human-in-the-loop approval system
- AI-generated sales emails
- Feedback-driven email rewriting
- Automated branching using text classification
- Structured output parsing for reliability
- End-to-end automation using n8n

---

## Tech Stack

- n8n
- Google Gemini (LLM)
- Google Sheets
- Gmail API
- Structured Output Parser

---

## Files in This Repository

- `My workflow.json`  
  n8n workflow export for the human-in-the-loop automation  

- `Screenshot-2026-01-02-135644.png`  
  Visual overview of the complete workflow  

- `README.md`  
  Project documentation  

---

## How to Use

1. Import `My workflow.json` into n8n
2. Configure Gmail and Google Sheets credentials
3. Update the form trigger or input source
4. Execute the workflow
5. Review, approve, or deny AI-generated emails

---

## Project Purpose

This project was built to demonstrate:
- Human-in-the-loop AI design
- Reliable AI content generation
- Sales automation workflows
- Practical use of AI agents in business
- Decision-based automation in n8n

---

## Author

Satvik Sharma  
AI Automation | n8n Workflows | Agentic AI Projects
