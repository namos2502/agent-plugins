# agent-plugins

AI plugin marketplace by [@namos2502](https://github.com/namos2502).

## Add this marketplace

Run this once inside Claude Code to register the marketplace:

```
/plugin marketplace add namos2502/agent-plugins
```

You only need to do this once. After that, you can install any plugin from this marketplace and get updates with `/plugin marketplace update`.

## Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [CortexLink](https://github.com/namos2502/CortexLink) | Cross-agent workflow plugin — gives your agent the full programmatic reference for every CLI tool you use. One plugin. Every CLI. Stay in flow. | `/plugin install cortexlink@agent-plugins` |

## Install a plugin

```
/plugin install cortexlink@agent-plugins
```

Then run `/reload-plugins` to activate.
