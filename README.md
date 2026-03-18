# agent-plugins

A personal Claude Code plugin marketplace by [@namos2502](https://github.com/namos2502).

## Add this marketplace

Run this once inside Claude Code to register the marketplace:

```
/plugin marketplace add namos2502/agent-plugins
```

You only need to do this once. After that, you can install any plugin from this marketplace and get updates with `/plugin marketplace update`.

## Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [CoFluent](https://github.com/namos2502/CoFluent) | Teaches Claude the GitHub Copilot CLI programmatic reference so it can invoke `copilot -p` correctly | `/plugin install cofluent@agent-plugins` |

## Install a plugin

```
/plugin install cofluent@agent-plugins
```

Then run `/reload-plugins` to activate.
