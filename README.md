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

Each plugin lives in its own repository, linked above. This repository only holds the catalog (`.claude-plugin/marketplace.json`).

## License

[MIT](LICENSE)
