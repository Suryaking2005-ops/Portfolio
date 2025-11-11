# Gemini Architecture Expert Agent (Using the Agent Development Kit)

This notebook walks through building an AI agent with **Google’s Gemini models** using the **Agent Development Kit (ADK)**. The agent is designed specifically to **answer questions about architecture** — including building design concepts, materials, structural considerations, and general architectural principles.

##  What This Notebook Does

- Connects to Gemini through ADK
- Creates an agent that specializes in **architecture-related queries**
- Lets you chat with the agent interactively
- Helps you understand how to structure and guide agent behavior using system prompts

You can modify the agent’s instructions to adjust the tone, level of detail, or domain knowledge.

## Tools & Libraries

| Library / Tool | Purpose |
|----------------|---------|
| `google-adk` | Framework for building and running the agent |
| `google.generativeai` | Provides access to Gemini models |
| `python` | Core programming environment |

## Setup Requirements

Before running the notebook, make sure you have:

- A Google Cloud project
- Gemini API key enabled
- ADK installed

Install ADK:

```bash
pip install google-adk
