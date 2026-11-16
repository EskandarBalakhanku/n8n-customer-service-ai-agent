# Customer Service AI Agent | n8n

## Project Overview

An AI-powered customer service agent built with n8n as part of the n8n Academy Quickstart (QS101) course.

The agent answers customer questions by retrieving customer and order information from connected data sources.

## Key Features

- AI-powered customer support
- Google Gemini integration
- Conversational memory
- Customer database lookup
- REST API integration
- Intelligent tool selection
- Custom system prompts

## Workflow Architecture

- Chat Trigger
- AI Agent
- Google Gemini Chat Model
- Simple Memory
- GetCustomers (Data Table)
- GetOrderData (HTTP Request)

## Technologies Used

- n8n
- Google Gemini
- REST API
- JSON
- Data Tables
- Prompt Engineering

## Getting Started

1. Download the workflow JSON file.
2. Import it into your n8n instance.
3. Configure your Google Gemini credentials.
4. Connect your customer Data Table.
5. Configure the order API credentials and assessment ID, or use your own API.
6. Test the AI Agent through the chat interface.

## Security

Personal credentials and private identifiers have been removed from the exported workflow.

## Project Status

Completed and tested as an n8n Academy educational project.

## Author

Eskandar Balakhanlu

## Workflow Screenshot

![Customer Service AI Agent](AI%20Agent.png)


