# cosmic-plugins

A [Claude Code](https://code.claude.com) plugin marketplace by [Giuseppe Bellamacina](https://github.com/GiuseppeBellamacina).

## Add the marketplace

```text
/plugin marketplace add GiuseppeBellamacina/cosmic-plugins
```

Where `/plugin` isn't available (e.g. the VS Code extension), use the CLI in a terminal:

```bash
claude plugin marketplace add GiuseppeBellamacina/cosmic-plugins
```

## Plugins

| Plugin | What it does | Install |
| --- | --- | --- |
| [**setup-sync**](https://github.com/GiuseppeBellamacina/claude-code-sync) | Move your whole Claude Code setup (settings, plugins, MCP servers, skills, agents, hooks, LSP servers, mods) to a new machine with `/setup-sync:push` and `/setup-sync:pull`. Handles existing setups with overwrite / replace / ask modes, verifies the result and writes a checklist report. | `/plugin install setup-sync@cosmic-plugins` |
| [**pr-review-helper**](https://github.com/GiuseppeBellamacina/pr-review-helper) | Find open GitHub pull requests nobody has reviewed yet with `/pr-review-helper:find` (by repo, user or topic such as LLMs or security, sorted by popularity or date), then review one with `/pr-review-helper:review`: a focused draft you confirm or edit before it is posted with `gh` under your own account. | `/plugin install pr-review-helper@cosmic-plugins` |
| [**prompt-queue**](https://github.com/GiuseppeBellamacina/prompt-queue) | Type `>> on` (or `>> <message>`): what you send while Claude works waits until the current task is finished, in a queue above the prompt where you reorder, cancel or clear messages. `>> off` is back to normal, and `>>` lines never reach Claude's history. `/now <message>` interrupts and sends at once. | `/plugin install prompt-queue@cosmic-plugins` |

Each plugin lives in its own repository, linked above. This repository only holds the catalog (`.claude-plugin/marketplace.json`).

## License

[MIT](LICENSE)
