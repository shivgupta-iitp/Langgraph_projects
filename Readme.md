# LangGraph Projects

A collection of educational projects built with [LangGraph](https://github.com/langchain-ai/langgraph), demonstrating core patterns for building stateful, multi-step AI workflows with LLMs.

## 📂 Projects

| Notebook | Description |
|----------|-------------|
| [`chatbot.ipynb`](./chatbot.ipynb) | A foundational conversational chatbot built as a LangGraph graph, covering state management, nodes, edges, and message passing. |
| [`humanintheloop.ipynb`](./humanintheloop.ipynb) | Demonstrates the human-in-the-loop pattern: interrupting graph execution, inspecting/approving state, and resuming the workflow with human feedback. |
| [`multiaiagent.ipynb`](./multiaiagent.ipynb) | A multi-agent system where specialized AI agents collaborate (e.g., routing, tool use, and delegation) to solve tasks within a single LangGraph workflow. |

## 🧠 Concepts Covered

- **Graph-based orchestration** — modeling LLM workflows as nodes and edges
- **State management** — shared, typed state passed between steps
- **Conditional routing** — dynamic control flow between nodes
- **Human-in-the-loop** — pausing, inspecting, and resuming graph execution
- **Multi-agent collaboration** — coordinating multiple specialized agents

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- A Jupyter environment (Jupyter Notebook / JupyterLab / VS Code)
- API keys for the LLM provider(s) used (e.g., OpenAI, Anthropic)

### Installation

```bash
# Clone the repository
git clone https://github.com/shivgupta-iitp/Langgraph_projects.git
cd Langgraph_projects

# (Recommended) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

Set your API key(s) as environment variables before running the notebooks:
Running = jupyter notebook

Then open any of the .ipynb files and run the cells in order.

📋 Requirements
Dependencies are listed in requirements.txt. Core libraries include LangGraph, LangChain, and the relevant LLM provider SDKs.

🎯 Purpose
These projects are educational — built to explore and demonstrate LangGraph's capabilities. They're intended as learning references and starting points for building more complex, stateful LLM applications.

🤝 Contributing
This is a personal learning repository. Feel free to fork it, open issues, or suggest improvements.

📄 License
No license specified. If you plan to share or reuse this code, consider adding one (e.g., MIT).

Author: shivgupta-iitp
