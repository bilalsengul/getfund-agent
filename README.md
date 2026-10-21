# getfund agent (spike)

Plugin for Claude Code and Codex: the getfund MCP server (sign in with your getfund account) plus a browser
tool (Playwright MCP) and the getfund skill. Spike build: the MCP URL points at preprod.

Claude Code (2.1.292+):

```sh
claude plugin install getfund --marketplace GlossGo/getfund-agent
```

Codex:

```sh
codex plugin marketplace add GlossGo/getfund-agent && codex plugin add getfund@getfund
```

Then say `getfund` in a new session and sign in when your client asks.
