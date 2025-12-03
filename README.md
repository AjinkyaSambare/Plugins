# PRD Writer Plugin for Claude Code

A Claude Code plugin that helps Product Managers create comprehensive Product Requirements Documents (PRDs) with industry best practices.

## Features

- **Slash Command**: `/prd` - Interactive PRD creation with guided prompts
- **Auto-Skill**: Automatically activates when you mention PRD, product specs, or feature documentation
- Comprehensive PRD template with all essential sections
- Best practices from top product teams
- Professional PM frameworks (OKRs, user stories, success metrics)

## Installation

### Add the marketplace

```bash
/marketplace add github:AjinkyaSambare/Plugins
```

### Install the plugin

```bash
/plugin install prd-writer@ajinkya-plugins
```

Or use the interactive installer:

```bash
/plugin
```

Then select "Browse Plugins" and choose `prd-writer`.

## Usage

### Method 1: Slash Command

```bash
/prd
```

Claude will guide you through creating a PRD by asking questions about your product/feature.

### Method 2: Natural Language (Auto-Skill)

Just mention what you need:

- "Help me write a PRD for a new authentication feature"
- "I need to create product requirements for mobile app"
- "Can you help me document this feature spec?"

The skill automatically activates and helps you create a structured PRD.

## PRD Structure

The plugin generates PRDs with these sections:

1. Executive Summary
2. Background & Context
3. Goals & Success Metrics
4. Target Users
5. User Stories & Use Cases
6. Requirements (Functional & Non-Functional)
7. Design & User Experience
8. Technical Considerations
9. Out of Scope
10. Timeline & Milestones
11. Risks & Mitigations
12. Open Questions

## Example Output

The plugin creates professional, markdown-formatted PRDs with:
- Clear section headers
- Bullet points and tables
- Measurable success metrics
- User-focused language
- Technical considerations

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

MIT

## Author

Ajinkya Sambare
