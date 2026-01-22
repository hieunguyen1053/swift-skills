---
description: Create a new skill in the swift-skills repository
---

This workflow helps you create a structured folder for a new skill.

1.  Ask the user for the `skill-name` (kebab-case) and a brief `description`.
2.  Create the directory: `skills/<skill-name>/`.
3.  Create the `resources` directory: `skills/<skill-name>/resources/`.
4.  Create the `SKILL.md` file in `skills/<skill-name>/` with the following template:

```markdown
---
name: <skill-name>
description: <description>
version: 1.0
license: MIT
---

# <Title Case Skill Name>

Short description of what this skill does.

## Capabilities

- List what this skill enables the agent to do.

## Instructions

1.  **Step 1**: ...
2.  **Step 2**: ...

## Resources

- List files in resources/ here.
```

5.  Notify the user that the skill scaffold is ready.
