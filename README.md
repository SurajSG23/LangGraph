# Repo Content:
```
├── Module-1.ipynb     # Introduction to LangGraph
├── Module-2.ipynb     # Annotated Construct and Reducer Functions
├── Module-3.ipynb     # Thread-Level Persistence
```
# LangGraph

* **LangGraph** is a way to connect multiple steps (like prompts, models, or tools) into a graph instead of a straight line.
* Useful for building apps where you need branching, parallel steps, or structured workflows.

## Key Parts

* **Node** → A single step (e.g., LLM call, retriever, parser).
* **Edge** → Connection that passes data from one node to another.
* **Graph** → The whole workflow of nodes + edges.

## Stateful vs Stateless

* **Stateless**: Each run starts fresh, no memory of past runs.
* **Stateful**: The graph remembers information across steps (like conversation history or intermediate results).

## Why it matters

* Nodes + edges define how data flows.
* Statefulness makes LangGraph useful for chatbots, multi-step reasoning, and workflows where context must be remembered.

---
