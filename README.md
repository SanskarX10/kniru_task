# kniru_task
task for AI intern at kniru

# FinBot

FinBot is a personal finance manager built using LangChain, OpenAI, and Streamlit. It utilizes the GPT-3.5 Turbo model from OpenAI to provide an AI-powered conversational interface for managing personal finance queries.

## Usage

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies by running the following command: pip install -r requirements.txt

3. Obtain an OpenAI API key and provide it when prompted by the application.
4. Start the application by running the following command:
streamlit run fin_bot.py

5. Access the application in your web browser at `http://localhost:8501`.

## Features

- Allows users to have interactive conversations with the AI-powered personal finance assistant.
- Provides a chat interface where users can ask questions or seek advice regarding personal finance management.
- Stores conversation sessions and allows users to review past conversations.
- Allows users to start a new chat session and clear all stored conversation sessions.

## Configuration

The application allows some configuration options through the sidebar:

- Preview memory store: Check this option to view the memory store.
- Preview memory buffer: Check this option to view the memory buffer.
- Model: Select the language model to use (currently only supports "gpt-3.5-turbo").
- Summary of prompts to consider: Specify the number of prompts to consider for entity memory.

## Dependencies

The project relies on the following dependencies:

- Streamlit
- LangChain
- OpenAI
