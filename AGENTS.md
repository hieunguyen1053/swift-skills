# Agent Instructions

This repository contains "skills" designed to enhance your capabilities when working on Swift, SwiftUI, and Apple platform projects.

## Repository Structure

- **`skills/`**: This directory contains the individual skills.
- **`skills/<skill-name>/`**: Each subdirectory represents a specific skill (e.g., `modern-swift-practices`).
- **`skills/<skill-name>/SKILL.md`**: The primary instruction file for the skill. **You MUST read this file** to understand how to use the skill.
- **`skills/<skill-name>/resources/`**: (Optional) Supplementary markdown files, templates, or code snippets referenced by the skill.
- **`skills/<skill-name>/scripts/`**: (Optional) Helper scripts.

## How to Use a Skill

When a user's request aligns with a skill in this repository:

1.  **Locate the Skill**: Identify the relevant directory in `skills/`.
2.  **Read Instructions**: Use `view_file` to read the `SKILL.md` file.
3.  **Follow Protocol**: Adhere to the `Instructions` and `Capabilities` defined in `SKILL.md`.
4.  **Leverage Resources**: If the skill points to files in `resources/`, read them as needed to extract specific code patterns or guidelines.

## Creating New Skills (Meta)

If you are asked to create a new skill:
1.  Create a new directory: `skills/<new-skill-name>` (use kebab-case).
2.  Create `skills/<new-skill-name>/SKILL.md`.
3.  Define `name`, `description`, `version`, and `license` in the YAML frontmatter.
4.  Write clear instructions, capabilities, and examples in the body.
