# Travel Planning AI Agents

This repository demonstrates the implementation of a multi-agent AI system for generating travel plans. The system uses OpenAI's GPT-based language models to facilitate communication between specialized agents, each tasked with a unique role in the planning process. The agents collaborate in a round-robin style to create an integrated and comprehensive travel itinerary.

## Features

- **Multi-Agent Collaboration**: Includes specialized agents for planning, local recommendations, language tips, and itinerary summarization.
- **Customizable Termination**: Uses a termination condition (`TERMINATE`) to signal when the planning process is complete.
- **Interactive Console**: Allows users to query the system and receive travel plans interactively.
- **Streaming Responses**: Supports real-time response streaming for dynamic interaction.

## High-Level Functionality

1. **Planner Agent**: Creates a high-level travel itinerary.
2. **Local Agent**: Suggests authentic and interesting local activities or destinations.
3. **Language Agent**: Provides critical tips for communication and language barriers.
4. **Summary Agent**: Integrates all input into a final, detailed travel plan.

## Example Usage

The system can be used to generate a detailed travel plan by providing a query like:

```plaintext
"Plan a three-day trip to Barcelona."
