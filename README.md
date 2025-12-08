# Jira Voice Assistant

## Project Summary 

This project explores the intersection of Voice AI and DevOps automation. The goal is to build a hands-free assistant that allows users to create and manage Jira tickets using natural language commands. Unlike standard chatbots, this system acts as a "translation engine," converting raw audio input into structured JSON data that executes precise actions via the Jira REST API.

This is a learning-focused project designed to understand the fundamental data flow between Audio Processing, Large Language Models (LLMs) for reasoning, and third-party APIs without relying on abstraction frameworks like LangChain initially.

## Key Tools & Tech Stack

- Python: Primary programming language.
- SpeechRecognition / PyAudio: The "Ears" of the system—handles microphone input and captures audio.
- OpenAI API: The "Brain"—performs Speech-to-Text (Whisper) and extracts Intent/Entities (GPT-4o/3.5) to generate structured JSON.
- Jira Python Library: The "Hands"—wraps the Jira REST API to authenticate and execute commands (Create, Update, Delete).
