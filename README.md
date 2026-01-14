# PRD Generator

A Claude Code plugin that generates comprehensive Product Requirements Documents (PRDs) from conversation context.

## Installation

### Option 1: Clone and Enable

```bash
git clone https://github.com/dredozubov/prd-generator ~/.claude/plugins/prd-generator
```

Then enable in Claude Code settings or via `/plugins enable prd-generator`.

### Option 2: Add to Project

Clone into your project directory and reference in your Claude Code settings.

## Commands

### `/create-prd [output_file]`

Generate a comprehensive Product Requirements Document based on the current conversation context.

**Usage:**
```
/create-prd              # Creates PRD.md (default)
/create-prd docs/PRD.md  # Creates PRD at specified path
```

**Generated PRD includes:**
- Executive Summary
- Mission & Core Principles
- Target Users & Personas
- MVP Scope (In/Out of scope)
- User Stories with examples
- Core Architecture & Patterns
- Tools/Features specification
- Technology Stack
- Security & Configuration
- API Specification (if applicable)
- Success Criteria
- Implementation Phases
- Future Considerations
- Risks & Mitigations

## When to Use

- Starting a new project or feature
- Documenting requirements from a planning conversation
- Creating formal specifications from informal discussions
- Onboarding team members with structured documentation

## Author

Denis Redozubov ([@dredozubov](https://github.com/dredozubov))

## License

MIT
