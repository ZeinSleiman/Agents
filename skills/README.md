# Skills

This folder contains reusable skills and tools that agents can invoke.

## Structure

Each skill should live in its own subfolder:

```
skills/
└── my-skill/
    ├── README.md        # Description, parameters, usage examples
    └── ...              # Implementation files
```

## Guidelines

- A skill should have a single, well-defined responsibility.
- Document all parameters and return values in the skill's `README.md`.
- Skills should be reusable across multiple agents and workflows.
