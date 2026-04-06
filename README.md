# # AI-Powered Lead Enrichment Pipeline

Using n8n, Gemini, Airtable and Slack


## What It Does
Automatically enriches new leads from a Tally form using Gemini AI 
and notifies your team on Slack.

## Workflow
Tally Form → Edit Fields → Gemini AI → Code Parser → Airtable → Slack

## Tools Used

| Tool | Purpose |
|---|---|
| n8n | Workflow automation |
| Tally.so | Lead capture form |
| Google Gemini | AI enrichment |
| Airtable | Lead database |
| Slack | Team notifications |

## Setup Instructions
1. Import `workflow.json` into your n8n instance
2. Connect your own credentials for each service
3. Update the Tally question IDs in the Edit Fields node to match your form fields
4. Publish the workflow and submit a test form entry

## Preview
<img width="1700" height="853" alt="Screenshot 2026-04-06 at 1 36 36 PM" src="https://github.com/user-attachments/assets/8d48c536-3b5e-4e7e-96af-c20ce2404157" />

<img width="1710" height="905" alt="Screenshot 2026-04-06 at 2 00 19 PM" src="https://github.com/user-attachments/assets/54abb2fa-a6de-4171-ab7c-8876c11a4f1f" />

## Setup
1. Import the workflow JSON into n8n
2. Connect your own credentials for each service
3. Update the Tally question IDs in the Edit Fields node to match your form
4. Publish and test
