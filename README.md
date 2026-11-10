# Tevyon for Claude Code

Create images and videos with [Tevyon](https://tevyon.ai/en) without leaving your conversation. The plugin connects Claude Code to your Tevyon account: choose a model, see what a job costs in credits before anything starts, and get the finished result back as a link.

## Install

In a Claude Code session:

```
/plugin marketplace add SMCHub/tevyon-claude-plugin
/plugin install tevyon@tevyon
```

The first tool call opens the sign-in for your Tevyon account in the browser. You decide there what the connection may spend per day, and you can disconnect it at any time in Tevyon under "API & MCP".

## What you can ask for

- "Which video models does Tevyon offer, and what does a 5-second clip cost?"
- "Create a launch poster for my sparkling tea brand, portrait format."
- "Turn this idea into a storyboard and then into a short film, scene by scene."
- "Plan three ad creatives from this product photo."
- "Show my latest results and my credit balance."

## Good to know

- You need a Tevyon account. Jobs use the credits of that account; every job shows its price first and is refunded in full if it fails.
- Results are private unless you choose to share them.
- Jobs that show a real person need that person's consent. Content that breaks the [usage policy](https://tevyon.ai/en/usage-policy) is not created.
- This repository holds only the connection settings. Tevyon runs at `https://app.tevyon.ai/api/mcp`.

Using claude.ai, the desktop app or the mobile app instead? See [tevyon.ai/en/claude](https://tevyon.ai/en/claude).

## Support

support@tevyon.ai · [Privacy](https://tevyon.ai/en/privacy) · [Terms](https://tevyon.ai/en/terms)

Claude is a trademark of Anthropic. Tevyon is not affiliated with or endorsed by Anthropic.
