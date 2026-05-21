# First Good First Issue — Template

## Issue Title

**Add English translations and docstrings to the agent identity configuration files**

[good first issue] [difficulty: easy] [estimated: <1h]

---

## Description

Our repository contains configuration files for nine AI agents (Shuyu, Zeus, Nova, Tristan, Ethan, Momo, Baron, Luna, Stella). Currently, most comments and documentation within these config files are written in Chinese with minimal English translation. This makes it harder for non-Chinese-speaking developers to understand and contribute to the agent setup.

## Goal

Add English comments and docstrings to the agent identity configuration files so that international developers can easily understand the agent architecture.

## What To Do

1. Navigate to the `/config/agents/` directory
2. For each agent config file:
   - Translate top-level comments to English (keep original Chinese, add English below)
   - Add Python-style docstrings (or JSON `description` fields) explaining each agent's role
   - Ensure configuration field names remain unchanged

### Example

```json
// Before (Chinese only)
{
  "name": "Luna",
  "role": "社群运营官"  // 负责全球开发者社区运营
}

// After (Chinese preserved + English added)
{
  "name": "Luna",
  "role": "社群运营官",  // 负责全球开发者社区运营
  // Community Operations Officer — manages global developer ecosystem
  "description": "Global developer community operations. Responsible for SDK docs, builder onboarding, community growth."
}
```

## Acceptance Criteria

- [ ] All 9 agent config files updated
- [ ] Original Chinese comments preserved
- [ ] English translations added below each Chinese comment
- [ ] A `description` field added to each agent object
- [ ] PR references this issue

## Resources

- See [CONTRIBUTING.md](CONTRIBUTING.md) for PR workflow
- Questions? Ask in Discord `#🏗️-integration-help`

## Labels

`good first issue`, `docs`, `difficulty: easy`, `estimated: <1h`
