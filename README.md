# Use Claude Code with ModelAPI

Point Claude Code at ModelAPI without changing your project source code.

## Configure

```bash
export ANTHROPIC_BASE_URL="https://api.aimodelapi.ai"
export ANTHROPIC_API_KEY="sk-ama-YOUR_KEY"
claude
```

`ANTHROPIC_BASE_URL` intentionally has no `/v1` suffix. Claude Code adds the Anthropic Messages API path itself.

## Persist locally

Add the exports to your shell profile or a secure secrets manager. Never commit the key to a repository.

## Verify and troubleshoot

- [Claude Code integration guide](https://aimodelapi.ai/claude-code-api?utm_source=github&utm_medium=repository&utm_campaign=claude_code)
- [Available Claude models](https://aimodelapi.ai/models?utm_source=github&utm_medium=repository&utm_campaign=claude_code)
- [System status](https://aimodelapi.ai/status?utm_source=github&utm_medium=repository&utm_campaign=claude_code)
- [Production onboarding](https://aimodelapi.ai/onboarding?utm_source=github&utm_medium=repository&utm_campaign=claude_code)

Model parity and hosted tools can differ from Anthropic-direct service. Review the current compatibility guide before production use.

