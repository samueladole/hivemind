# 🐝 HiveMind

**Collective Intelligence for Autonomous Agents**

HiveMind is a modular multi-agent AI framework built with LangChain and LangGraph.

Inspired by the collective intelligence of a beehive, HiveMind enables specialized AI agents to collaborate, reason, and execute complex tasks through a shared orchestration layer.

Whether you're building research assistants, coding agents, workflow automations, or autonomous AI systems, HiveMind provides a scalable foundation for agent collaboration.

## Features

- 🤖 Multi-agent architecture
- 🧠 Agent orchestration and delegation
- 🔧 Extensible tool ecosystem
- 📚 RAG and knowledge retrieval support
- 💾 Short-term and long-term memory
- 🔄 LangGraph-powered workflows
- 📊 Observability and evaluation ready
- ⚡ Support for multiple LLM providers

## Architecture

```text
                    User Request
                          │
                          ▼
                  Orchestrator Agent
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼
  Research Agent    Coding Agent    Analysis Agent
        │                 │                 │
        └─────────────────┼─────────────────┘
                          ▼
                   Reviewer Agent
                          │
                          ▼
                    Final Response
```

## Installation

```bash
git clone https://github.com/samueladole/hivemind.git
cd hivemind
uv sync
```

## Configuration

Create a `.env` file:

```env
OPENAI_API_KEY=your_key
ANTHROPIC_API_KEY=your_key
```

## Run

```bash
uv run python main.py
```

## Example Use Cases

- AI research assistant
- Software engineering agents
- Document analysis
- Autonomous task execution
- Workflow automation
- Knowledge management systems
- Multi-step reasoning pipelines

## Roadmap

- [ ] Agent marketplace
- [ ] Dynamic agent creation
- [ ] Human-in-the-loop workflows
- [ ] Multi-modal support
- [ ] Distributed agent execution
- [ ] Agent memory persistence
- [ ] Built-in evaluation framework

## Tech Stack

- LangChain
- LangGraph
- Pydantic
- FastAPI
- OpenAI
- Anthropic
- Ollama
- ChromaDB / Qdrant

## License

MIT

---

*Individual agents think. HiveMind collaborates.*
