# 📝 Agentic AI Blog Generation System

An end-to-end Agentic AI application built using LangGraph and FastAPI that automatically generates structured, SEO-friendly blog content from a topic prompt. The system orchestrates multiple LLM agents (title generation, content synthesis, translation) using a stateful graph-based workflow with typed state propagation.

The project supports multilingual blog generation via conditional routing (e.g., English → Hindi/French) and provides full execution tracing, debugging, and human-in-the-loop control through LangSmith and LangGraph Studio. Designed with a modular architecture to enable easy extension to additional languages, agents, or content sources (e.g., video transcripts).
