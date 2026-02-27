# Agents

This folder contains individual agent definitions and configurations.

## Structure

Each agent should live in its own subfolder:

```
agents/
└── my-agent/
    ├── README.md        # Purpose, inputs, outputs, dependencies
    ├── agent.yaml       # Agent configuration
    └── ...              # Any additional files (tools, configs, etc.)
```

## Guidelines

- Give each agent a clear, descriptive name.
- Document the agent's purpose, expected inputs, and outputs in its `README.md`.
- Keep agent configurations self-contained within their subfolder.
