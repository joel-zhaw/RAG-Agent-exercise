# RAG-Agent-exercise

## 🎯 Learning goals for today

By the end of this exercise, you will:

- **Build a state-of-the-art agent** using a modern framework (LangGraph) that can **decide** when to call a tool.
- **Understand what a retriever does** in RAG: turn a question into a vector search and return the most relevant text chunks.
- **Wrap retrieval as a Tool** so the agent/router can call it on demand.
- **Inspect the decision flow** (route → retrieve → grade → rewrite/answer) and explain why each step exists.
- **Practice basic quality control**: grade retrieved chunks for relevance; avoid answering from poor context.
- **Run the full pipeline** end-to-end and expose a **simple function** (`run_agent(question)`) suitable for a frontend.

> Outcome: you’ll have a minimal, production-shaped agent that’s easy to reason about—and you’ll know when and why it retrieves.