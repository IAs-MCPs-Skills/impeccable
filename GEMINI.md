# Everything Claude Code (ECC) in Gemini CLI

This repository is equipped with the Everything Claude Code (ECC) suite to provide advanced engineering capabilities, specialized agents, and robust workflows.

## 🚀 Getting Started

ECC assets are located in the `.gemini/` directory:
- **Skills**: Specialized guidance and tools in `.gemini/skills/`.
- **Agents**: Expert persona definitions in `.gemini/agents/`.
- **Rules**: Language and domain-specific coding rules in `.gemini/rules/`.

## 🛠 Available Skills

To use a skill, call `activate_skill(name="skill-name")`. Some key skills included:
- `tdd-workflow`: Enforces test-driven development with 80%+ coverage.
- `verification-loop`: Automated quality and security checks.
- `security-review`: Comprehensive security audits for your code.
- `deep-research`: Advanced multi-source research with cited reports.
- `frontend-patterns`: Expert patterns for React, Next.js, and modern UI.

*List all skills in `.gemini/skills/` to explore the full catalog.*

## 🤖 Expert Agents

You can invoke specialized expert agents to help with specific tasks using `invoke_agent(agent_name="...", prompt="...")`.

Available agents include:
- `a11y-architect`: Accessibility and WCAG 2.2 compliance expert.
- `architect`: System design and scalability specialist.
- `code-reviewer`: Deep logic and security code reviewer.
- `performance-optimizer`: Specialist in identifying and fixing bottlenecks.
- `security-reviewer`: Vulnerability detection and remediation expert.

*For a full list, see `.gemini/agents/`.*

## 📏 Coding Rules

The rules in `.gemini/rules/` are applied to maintain high standards:
- **Common**: Base principles for style, git, and security.
- **TypeScript/JavaScript**: Specific patterns for the JS ecosystem.
- **Web**: UI/UX and design system rules.

## 🔄 ECC Workflow

1. **Research First**: Use `deep-research` or `exa-search` before implementing complex features.
2. **Test-First**: Use `tdd-workflow` for all bug fixes and new modules.
3. **Verify**: Run the `verification-loop` before finalizing any significant change.
4. **Compact**: Use `strategic-compact` to manage context efficiently during long sessions.

## ⚠️ Repository Specifics

- **Impeccable Skill**: The core skill for this repo is in `.gemini/skills/impeccable/`.
- **Source of Truth**: `source/` contains the source for all generated artifacts.
- **Build**: Always run `bun run build` after modifying source files.
