# Swift Agent Skills

A collection of specialized skills designed to empower AI coding agents with expert knowledge in Swift, SwiftUI, and the Apple ecosystem. These skills are derived from official Apple resources and Xcode's internal intelligence guidelines, ensuring that your agent acts as a true domain expert.

## Available Skills

### 🚀 Modern Swift Practices (`skills/modern-swift-practices`)
Guidelines for implementing cutting-edge Apple features and design systems.
- **Liquid Glass Design**: Implement Apple's new design language across SwiftUI, UIKit, and AppKit.
- **On-Device Intelligence**: Best practices for integrating local LLMs and visual intelligence.
- **Core Framework Updates**: Modern patterns for Swift Concurrency, SwiftData, and Foundation.

### 📏 Swift Guidelines (`skills/swift-guidelines`)
The definitive coding standards and behavioral protocols derived from Xcode's `IDEIntelligenceChat` engine.
- **Modern Concurrency**: Prioritizes `async`/`await` and Actors over GCD.
- **Swift Testing**: Enforces the new `Testing` framework macros (`@Test`, `#expect`) over XCTest.
- **Platform Correctness**: strict adherence to platform terminology (e.g., macOS, visionOS).
- **SwiftUI Previews**: Best practices for macro-based previews (`#Preview`).

## Concept

Each "skill" is a self-contained package of instructions and resources that transforms a generic AI assistant into a specialized expert. By referencing these skills, the agent gains access to:
- **Specific Capabilities**: Defined tasks the agent can perform.
- **Step-by-Step Instructions**: Protocols for executing tasks correctly.
- **Curated Resources**: Reference documentation, templates, and guidelines.

## Source of Information

The content in this repository is largely extracted from Xcode's internal resources, ensuring alignment with Apple's official tooling and direction.
- **Origin**: `Xcode.app/Contents/PlugIns/IDEIntelligenceChat.framework`

## Structure

```
swift-skills/
├── AGENTS.md               # Guide for AI agents on how to use this repo
├── README.md               # Project overview
├── workflows/              # Agent workflows
└── skills/
    ├── modern-swift-practices/
    │   ├── SKILL.md        # Instructions for modern practices
    │   └── resources/      # Reference markdowns (Liquid Glass, AI, etc.)
    └── swift-guidelines/
        └── SKILL.md        # Instructions for coding standards
```

## Contributing

To add a new skill:
1. Create a new folder in `skills/` (use kebab-case).
2. Add a `SKILL.md` file with the required metadata (name, description, version, license).
3. Populate it with `Capabilities`, `Instructions`, and optional `resources`.
