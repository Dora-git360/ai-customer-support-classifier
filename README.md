# AI Customer Support Classifier

## Overview

This project automates customer support ticket classification using n8n and Google Gemini AI.

It analyzes incoming customer support requests, identifies the ticket category, and prepares the data for downstream automation such as routing, prioritization, and CRM processing.

---

## Business Problem

Customer support teams receive hundreds of requests every day. Manually classifying tickets into categories such as Billing, Technical Support, Shipping, or General Inquiry is repetitive and time-consuming.

This workflow automates the classification process using AI, improving consistency and reducing manual effort.

---

## Solution

The workflow receives customer support requests, processes the ticket information, sends the content to Google Gemini AI for classification, and returns the predicted category for further automation.

---

## Workflow

Webhook

↓

Edit Fields

↓

Google Gemini AI

↓

Classify Ticket

↓

Return Response

---

## Features

- AI-powered ticket classification
- Google Gemini AI integration
- Automated workflow using n8n
- REST API support
- JSON request processing
- Easy to customize

---

## Technologies Used

- n8n
- Google Gemini AI
- REST API
- JSON
- Webhooks

---

## Project Structure

```text
README.md
LICENSE
Project-04-AI-Customer-Support-Classifier.json
```

---

## How to Import

1. Download the workflow JSON file.
2. Open n8n.
3. Click **Import Workflow**.
4. Select `Project-04-AI-Customer-Support-Classifier.json`.
5. Configure your Google Gemini AI credentials.
6. Execute the workflow.

---

## Sample Input

```json
{
  "customerName": "John",
  "message": "I was charged twice for my order."
}
```

---

## Sample Output

```json
{
  "category": "Billing",
  "priority": "High"
}
```

---

## Use Cases

- Customer Support Automation
- AI Ticket Classification
- CRM Automation
- Helpdesk Systems
- Workflow Automation
- AI Operations

---

## Future Improvements

- Sentiment analysis
- Automatic ticket prioritization
- CRM integration
- Google Sheets logging
- Slack or Microsoft Teams notifications
- Multi-language classification

---

## Project Status

Completed

---

## Author

**Buddha Dorababu**

AI Automation Engineer | n8n | AI Workflows | Gemini AI | CRM Automation | API Integrations
