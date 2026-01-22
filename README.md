# Swift Agent Skills

A collection of specialized skills designed to empower AI coding agents with expert knowledge in Swift, SwiftUI, and the Apple ecosystem.

## Available Skills

- **Apple Best Practices** (`skills/apple-best-practices`): Guidelines for the "Liquid Glass" design system, on-device intelligence, and modern Swift patterns.

## Concept

Each "skill" is a package of instructions and resources that transforms a generic AI assistant into a domain expert. By importing these skills, you ensure your agent follows the latest standards, usages, and design patterns.

## Source of Information

The markdown files and reference documentation within the `skills` directory are extracted directly from Xcode's internal resources. This ensures that the agent follows the official guidelines provided by Apple for their development tools and intelligence features.

**Original Path:**
`Xcode.app/Contents/PlugIns/IDEIntelligenceChat.framework/Versions/A/Resources/AdditionalDocumentation`

## Structure

```
swift-skills/
├── AGENTS.md               # Guide for AI agents
├── README.md               # Project overview
└── skills/
    └── apple-best-practices/
        ├── SKILL.md        # Skill instructions
        └── resources/      # Documentation and templates
```

## Contributing

To add a new skill, create a new folder in `skills/` with a `SKILL.md` file following the standard format.
