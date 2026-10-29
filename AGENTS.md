# Agent Entry Point

This file is the auto-discovered entry point. The complete operating procedure
is in `AGENT_INSTRUCTIONS.md`.

Before taking any job-search or application action:

1. Read `AGENT_INSTRUCTIONS.md`, `RUN_CONFIG.md`, `docs/RULEBOOK.md`, and
   `applications.md` in full.
2. Confirm that a Playwright **MCP** browser tool is available. Playwright Test
   alone is not a substitute for MCP browser tools.
3. If the MCP tool is unavailable, do not run `npm init playwright`. Tell the
   user to copy the server entry from `.mcp.json` into that agent client's MCP
   configuration, then restart or refresh the client.
4. Use a visible browser and let the user complete login. Never request, store,
   or enter their password.
5. Follow `AGENT_INSTRUCTIONS.md` exactly, including duplicate checks,
   submission boundaries, immediate logging, and pause conditions.

If dependencies are absent, run `npm install` (`npm.cmd install` in Windows
PowerShell when script execution is restricted). This installs Playwright MCP and
its Chromium browser.
