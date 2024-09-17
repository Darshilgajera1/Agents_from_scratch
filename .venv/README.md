# AI Research Assistant with Tool Integration

This project implements an AI-powered research assistant that can use external tools such as internet search engines to enhance its ability to look up real-time information and provide insightful responses. It interacts with users via a chat-like interface, making it useful for research tasks where access to up-to-date information is crucial.

## Features
- **Tool Integration**: The assistant can perform internet searches to gather real-time information.
- **Dynamic Prompts**: System prompts are dynamic and can be customized based on the current date and situation.
- **Function Calls**: Supports AI-generated tool calls to invoke specific functions for external operations like searching the web.
- **Interactive Chat Interface**: Engages with users in a simple command-line interface, allowing for natural conversation.

## Technology Stack
- **Python**: Core language for implementing the AI assistant.
- **Tavily**: Used for performing internet searches via the Tavily API.
- **Litellm**: Helps with handling language model completions.
- **Python-dotenv**: Manages environment variables to securely store API keys and sensitive information.
- **Colorama**: Provides colored output for better readability in the terminal.

## Requirements
- Python 3.8 or later
- API keys for Tavily

### Python Libraries
You can install the required libraries by running:

```bash
pip install -r requirements.txt
