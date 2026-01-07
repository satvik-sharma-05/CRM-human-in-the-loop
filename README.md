# Human-in-the-Loop Sales Email Automation using n8n

This project demonstrates a Human-in-the-Loop AI sales automation workflow built using n8n.

An AI agent drafts a personalized sales email for a new lead, a human reviewer then approves or rejects the email, and the workflow automatically takes the next action based on that decision. If approved, the email is sent to the lead. If rejected, the email is revised based on feedback and reprocessed.

This project highlights how AI automation and human judgment can work together in real-world sales workflows.

---

## Demo

### Workflow Screenshot
[![Human-in-the-Loop Demo](Screenshot%202026-01-02%20135644.png)](https://youtu.be/Sz-O8Wl1Ckw)

### Direct Video Link
https://youtu.be/Sz-O8Wl1Ckw

---

## Workflow Overview

1. A new lead submits a form
2. Lead details are stored in Google Sheets
3. An AI agent generates a personalized sales email
4. The email is sent to a human reviewer for approval
5. Reviewer approves or rejects the email
6. If approved, the email is sent to the customer
7. If rejected, feedback is captured
8. A second AI agent rewrites the email based on feedback
9. The revised email can be reviewed again or sent

---

## Key Features

- Human-in-the-Loop approval system
- AI-generated sales emails
- Feedback-driven email rewriting
- Conditional routing based on approval or rejection
- Automated email delivery
- Built entirely using n8n workflows

---

## Tech Stack

- n8n
- Google Gemini (LLM)
- Google Sheets
- Gmail
- Structured Output Parser
- Text Classification

---

## Files in This Repository

- `My workflow.json`  
  n8n workflow export for the Human-in-the-Loop automation

- `Screenshot 2026-01-02 135644.png`  
  Visual overview of the complete workflow

- `README.md`  
  Project documentation

---

## How to Use

1. Import `My workflow.json` into n8n
2. Configure Gmail and Google Sheets credentials
3. Set up the lead intake form
4. Run the workflow
5. Review AI-generated emails and approve or reject them

---

## Project Purpose

This project was built to demonstrate:
- Practical Human-in-the-Loop AI design
- Real-world sales automation
- AI-assisted decision workflows
- Advanced n8n automation patterns

---

## Author

Satvik Sharma  
AI Automation | n8n Workflows
