# aichatbot
# Agentic Meeting Assistant Bot

An AI-powered agent that transforms **meeting transcripts** into:
- Concise summaries  
- Actionable tasks with deadlines & owners  
- Context-aware insights using past meetings  

Built with **React + FastAPI + Groq + RAG + Whisper**.

## Features
- LLM-powered meeting summarization  
- Task extraction with owner & deadline  
- Contextual memory using RAG (FAISS + HuggingFace)  
- Speaker tagging & tone awareness  
- Google Calendar sync *(coming soon)*  
- Export to Slack, Notion, Email *(coming soon)*  
- Meeting health score *(coming soon)*  

## Project Structure
agentic-bot/
├── backend/ # FastAPI + Langchain RAG + Groq API
│ ├── main.py
│ └── past_meetings/
├── frontend/ # React + Tailwind + ShadCN
│ ├── src/
│ └── index.tsx


