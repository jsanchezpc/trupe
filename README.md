# 🚀 Trupe – Multi-Agent AI System with crewAI

<div align="center">

![Trupe Logo](https://img.shields.io/badge/AI%20Agents-crewAI-blueviolet?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10%20--%203.13-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-Custom-informational?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Alpha-orange?style=for-the-badge)

</div>



Welcome to **Trupe**, an advanced multi-agent AI system powered by [crewAI](https://crewai.com). Trupe is designed to orchestrate collaborative agents that solve complex tasks through intelligent coordination. Whether you're building autonomous workflows or exploring the future of AI teamwork, Trupe offers a solid foundation.

---

## 📌 What is Trupe?

**Trupe** is a Python-based application built on the [crewAI](https://crewai.com) framework. It empowers you to define, train, and deploy intelligent agents with distinct roles who collaborate to complete multifaceted tasks—like researching topics and generating structured reports.

Out of the box, Trupe comes with:
- A **Research Agent** for gathering knowledge
- A **Reporting Analyst** for transforming findings into coherent documentation

---

## ✨ Key Features

- 🤖 **Multi-Agent Collaboration** – Distribute and coordinate tasks between specialized agents
- 🧠 **Configurable Agent Profiles** – Define custom roles, goals, and personalities
- 🧰 **Tool Integration** – Extend agents with custom tools and functions
- 🔁 **Training & Feedback Loop** – Iteratively improve agent output with training iterations
- 🔍 **Replay & Debugging** – Revisit past executions for evaluation or demonstration
- 🧪 **Built-in Testing** – Validate system behavior and outputs

---

## ⚙️ Installation

### Requirements
- Python **3.10** to **3.13**
- `pip` for package management

### Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd trupe
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # or .venv\Scripts\activate on Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -e .
   ```

---

## 🚦 Usage

### Run the Crew
Start the agent system and execute the default workflow:
```bash
run_crew
# or
trupe
```

📝 This generates a `report.md` with research findings on AI LLMs by default.

---

### Train Your Crew
Improve agent behavior over multiple iterations:
```bash
train <iterations> <filename>
```

- `iterations`: Number of training loops
- `filename`: Output file for results

---

### Replay a Task
Re-execute a past task for debugging or review:
```bash
replay <task_id>
```

---

### Test the System
Run all agents and validate outputs:
```bash
test
```

---

## 📁 Project Structure

```
trupe/
├── config/
│   ├── agents.yaml       # Agent roles, goals, and backstories
│   └── tasks.yaml        # Task definitions and output expectations
├── crew.py               # Crew configuration and orchestration logic
├── main.py               # CLI entry points for run, train, replay, and test
└── tools/                # Custom tools and utilities for agents
```

---

## 🧠 Agent Overview

Trupe's strength lies in its modular agents, defined in YAML configs.

### Default Agents
- **🧑‍🔬 Researcher** – Expert in finding the latest and most relevant insights
- **📊 Reporting Analyst** – Synthesizes raw information into structured reports

### Default Tasks
- **Research Task** – Extract relevant knowledge about a given topic
- **Reporting Task** – Format the research into a human-readable report (`markdown`)

You can easily customize or expand the crew by editing the YAML files in `config/`.

---

## 🛠 Customization

Tailor Trupe to your needs by:

- Updating agent profiles in `config/agents.yaml`
- Defining new tasks in `config/tasks.yaml`
- Creating tools under `tools/` to enhance agent capabilities
- Extending logic in `crew.py` for new behaviors

---

## 📜 License

> Specify your license here (e.g. MIT, Apache 2.0, etc.)

---

## 🤝 Contributing

> Contributions are welcome! Feel free to open issues or submit pull requests.
> [Specify detailed guidelines here if needed.]

---

## 🙏 Acknowledgements

- 💡 Built with [crewAI](https://crewai.com) – a powerful framework for multi-agent AI systems.
- 💻 Inspired by the potential of autonomous, collaborative AI.

---

Ready to assemble your own AI crew?  
Let **Trupe** be your command center.