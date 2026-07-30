# AI Meeting Assistant

An AI-powered meeting documentation workflow built with n8n and OpenAI that transforms raw meeting notes into structured summaries, key decisions, action items, and next steps. The generated information is automatically stored in Google Sheets and delivered to participants via email.

---

# Problem It Solves

Taking notes during meetings is easy, but organizing them into clear summaries and actionable follow-ups is often time-consuming.

AI Meeting Assistant automates this process by allowing users to submit:

- Meeting title
- Meeting notes
- Name
- Email address

The workflow analyzes the meeting notes, generates structured documentation, stores the results in Google Sheets, and emails a personalized meeting summary to the user.

---

# Features

- AI-powered meeting summarization
- Automatic extraction of key decisions
- Action item generation
- Next-step recommendations
- Structured AI output
- Google Sheets integration
- Gmail email delivery
- Form-based user interface
- End-to-end workflow automation

---

# Workflow Architecture

### Form Trigger

Collects meeting details from the user.

### AI Agent

Analyzes the meeting notes and generates:

- Meeting Summary
- Key Decisions
- Action Items
- Next Steps

### Structured Output Parser

Converts the AI response into a structured JSON format for reliable downstream processing.

### Google Sheets

Stores all processed meeting information automatically.

### Gmail

Sends a personalized meeting summary to the user's email.

The workflow is powered by **OpenAI GPT-4.1 Mini** and orchestrated using **n8n**.

---

# Tech Stack

- n8n
- OpenAI GPT-4.1 Mini
- Structured Output Parser
- Google Sheets
- Gmail
- Form Trigger

---
# Screenshots

## n8n Workflow

![n8n Workflow](workflow.png)

---

## Google Sheets Output

![Google Sheets Output](google-sheet.png)

---

## Generated Meeting Records

![Generated Meeting Records](google-sheet1.png)

---

## Personalized Email Output

![Email Output](email-output.png)

---

# How It Works

1. User submits meeting details.
2. AI analyzes the meeting notes.
3. Summary, decisions, action items, and next steps are generated.
4. Results are stored in Google Sheets.
5. A personalized meeting summary is emailed to the user.

---

# Run Locally

1. Import the workflow JSON into n8n.
2. Configure OpenAI credentials.
3. Configure Google Sheets credentials.
4. Configure Gmail credentials.
5. Activate the workflow.
6. Submit the meeting form.

---

# Repository Structure

```text
README.md
ai-meeting-assistant-workflow.json
images/
```

---

# 👩‍💻 Author

**Tabinda Fatima**

AI Automation & Workflow Developer
