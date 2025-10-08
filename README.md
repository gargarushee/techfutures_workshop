TechFutures Workshop on Agent Building 2025
This repository contains materials for the TechFutures Workshop on Agent Building. It focuses on building multi-agent systems using the LangGraph library.

Event link: https://events.techfutures.com/2025/agenda/session/1733836
Slide deck: https://docs.google.com/presentation/d/1Io7YlYMVPc05ZWtk61sj00ZTVy2E5gyD/edit?usp=sharing&ouid=111830819194327605461&rtpof=true&sd=true

**SETUP**

Setup API KEYS!!
1. OPENAI_API_KEY: Obtain your API key from https://platform.openai.com/api-keys.
2. LANGSMITH_API_KEY: Obtain your API key for Langsmith tracing (optional but recommended for debugging).

Environment Variables
Set your API keys in the provided code cell:

**Using this in Google Colab**

Open this notebook in Google Colab.
Go to "Runtime" -> "Run all" to execute all cells.
Replace the placeholder values for OPENAI_API_KEY and LANGSMITH_API_KEY in the "Set your API keys here" code cell with your actual keys.
The notebook will then install the necessary packages, set the environment variables, define the agent system, and demonstrate example usage.

Learn how to create AI agents that can collaborate to solve complex problems. The workshop includes:
- **Exercise 1**: Sample LangGraph basics
- **Exercise 2**: Multi-agent Travel Itinerary System

### 🤖 Travel Itinerary Agent System

A sophisticated multi-agent system that generates comprehensive travel itineraries using a supervisor-based architecture.

#### Components:
- **Supervisor Agent** - Intelligent router with conditional logic
- **Generic Planner Agent** - Creates base itinerary
- **Weather Planner Agent** - Adds weather recommendations
- **Restaurant Planner Agent** - Suggests dining options
- **Synthesizer Agent** - Combines everything into polished output
