# AI-Powered Conversational Customer Support Chatbot

## Setup Instructions
```bash
docker build -t chatbot .
docker run -p 8000:8000 chatbot
```

## Architecture
- Uses a simple file-based knowledge base
- LLM for understanding and generating responses
- Context handling and fallback mechanism included

## Prompt Engineering
Uses keyword and embedding matching to create context-aware responses.

## Limitations
- Basic memory implementation
- Responses limited to static KB context

## Future Improvements
- Add UI (Streamlit)
- Vector DB for advanced context
