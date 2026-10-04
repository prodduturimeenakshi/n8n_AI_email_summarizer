# AI Email Summarizer with n8n

An AI-powered email automation workflow built using n8n.

## Workflow

Gmail → AI Agent → Google Gemini → Google Sheets

## What it does

- Detects incoming Gmail messages
- Sends the email content to an AI agent
- Generates a short summary
- Identifies whether an action is required
- Stores the date, sender, subject, summary, and required action in Google Sheets

## Technologies Used

- n8n
- Gmail
- Google Gemini
- Google Sheets
- AI Agent

## Workflow Structure

1. Gmail Trigger
2. AI Agent
3. Google Gemini Chat Model
4. Google Sheets – Append Row

## Security

The published workflow does not contain personal OAuth tokens, API keys, or private credential values.

To use the workflow, users must connect their own Gmail and Google Sheets credentials and provide their own Google Sheet.

## Author

Meenakshi
