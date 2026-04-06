# # AI-Powered Lead Enrichment Pipeline

Using n8n, Gemini, Airtable and Slack


## What It Does
Automatically enriches new leads from a Tally form using Gemini AI 
and notifies your team on Slack.

## Workflow
Tally Form → Edit Fields → Gemini AI → Code Parser → Airtable → Slack

## Tools Used
- n8n
- Tally.so
- Google Gemini (gemini-2.5-flash)
- Airtable
- Slack

## Setup
1. Import the workflow JSON into n8n
2. Connect your own credentials for each service
3. Update the Tally question IDs in the Edit Fields node to match your form
4. Publish and test
