# AI Email Triage Assistant

An AI-powered email triage workflow built with n8n that monitors Gmail, classifies incoming emails using DeepSeek V4 Flash, and sends notifications for important career-related opportunities.

## Features

* Gmail monitoring using Gmail Trigger
* AI-powered email classification
* DeepSeek V4 Flash integration
* Career-focused filtering
* Automatic notifications via ntfy
* Low-latency workflow execution

## Workflow Architecture

Gmail Trigger

↓

DeepSeek V4 Flash

↓

IF Node

↓

ntfy Notification

## Tech Stack

* n8n
* Gmail API
* NVIDIA NIM
* DeepSeek V4 Flash
* ntfy

## Use Case

This workflow was built to reduce the chance of missing important emails such as:

* Internship opportunities
* Job opportunities
* Interview invitations
* Coding assessments
* Placement drives
* University deadlines
* Scholarship notifications

## Future Improvements

* WhatsApp notifications
* VPS deployment for 24/7 monitoring
* Multi-level priority scoring
* Email summarization
* Dashboard and analytics

## Importing the Workflow

1. Download the workflow JSON file.
2. Import it into n8n.
3. Configure Gmail credentials.
4. Add your NVIDIA API key.
5. Configure your ntfy topic.
6. Activate the workflow.

## Disclaimer

Before using this workflow, replace all placeholder credentials with your own credentials and API keys.
