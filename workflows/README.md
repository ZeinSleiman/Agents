# Workflows

This folder contains end-to-end agentic workflow definitions.

## Structure

Each workflow should live in its own subfolder:

```
workflows/
└── my-workflow/
    ├── README.md        # Steps, triggers, and expected outputs
    ├── workflow.yaml    # Workflow definition
    └── ...              # Supporting files
```

## Guidelines

- Document workflow steps, triggers, and expected outputs in the `README.md`.
- Compose existing skills and agents rather than duplicating logic.
- Keep workflow definitions declarative and easy to follow.
