[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/dafnckstudio-dafnckmachine-v3-1-badge.png)](https://mseep.ai/app/dafnckstudio-dafnckmachine-v3-1)

$$$$$$$\   $$$$$$\  $$$$$$$$\ $$\   $$\  $$$$$$\  $$\   $$\ 
$$  __$$\ $$  __$$\ $$  _____|$$$\  $$ |$$  __$$\ $$ | $$  |
$$ |  $$ |$$ /  $$ |$$ |      $$$$\ $$ |$$ /  \__|$$ |$$  / 
$$ |  $$ |$$$$$$$$ |$$$$$\    $$ $$\$$ |$$ |      $$$$$  /  
$$ |  $$ |$$  __$$ |$$  __|   $$ \$$$$ |$$ |      $$  $$<   
$$ |  $$ |$$ |  $$ |$$ |      $$ |\$$$ |$$ |  $$\ $$ |\$$\  
$$$$$$$  |$$ |  $$ |$$ |      $$ | \$$ |\$$$$$$  |$$ | \$$\ 
\_______/ \__|  \__|\__|      \__|  \__| \______/ \__|  \__|


# 🚀 DafnckMachine - Agentic Coding Framework

*Automate Your Vision into Realit - Build anything !*
*Transforming software / app / saas / game development with spec-driven, AI-powered agentic workflows.*

----

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-3.1-informational)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange)

---

# DafnckMachine-V3.1
## Autonomous AI Workflow Orchestration Platform

---

## 🚀 What is DafnckMachine?

DafnckMachine is a next-generation, agent-driven workflow orchestration platform designed for AI-augmented software development. It enables both AI agents and human users to collaborate on complex projects, automating everything from requirements gathering to deployment and continuous improvement.

- **Multi-agent system**: 67+ specialized agents for every phase of the SDLC.
- **Smart Brain System**: DNA, STEP, GENESIS JSONs for state, workflow, and learning.
- **Task Master Integration**: Full-featured task breakdown, tracking, and automation.
- **Performance-optimized**: Lightweight configs, caching, and real-time state sync.
- **Cursor/RooCode Ready**: Native support for agent invocation and workflow navigation.

---

# How to Start from a Small Idea or Blank Slate

You can begin your DafnckMachine project with just a rough idea, a few features, or even nothing at all!

1. **Open and Edit `@Project.md`:**
   - Jot down any initial thoughts, goals, or features you have in mind—even if it's just a sentence or a few bullet points.
   - This file will serve as the seed for your project vision and requirements.
   - Don't worry about completeness; you can always update it later.

2. **Save `@Project.md`**
   - The more detail you provide, the less the agents will need to ask. But you can start with as little as a single idea.

3. **Prompt the System (Recommended):**
   - In Cursor or RooCode chat, type `@uber-orchestrator-agent` and describe your idea, or simply ask "Help me start a new project."
   - The orchestrator agent will analyze your `@Project.md`, ask for any missing info, and guide you through the next steps.

4. **Start the Workflow (Optional):**
   - For a full environment setup, begin with [`00_Project_Initialization.md`](01_Machine/01_Workflow/Phase 0 : Project Setup/00_Project_Initialization.md).
   - For user context and requirements gathering, start with [`P01-S01-T01-User-Profile-Development.md`](01_Machine/01_Workflow/Phase 1: Initial User Input & Project Inception/01_User_Briefing/P01-S01-T01-User-Profile-Development.md).

5. **Let the Agents Guide You:**
   - The agents will read your `@Project.md` and only ask for missing or unclear information.
   - They will guide you through the rest of the process, step by step, adapting to what you have already provided.

**Tip:** If you're unsure where to start, just type `@uber-orchestrator-agent` in chat and say "Start my project"—the system will handle the rest!

**The workflow is adaptive—add as much or as little as you want to `@Project.md`. The system will fill in the gaps and help you clarify your vision as you go!**

---

---

## 🏗️ System Architecture

```
DafnckMachine-V3.1/
├── 01_Machine/           # The Engine (How to execute)
│   ├── 01_Workflow/      # Step-by-step execution plans
│   ├── 02_Agents/        # Agent definitions and capabilities  
│   ├── 03_Brain/         # Intelligence system (DNA, STEP, GENESIS)
│   └── 04_Documentation/ # System documentation
├── 02_Vision/            # The Strategy (What to build)
│   ├── Project goals and vision
│   ├── Strategic direction
│   └── High-level requirements
└── 03_Project/           # The Output (What gets built)
    ├── Actual project files
    ├── Generated code
    └── Implementation artifacts
```

- **DNA.json**: Agent registry, capabilities, and communication protocols
- **STEP.json**: Execution engine with task mapping and state management
- **GENESIS.json**: Adaptive configuration and learning system
- **AGENT_INTERFACE.json**: ⚡ Performance-optimized lightweight configs

