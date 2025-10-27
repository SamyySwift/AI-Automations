# n8n Automations

This repository contains a collection of n8n workflow automations for various business processes.

## Automations

### HR Hiring Automation
A workflow that automates the HR hiring process by processing incoming resumes from Gmail, storing them in Google Drive, and analyzing candidate information.

![HR Hiring Automation](./images/hr%20hiring.png)

### Lead Capture Instagram Bot
An automation that captures leads from Instagram and processes them for marketing or sales follow-up.

![Lead Capture Instagram Bot](./images/lead-capture.png)

### RAG (Retrieval-Augmented Generation)
A knowledge management workflow that implements Retrieval-Augmented Generation for improved information retrieval and content generation.

![RAG Workflow](./images/rag.png)

## Tools Used

This section lists all the n8n nodes/tools used across the automations:

### Triggers and Webhooks
- Gmail Trigger - Monitors email inbox for new messages
- Manual Trigger - Starts workflow manually
- Webhook - Receives HTTP requests from external services
- Execute Workflow Trigger - Allows workflows to be triggered by other workflows

### Google Services
- Google Drive - File storage and management
- Google Sheets - Spreadsheet operations and data storage
- Google Sheets Tool - Advanced spreadsheet operations

### Communication
- Gmail - Sends emails and processes email content
- Respond to Webhook - Returns HTTP responses

### HTTP and API
- HTTP Request Tool - Makes API calls to external services

### Flow Control
- If - Conditional branching in workflows
- Sticky Note - Documentation and workflow organization