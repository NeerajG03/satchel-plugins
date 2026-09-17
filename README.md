# Satchel plugins

Install catalog for the Satchel plugin. It gives Claude Code and Codex the address of your Satchel, loads your memory index when a session starts, and teaches the agent how to save and read memories and tasks. No memory or credentials live here. Sign in happens in your browser after install.

## Claude Code

```sh
claude plugin marketplace add NeerajG03/satchel-plugins
claude plugin install satchel@satchel
claude mcp login plugin:satchel:satchel
```

## Codex

```sh
codex plugin marketplace add NeerajG03/satchel-plugins
codex plugin add satchel@satchel
codex mcp login satchel
```

Then allow access on the Satchel page that opens, and start a fresh session. Manage or revoke access at https://satchel-pi.vercel.app/apps.

Generated from the Satchel repository by `scripts/publish-plugins.mjs`. Do not edit here.
