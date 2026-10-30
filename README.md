# getfund agent

Plugin for Claude Code and Codex: the getfund MCP server (sign in with your getfund account), a browser tool
(Playwright MCP in your installed Google Chrome, so you can sign in to a portal or pass a captcha yourself) and
the getfund skill. Version 2.2.1, server `https://getfund.space/mcp`.

Claude Code (2.1.292 or newer):

```sh
claude plugin install getfund --marketplace bilalsengul/getfund-agent
```

Then sign in: run `/mcp`, pick getfund (listed as `plugin:getfund:getfund`) and choose Authenticate.

Codex:

```sh
codex plugin marketplace add bilalsengul/getfund-agent && codex plugin add getfund@getfund
```

Then sign in: `codex mcp login getfund`.

Start a new session and say `getfund`: the skill completes your setup, fills the program's form in Chrome and
asks before it submits. The browser tool needs Node.js (`npx`) and Google Chrome.

Help: https://getfund.space/en/help/ · Privacy: https://getfund.space/en/legal/privacy/ · Terms: https://getfund.space/en/legal/terms/

This repository is generated; a change made here is overwritten by the next publish.
