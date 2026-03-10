# hilli/skills

Agent skills for GitHub Copilot CLI and compatible agents.

## Skills

- **[llm-auditor](skills/llm-auditor/SKILL.md)** — Fact-checks LLM responses by extracting verifiable claims, verifying each via web search, producing an audit report with verdicts, and optionally revising inaccurate responses.

## Installation

```bash
npx skills add hilli/skills@llm-auditor
```

Or install globally:

```bash
npx skills add hilli/skills@llm-auditor -g
```

## Usage

Once installed, trigger the auditor in any Copilot CLI session:

- *"audit that"*
- *"fact-check your last response"*
- *"double-check those claims"*
- *"verify that"*

## License

MIT
