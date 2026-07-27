# AI Lead Qualification Assistant

## Overview

This project is an AI-powered Lead Qualification Assistant built using **n8n**, **OpenAI**, **Google Sheets**, **Gmail**, and **Slack**.

The workflow interacts with potential customers, asks intelligent follow-up questions, qualifies leads based on predefined business rules, extracts structured customer information, and automatically triggers business actions.

---

## Features

- AI-powered conversational lead qualification
- Multi-turn conversation support
- Automatic lead scoring
- Structured data extraction
- Lead routing (Qualified / In Progress / Disqualified)
- Google Sheets CRM integration
- Gmail confirmation emails
- Slack sales notifications
- Conversation history tracking
- Error handling using Continue On Fail

---

## Tech Stack

- n8n
- OpenAI
- Google Sheets
- Gmail
- Slack

---

## Workflow

1. Customer sends a message via the webhook.
2. The workflow retrieves previous conversation history.
3. The AI agent analyses the conversation.
4. Missing information is requested when necessary.
5. The lead is classified as:
   - Qualified
   - In Progress
   - Disqualified
6. Qualified leads are:
   - Saved to Google Sheets
   - Sent a confirmation email
   - Sent to Slack for the sales team
7. All conversations are stored for future context.

---

## AI Data Extracted

- Name
- Email
- Phone Number
- Business Requirement
- Budget
- Timeline
- Lead Score
- Qualification Reason
- Next Action

---

## Project Structure

```text
AI-Lead-Qualification-Assistant/
│
├── ai-lead-qualification-workflow.json
├── README.md
└── screenshots/
```

---

## Setup

1. Import the workflow into n8n.
2. Configure your OpenAI credentials.
3. Connect Google Sheets.
4. Connect Gmail.
5. Connect Slack.
6. Execute the workflow.
7. Test using Postman.

---

## Future Improvements

- WhatsApp integration
- CRM integration (HubSpot/Salesforce)
- Calendar booking
- Analytics dashboard
- Lead prioritization

---

## Author

Efosa Macaulay-Smith

AI Automation Engineer
