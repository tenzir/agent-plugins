# Tenzir Agent Plugins

This repository publishes the Tenzir agent plugin marketplace. Plugin sources
are maintained in [`tenzir/skills`](https://github.com/tenzir/skills) and the
private [`tenzir/dev-skills`](https://github.com/tenzir/dev-skills) repository.

The marketplace is available for both Codex and Claude Code.

## Add the marketplace

Codex:

```bash
codex plugin marketplace add tenzir/agent-plugins
```

Claude Code:

```
/plugin marketplace add tenzir/agent-plugins
```

## Install a plugin

Install the public skills:

```bash
codex plugin add skills@tenzir
```

```
/plugin install skills@tenzir
```

Tenzir employees can also install the private developer skills:

```bash
codex plugin add dev-skills@tenzir
```

```
/plugin install dev-skills@tenzir
```
