# nexora-morning-summary
# Nexora Daily Morning Summary — AI Automation

An automated AI workflow built with n8n that delivers a complete business 
summary to the owner every morning at 9 AM — without any manual work.

## What it does
- Reads live data from Google Sheets (Finance Tracker + Lead Tracker)
- AI analyzes overdue payments, upcoming dues, and lead follow-ups
- Generates a structured daily summary using LLaMA 3.3 70B via Groq
- Sends the full report to email automatically every morning

## Business problem it solves
Small business owners waste 30–45 minutes every morning checking spreadsheets, 
chasing payments, and reviewing leads. This workflow does it in 0 minutes.

## Tech stack
- n8n (workflow automation)
- Groq API — LLaMA 3.3 70B (AI summary generation)
- Google Sheets API (live business data)
- Gmail API (email delivery)
- Schedule Trigger (runs daily at 9 AM)

## Built for
Nexora Marketing Agency — delivered as a real client project, May 2026

## Workflow file
Import `daily_morning_summary.json` directly into n8n to use this workflow.

