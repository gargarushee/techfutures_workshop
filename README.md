TechFutures Workshop on Agent Building
This repository contains materials for the TechFutures Workshop on Agent Building. It focuses on building multi-agent systems using the LangGraph library.

**SETUP**

Setup API KEYS!!
1. OPENAI_API_KEY: Obtain your API key from https://platform.openai.com/api-keys.
2. TAVILY_SEARCH: Sign up at https://www.tavily.com/ to get API KEY access for web search.
3. LANGSMITH_API_KEY: Obtain your API key for Langsmith tracing (optional but recommended for debugging).

Environment Variables
Set your API keys in the provided code cell:

**Using this in Google Colab**

Open this notebook in Google Colab.
Go to "Runtime" -> "Run all" to execute all cells.
Replace the placeholder values for OPENAI_API_KEY, TAVILY_API_KEY, and LANGSMITH_API_KEY in the "Set your API keys here" code cell with your actual keys.
The notebook will then install the necessary packages, set the environment variables, define the agent system, and demonstrate example usage.

Learn how to create AI agents that can collaborate to solve complex problems. The workshop includes:
- **Exercise 1**: Sample LangGraph basics
- **Exercise 2**: Multi-agent Travel Itinerary System

### 🤖 Travel Itinerary Agent System

A sophisticated multi-agent system that generates comprehensive travel itineraries using a supervisor-based architecture.

#### Components:
- **Supervisor Node** - Intelligent router with conditional logic
- **Generic Planner Agent** - Creates base itinerary
- **Weather Planner Agent** - Adds weather recommendations
- **Restaurant Planner Agent** - Suggests dining options
- **Finalize Node** - Combines everything into polished output
