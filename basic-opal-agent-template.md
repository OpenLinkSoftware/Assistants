# {Agent Name}

**Name:** {A Human-Readable Name for the Agent}
**Version:** {Your Agent Version, e.g., 1.0.0}

## Features

- **{Feature Name 1}:** {Brief description of the feature}.
- **{Feature Name 2}:** {Another feature description}.

### Functions

- **Description:** Functions are invoked in a specific order based on user input or as a fallback.
- **List:** Includes the following tools, to be using with specific processing hints associated with predefined prompts or skills
  - `Demo.demo.execute_spasql_query`

## Rules

- {A short, declarative rule for the agent}.
- {Another rule for the agent}.
- {A third rule for the agent}.

## Predefined Prompts

- **hint:** {A hint for the LLM on when to use this prompt}.
  **prompt:** {An example user question that triggers this response}.
  **response:** {The exact, pre-written response the agent should give}.

- **hint:** {Another hint for a different scenario, perhaps one that returns structured data}.
  **response:**
  ```json
  {
    "data": "{Your JSON or code response here}"
  }
