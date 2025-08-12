AI-Powered Automated Proposal Generator
Seamlessly generate professional proposals and presentations using AI




Overview
The AI-Powered Automated Proposal Generator streamlines the process of creating tailored project proposals and presentations.
By integrating AI language models with document APIs, the system automatically generates well-structured, client-specific proposals—reducing manual effort by 80% and improving consistency across deliverables.

Features
✍ AI Content Generation – Uses OpenAI and OpenRouter APIs to create customized proposals based on input prompts.

📊 Automated Presentation Creation – Builds Google Slides decks with dynamic project milestones and visual assets.

📑 Smart Data Flow – Parses structured JSON to populate proposal templates automatically.

📬 Instant Delivery – Sends completed proposals directly via email for client review.

Tech Stack
AI Integration: OpenAI API, OpenRouter API

Document Automation: PandaDoc API, Google Slides API

Workflow Automation: Tally, Make.com

Backend: JSON parsing, HTTP requests

Deployment: Cloud-hosted workflow automation

Architecture : 

Input Form (Tally)
        |
        |--- AI Proposal Generator
        |       ├── OpenAI/OpenRouter API
        |       ├── Custom Prompt Templates
        |
        |--- Proposal Formatting
        |       ├── PandaDoc API
        |       ├── Google Slides API
        |
        └── Delivery
                ├── Automated Email
                └── Client Access Link

(Since this project relies on API integrations and automation platforms like Make.com, setup requires configuring environment variables and webhooks as per documentation.)

<img width="1791" height="530" alt="image" src="https://github.com/user-attachments/assets/17b4f37d-bdc9-4b26-bd57-52e82ac4b0fa" />




















