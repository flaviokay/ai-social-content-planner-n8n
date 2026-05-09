<img width="2475" height="1232" alt="ScreenMVPaiSocial" src="https://github.com/user-attachments/assets/7a6fa175-8cff-4366-900a-adcd0c1f9b19" />

# ai-social-content-planner-n8n
AI automation MVP built with n8n, Docker and Ollama to generate structured editorial plans and send them via email.
 # AI Social Content Planner - n8n

AI automation MVP built with n8n, Docker and Ollama to generate structured editorial content plans and send them automatically via email.

## Project Overview

This project is an automation workflow designed to support social media content planning.

The workflow takes a predefined content brief, processes multiple content ideas, sends each item to a local AI model through Ollama, structures the generated output, formats the final result in HTML and sends the complete editorial plan via email.

The goal of this MVP is to demonstrate how AI and automation tools can be combined to create a practical content generation pipeline.

## Main Features

- Automated content planning workflow
- Local AI generation using Ollama
- Workflow orchestration with n8n
- Docker-based local environment
- Loop-based processing of multiple content ideas
- JSON output parsing and formatting
- HTML email generation
- Automatic email delivery via SMTP

## Tech Stack

- n8n
- Docker
- Ollama
- JavaScript
- SMTP / Email automation
- Local LLM workflow

## Workflow Structure

The workflow is composed of the following main steps:

1. Manual Trigger  
   Starts the workflow manually.

2. Input Contenuto  
   Defines the initial content ideas and campaign structure.

3. Loop Over Items  
   Processes multiple content ideas one by one.

4. Ollama AI Request  
   Sends each content item to a local AI model.

5. Parse Output JSON  
   Extracts and structures the AI-generated response.

6. Format Email  
   Creates a readable HTML version of the editorial plan.

7. Send Email  
   Sends the final editorial plan via email.

## Use Case

This MVP can be used as a base for:

- Social media content planning
- Music release promotion
- Marketing campaign ideation
- Editorial calendar generation
- AI-assisted creative workflows

## Security Notes

Sensitive credentials such as email passwords, SMTP credentials or API keys are not included in this repository.

The workflow file is provided for demonstration and portfolio purposes.

## Future Improvements

Possible next steps:

- Replace local Ollama model with GPT or Claude API for higher-quality production output
- Add Google Sheets integration for input/output tracking
- Add recruiter or client-specific personalization
- Add approval step before sending content
- Add WhatsApp or Telegram notification
- Deploy workflow on a cloud server

## Status

MVP completed and tested locally.
