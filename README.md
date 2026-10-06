# Cairn for Claude Code

Cairn is a chief-of-staff workspace for macOS. This plugin connects Claude Code
to the Cairn installed on your Mac: its MCP tools (`cairn mcp`) and a skill
holding the guide to working with Cairn (`cairn guide`). Both come from the app
in `/Applications/Cairn.app`, so they always match the version you run; this
repository holds only the wiring.

## Installing it

From Cairn: Settings → Tools → In your Claude apps, **Turn on** beside Claude
Code. Or by hand:

```bash
claude plugin marketplace add benorfaz/cairn-plugin
claude plugin install cairn@cairn
```

Without Cairn in `/Applications`, the tools do not start and the skill says to
install it.

This repository is published from Cairn's own at each release: changes made
here are overwritten.
