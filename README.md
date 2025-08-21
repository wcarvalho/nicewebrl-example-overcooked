# Overcooked Example

This example demonstrates how to create a multi-agent web interface for the [JaxMARL Overcooked environment](https://github.com/FLAIROx/JaxMARL). Overcooked is a cooperative cooking game where two agents must work together to prepare and serve meals.

![Overcooked Environment](https://github.com/FLAIROx/JaxMARL/blob/main/docs/imgs/cramped_room.gif?raw=true)

## Features
- Multi-agent cooperative environment
- Cooking tasks requiring coordination
- Multiple layouts available
- Real-time interaction between two human players

## Installation

**Make sure you have CMake installed**

```bash
# Install uv if you haven't already
curl -LsSf https://astral.sh/uv/install.sh | sh

# Install dependencies
uv sync
```

## Running the Example
```bash
# Run the web app
uv run python web_app.py
```

Note: This example requires two players to connect to play together. 