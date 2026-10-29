# Job Application Agent

Browser-assisted job application workflow for Indeed, Naukri, LinkedIn, and
other portals. The repository holds the candidate profile, run settings,
application history, and agent rules. Browser control is provided by Playwright
MCP.

## Install on a new computer

Install [Node.js 20 or newer](https://nodejs.org/), then run from this folder:

```powershell
npm.cmd install
```

Use `npm install` on macOS or Linux. The first install does two things:

1. Installs the pinned `@playwright/mcp` package.
2. Downloads the matching Chromium browser required by Playwright MCP.

On Windows, the browser is stored in `%LOCALAPPDATA%\ms-playwright`. It is a
Playwright-managed browser, separate from your normal Chrome installation. Do
not run `npm init playwright@latest`; it generates a separate test project and
is not needed here.

## Configure your agent

This repository intentionally has one MCP configuration template:

```text
.mcp.json
```

Copy the complete contents of that file into the MCP configuration location for
the agent you use. Merge its `playwright` entry with any existing `mcpServers`
entries; do not replace your other servers.

For Antigravity IDE, open or create:

```text
~/.gemini/config/mcp_config.json
```

Paste the `playwright` entry from `.mcp.json` into its `mcpServers` object, save,
then restart Antigravity or refresh MCP servers from `/mcp`.

The same `.mcp.json` entry can be copied into Cursor, Codex, Claude, VS Code, or
another agent's own MCP configuration file. Each client has a different file
location, so this repository does not try to configure them automatically.

## Project files

```text
.mcp.json                The one portable Playwright MCP server template
AGENTS.md                Agent entry point
AGENT_INSTRUCTIONS.md    Complete job-application operating procedure
RUN_CONFIG.md            Settings for the next run
applications.md          Application history and duplicate protection
docs/RULEBOOK.md         Candidate details, fit rules, and standard answers
docs/Resume_Aman_Mishra.pdf
```

Before the first run, verify the personal details in `docs/RULEBOOK.md`, confirm
the resume path in `RUN_CONFIG.md`, and choose a small
`max_jobs_to_process` value.

## Start a job-application run

Open the repository in your agent after configuring the MCP server and say:

> Follow `AGENTS.md` and start the configured job-application run. Use the
> Playwright MCP browser. Pause when manual login or an unanswered sensitive
> question is required.

The agent must read `AGENT_INSTRUCTIONS.md`, `RUN_CONFIG.md`,
`docs/RULEBOOK.md`, and `applications.md` before browsing. You sign in manually;
credentials must never be placed in the repository or chat.

## Update or repair the installation

Run the same command again:

```powershell
npm.cmd install
```

It verifies the package installation and ensures the matching Chromium browser is
available.
