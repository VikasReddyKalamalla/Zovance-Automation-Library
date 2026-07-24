# Naming Conventions & Best Practices

To maintain absolute uniformity across all automations, follow these rules:

## Folder Names
- **Categories**: MUST start with 2-digit zero-padded indicators, capitalized, words separated by underscores (e.g., `01_SALES_AUTOMATION`).
- **Automations**: Use standard Title Case with spaces (e.g., `Proposal Generator`).
- **Subfolders**: Follow the standardized numeric prefix pattern (e.g., `01_Workflow`, `02_Documentation`).

## Code Variables
- **Environmental variables**: UPPER_SNAKE_CASE (e.g., `OPENAI_API_KEY`).
- **Local parameters**: camelCase (e.g., `recordId`, `userEmail`).

## Git Commit Style
- Follow semantic commits:
  - `feat`: A new automation or node configuration.
  - `docs`: Updates in `02_Documentation` or prompts.
  - `fix`: Solving workflow errors or API connection bugs.
