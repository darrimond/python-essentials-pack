# Python Essentials Pack

A focused VS Code extension pack for Python developers who want a practical setup without a bloated extension list.

Python Essentials Pack installs a curated set of extensions for the day-to-day Python workflow: language support, linting and formatting, notebooks, Git context, containers, remote development, API testing, and AI-assisted coding.

## Included Extensions

- `ms-python.python` - Core Python support for editing, debugging, environments, testing, and IntelliSense.
- `charliermarsh.ruff` - Fast Python linting and formatting powered by Ruff.
- `ms-toolsai.jupyter` - Notebook support for data exploration, experiments, and interactive workflows.
- `eamodio.gitlens` - In-editor Git history, blame, and change insight.
- `ms-azuretools.vscode-docker` - Docker tooling for containerized Python apps and services.
- `ms-vscode-remote.remote-wsl` - Smooth development inside WSL for Linux-based Python environments.
- `postman.postman-for-vscode` - API testing and request workflows without leaving VS Code.
- `anthropic.claude-code` - AI-assisted coding support for navigating, editing, and iterating on Python projects.

## Why This Pack

- Keeps the toolset intentionally small and useful.
- Covers common Python workflows on a fresh machine.
- Works well for app development, scripting, notebooks, and team onboarding.
- Leaves room to add specialized extensions only when a project needs them.

## Best For

- Developers setting up Python in VS Code for the first time
- Teams that want a lean, shared default extension baseline
- Learners who want a strong Python workflow without hunting through the marketplace

## What This Pack Does Not Include

This extension pack installs editor extensions only. It does not install Python, Ruff, Docker, WSL, or any project dependencies for you.

Before you start, make sure your machine has the tools your workflow needs, such as:

- `python`
- `pip` or your preferred package manager
- `ruff` if you want a local Ruff binary in your environment
- Docker Desktop or another Docker runtime if you use containers
- WSL if you plan to develop in a Linux environment on Windows

## Quick Start

1. Install the pack from the VS Code Marketplace.
2. Open a Python project or create a new workspace.
3. Select your Python interpreter in VS Code.
4. Let the Python and Ruff extensions initialize for the workspace.
5. Use Jupyter for notebooks, Docker for containers, and Remote WSL when your project calls for them.

## Philosophy

Python Essentials Pack is intentionally opinionated: start with a compact, high-value baseline first, then add niche tools only when they earn their place in your workflow.

## License

MIT
