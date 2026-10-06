# Claude Code for Home Assistant

Run [Claude Code](https://docs.anthropic.com/en/docs/claude-code), Anthropic's AI coding assistant, in your Home Assistant sidebar to write automations, debug configuration and query your devices.

- Web terminal in the HA sidebar
- Read-write access to your HA config directory; read-only `/media` and `/share`
- Home Assistant integration through [hass-mcp](https://github.com/voska/hass-mcp)
- No Supervisor, Docker or UART access
- amd64 only

Full documentation is in [DOCS.md](DOCS.md), also shown in the add-on's **Documentation** tab in Home Assistant.

Adapted from [robsonfelix/robsonfelix-hass-addons](https://github.com/robsonfelix/robsonfelix-hass-addons).