---

## ⚡ Quick Start

### For AI Agents (Cursor/RooCode)

1. **Open the current workflow file**:  
   `01_Machine/01_Workflow/{Phase}/[Step].md`
2. **Read the Agent Context** at the top for instructions and config.
3. **Use `@agent-name` in Cursor/RooCode chat** to invoke a specific agent (see below).
4. **Follow the numbered tasks** (1.1, 1.2, etc.) in the workflow file.
5. **Output results** to `03_Project/{step_outputs}/`.
6. **Update progress** in the workflow file and state JSONs.
7. **Navigate to the next step** using the provided links.

### For Human Users (CLI/Manual)

1. **Review the architecture**:  
   `01_Machine/04_Documentation/01_System/Project_Structure_Integration.md`
2. **Check the Agent Operations Manual**:  
   `01_Machine/04_Documentation/01_System/Agent_Operations_Manual.md`
3. **Monitor progress** in `01_Machine/01_Workflow/` files.
4. **Review outputs** in `03_Project/` directories.
5. **Use Task Master CLI** for task management (see below).

---

## 🤖 Using with Cursor/RooCode

- **Invoke agents** in chat with `@agent-name` (e.g., `@coding-agent`, `@uber-orchestrator-agent`).
- **Agents collaborate**: Mention multiple agents for complex tasks.
- **Agent context**: Each workflow file specifies the responsible agent and their capabilities.
- **Workflow navigation**:  
  - Use the links in workflow files to move between steps.
  - Progress and state are tracked in `01_Machine/03_Brain/Step.json` and `workflow_state.json`.
- **Best practices**:
  - Be specific in your requests to agents.
  - Reference the correct agent for each phase (see agent list below).
  - Combine agents for multi-domain tasks.
  - Provide context for better results.

**Example agent invocations:**
```
@uber-orchestrator-agent Planifie la roadmap de ce projet
@coding-agent Implémente une API REST pour la gestion des tâches
@ui-designer-agent Propose un design moderne pour le dashboard
```

---

## 🛠️ Task Master Workflow (MCP & CLI)

DafnckMachine uses Task Master for all task, subtask, and workflow management.

### **MCP Server (Recommended for Cursor/RooCode)**
- Use integrated tools (MCP) for best performance and error handling.
- Key commands:
  - `get_tasks` / `task-master list`
  - `next_task` / `task-master next`
  - `expand_task` / `task-master expand --id=<id>`
  - `set_task_status` / `task-master set-status --id=<id> --status=done`
  - `add_task`, `add_subtask`, `update_task`, `update_subtask`, etc.

### **CLI Usage**
- Install: `npm install -g task-master-ai`
- Or use locally: `npx task-master-ai ...`
- See `.roo/rules/taskmaster.md` for full command reference.

### **Workflow Example**
1. `task-master init` — Initialize project structure.
2. `task-master parse-prd --input='scripts/prd.txt'` — Generate initial tasks.
3. `task-master list` — View all tasks.
4. `task-master next` — See the next actionable task.
5. `task-master expand --id=1 --force --research` — Break down complex tasks.
6. `task-master set-status --id=1.1 --status=done` — Mark subtasks as complete.

---

## 🧠 Agent System & Collaboration

- **67+ specialized agents** for every phase of the SDLC.
- **Invoke with `@agent-name`** in Cursor/RooCode or reference in workflow files.
- **Collaboration**: Agents can be combined for multi-domain tasks.
- **Agent registry**: See `01_Machine/02_Agents/` and `DNA.json` for full list.

**Key agent categories:**
- **Orchestration**: `@uber-orchestrator-agent`, `@development-orchestrator-agent`
- **Planning**: `@task-planning-agent`, `@prd-architect-agent`
- **Development**: `@coding-agent`, `@system-architect-agent`, `@code-reviewer-agent`
- **Design/UX**: `@ui-designer-agent`, `@ux-researcher-agent`, `@design-system-agent`
- **Testing**: `@test-orchestrator-agent`, `@functional-tester-agent`, `@security-auditor-agent`
- **Documentation**: `@scribe-agent`, `@documentation-agent`, `@elicitation-agent`
- **DevOps**: `@devops-agent`, `@adaptive-deployment-strategist-agent`
- **Analytics/Marketing**: `@analytics-setup-agent`, `@marketing-strategy-orchestrator`

**See**:  
- `01_Machine/04_Documentation/01_System/AGENTS_README.md`  
- `01_Machine/04_Documentation/01_System/AGENT_GUIDE.md`  
- `.roo/rules/dev_workflow.md` for agent workflow best practices.

---

## 📁 Directory & Documentation

