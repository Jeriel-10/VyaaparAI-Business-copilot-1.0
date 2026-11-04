VyapaarAI – AI Business Decision Support System

### Your Intelligent AI Business Assistant for Small Businesses

VyapaarAI is an AI-powered business assistant designed to help small and medium-sized businesses understand inventory information and make smarter business decisions through natural language conversations.

## 💡 Problem Statement

Small businesses often face challenges in:
- Tracking inventory and stock levels.
- Identifying products that need restocking.
- Understanding inventory status.
- Accessing business information quickly.

## 🎯 Proposed Solution

VyapaarAI uses Generative AI and workflow automation to provide a conversational interface for business-related queries.

Users can interact with the assistant in Tamil or English and retrieve inventory information from Google Sheets.

## ✨ Features – V1.0

- AI-powered business chat assistant.
- Google Sheets inventory data retrieval.
- Product stock information analysis.
- Inventory status summaries.
- Tamil and English interaction support.
- Conversational memory.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Google Gemini AI | AI language model |
| n8n | Workflow automation and AI Agent |
| Google Sheets | Inventory data source |
| Simple Memory | Conversation context |

## 🏗️ Workflow Architecture

User Message
     ↓
Chat Trigger
     ↓
AI Agent
     ↓
Google Gemini Model
     ↓
Google Sheets Tool
     ↓
Inventory Data Retrieval
     ↓
AI Generated Response

Simple Memory maintains conversational context.

## 📂 Repository Structure

```text
VyapaarAI-Business-copilot-1.0/
│
├── README.md
└── vyapaarai-v1-workflow-public.json
