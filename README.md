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

## How It Works
- **System Prompt**: Defines the assistant's behavior and capabilities. The assistant is instructed to use external tools to look up information.
- **Internet Search**: Utilizes the Tavily API to perform web searches and retrieve up-to-date information on the given query.
- **Function Calls**: When the assistant requires an external tool (like internet search), it invokes the appropriate function to gather information and continue the conversation.

## Example 

```bash
- $ python main.py
Welcome to the AI Chat! Type 'exit' to end the conversation.
You: Tell me the latest news about AI research.
Calling tool: search_internet
Arguments: {'query': 'latest AI research news'}
AI: The latest AI research indicates advances in generative models...
You: exit
AI: Goodbye!

```

## Future Enhancements

- **Additional Tools**: Integrate more tools for enhanced functionality, such as file retrieval, task management, or computational tools.
- **Advanced Conversation Logic**: Improve the assistant's ability to handle more complex queries that require multi-step reasoning.

## Contributing

- Contributions are welcome! Please feel free to submit a Pull Request or report issues via GitHub Issues.