- **01_Machine/01_Workflow/**: Step-by-step execution plans (primary workspace)
- **01_Machine/02_Agents/**: Agent definitions and capabilities
- **01_Machine/03_Brain/**: Core system state (DNA, STEP, GENESIS, AGENT_INTERFACE)
- **01_Machine/04_Documentation/**: System docs, templates, and guides
- **02_Vision/**: Project vision, strategy, and high-level requirements
- **03_Project/**: All generated outputs and deliverables

**Key docs:**
- `01_Machine/04_Documentation/01_System/Agent_Operations_Manual.md`
- `01_Machine/04_Documentation/01_System/Project_Structure_Integration.md`
- `01_Machine/04_Documentation/01_System/Template-Step-Structure.md`
- `.roo/rules/dev_workflow.md`
- `.roo/rules/taskmaster.md`
- `.roo/rules/self_improve.md`

---

## 🎯 Best Practices

- **Start with workflow files** — All instructions are embedded.
- **Use lightweight configs** — AGENT_INTERFACE.json for most operations.
- **Follow numbered task structure** — 1.1, 1.2, 2.1, etc.
- **Update progress in real-time** — Keep checklists current.
- **Reference vision strategically** — Only when needed for decisions.
- **Output to structured directories** — Follow 03_Project/ organization.
- **Iterate and improve rules** — See `.roo/rules/self_improve.md`.

---

## 🔧 Troubleshooting & Continuous Improvement

- **Agent not responding?** — Check Agent Context in workflow file and agent registry.
- **Performance issues?** — Use lightweight configs, check for caching.
- **Task Master errors?** — Ensure API keys are set in `.env` or `.cursor/mcp.json`.
- **Rule evolution** — Add/update rules in `.roo/rules/` as new patterns emerge.
- **Validate agents** — Use unified agent validator scripts in `01_Machine/03_Brain/Agents-Check/`.

---

## 📈 System Evolution

- **GENESIS system** learns from agent performance and usage.
- **Automatic optimization** and real-time adaptation.
- **Performance feedback loops** for system enhancement.

---

## 📝 Contributing

- **Add new agents** in `01_Machine/02_Agents/` and update `DNA.json`.
- **Document new steps** using `Template-Step-Structure.md`.
- **Improve rules** in `.roo/rules/` as new best practices emerge.
- **See**: `01_Machine/04_Documentation/01_System/00_Documentation_Index.md` for step documentation.

---

## 🧪 Agent Validation & System Health

### What is `unified_agent_validator.py` and `unified_agent_validator.sh`?

- **Location:** `01_Machine/03_Brain/Agents-Check/`
- **Purpose:** These scripts validate all agent definitions, check for errors, repair common issues, and ensure the system is ready for use.
- **Features:**
  - Validate agent JSON structure and required fields
  - Auto-repair common format and reference issues
  - Test agent loading and system initialization
  - Generate comprehensive health reports
  - Sync agent definitions to `.roomodes` (RooCode) and `.cursorrules` (Cursor)
- **How to use:**
  - Run `python3 unified_agent_validator.py` (for full-featured validation, repair, and reporting)
  - Or run `bash unified_agent_validator.sh` (for shell-based validation and repair)
  - Use menu options or CLI flags for repair, sync, and report generation
  - See script comments and help output for advanced usage

---

## ⚙️ MCP Server Configuration

DafnckMachine uses MCP servers for advanced agent and workflow integration (Cursor, RooCode, Task Master, etc).

### How to Set Up MCP Servers

1. **Locate the template config:**
   - `.roo/mcp-template.json` (for RooCode)
   - `.cursor/mcp-template.json` (for Cursor)
2. **Copy and rename:**
   - Remove `-template` from the filename (e.g., `.roo/mcp.json`)
3. **Edit the config:**
   - Fill in your API keys for each service (e.g., Anthropic, Perplexity, Supabase, GitHub, Stripe, etc.)
   - Update any paths or user IDs as needed
   - Do **not** share your API secrets publicly
4. **Supported servers (examples):**
   - `taskmaster-ai` (Task Master integration)
   - `supabase` (database)
   - `github` (repo management)
   - `firebase`, `playwright`, `puppeteer`, `stripe`, `context7`, `perplexity-mcp`, `shadcn`, `langgraph`, `three-devtools`, `elizaOS`, `memory`, `everything`, `railway`, `Framelink Figma MCP`, `A2A Docs`, `Pheromind Docs`, `n8n Docs`, `chakra-ui Docs`, `@21st-dev/magic`, etc.
   - Add or remove servers as needed for your project
5. **Activate the config:**
   - The system will use `.roo/mcp.json` or `.cursor/mcp.json` automatically if present
   - Restart your MCP server or reload your workspace if needed

**Note:**
- Never commit your API secrets to public repositories.
- See the template files for all available server options and required fields.
- For more details, see the comments in the template files and the main README.

---

**Last Updated**: 2025-06-05  
**Support**: See `01_Machine/04_Documentation/`  
**Brain Status**: Optimized for performance and usability  
**Performance**: Lightweight interface active