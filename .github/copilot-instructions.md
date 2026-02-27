# Copilot Instructions

This repository contains agents, skills, prompts, and agentic workflows used for AI-powered automation experiments.

## Repository Structure

```
agents/       # Agent definitions and configurations
skills/       # Reusable skills and tools that agents can invoke
prompts/      # Prompt templates used by agents and workflows
workflows/    # End-to-end agentic workflow definitions
```

## Guidelines

### Agents
- Each agent lives in its own subfolder under `agents/`.
- Include a `README.md` describing the agent's purpose, inputs, outputs, and any dependencies.
- Agent configuration files should be clearly named (e.g., `agent.yaml`, `agent.json`).

### Skills
- Each skill lives in its own subfolder under `skills/`.
- A skill should be focused on a single, well-defined capability.
- Include a `README.md` with usage examples and parameter descriptions.

### Prompts
- Store prompt templates under `prompts/`, organised by agent or use-case.
- Use descriptive file names (e.g., `summarise-document.md`, `extract-entities.txt`).
- Document any variables/placeholders at the top of each prompt file.

### Workflows
- Each workflow lives in its own subfolder under `workflows/`.
- Include a `README.md` explaining the workflow steps, triggers, and expected outputs.
- Prefer composing existing skills and agents rather than duplicating logic.

## Coding Conventions
- Prefer YAML for configuration files.
- Keep prompts version-controlled so changes are traceable.
- Document every agent, skill, and workflow with at least a short `README.md`.
