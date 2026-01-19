# CLAUDE.MD

## Project Overview

This is the `claudecodeenvtest` repository - a test environment for working with Claude Code.

## Repository Structure

```
claudecodeenvtest/
├── README.md          # Main project README
└── CLAUDE.MD         # This file - Claude Code guidelines
```

## Development Guidelines

- This is me testing git

### Git Workflow

- **Main Branch**: Default branch for stable code
- **Feature Branches**: All development should happen on feature branches
- Branch naming convention: `claude/feature-name-{session-id}`

### Commit Practices

- Write clear, descriptive commit messages
- Focus on the "why" rather than the "what"
- Keep commits focused and atomic

### Code Standards

- Maintain code simplicity and avoid over-engineering
- Only make changes that are directly requested or clearly necessary
- Avoid premature optimization and abstraction
- Remove unused code completely rather than commenting it out

## Working with Claude Code

### Best Practices

1. **Always read before modifying**: Never propose changes to code you haven't read
2. **Ask questions**: Use clarifying questions when requirements are unclear
3. **Plan complex tasks**: Break down large tasks into smaller, manageable steps
4. **Test your changes**: Verify that changes work as expected
5. **Security first**: Be careful to avoid common vulnerabilities (XSS, SQL injection, etc.)

### Common Patterns

- Use dedicated tools for file operations (Read, Edit, Write) instead of bash commands
- Prefer parallel tool calls when operations are independent
- Keep solutions focused on the specific task at hand

## Project Context

This is a test repository designed for exploring Claude Code functionality and workflows.

---

*Last updated: 2026-01-19*
