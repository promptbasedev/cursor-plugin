<img src="assets/logo.png" alt="PromptBase" width="64" height="64">

# PromptBase for Cursor, Grok Build and Antigravity

Search and use 300,000+ AI prompts and skills from [PromptBase](https://promptbase.com) without leaving Cursor, Grok Build or Google Antigravity. Find prompts for game sprites, website images, video ads, marketing copy and more, then have Cursor's agent fill them in and use them in your project.

## What it adds

- **The PromptBase MCP server** at `https://promptbase.com/mcp`, with tools to:
  - Search prompts and skills
  - View a listing's description, examples and the creator's rating
  - Open prompts you already own and fill in their variables
  - Download free prompts, or use your PromptBase Select downloads (the agent asks first)
  - Check your plan and list your prompts
- **A `find-prompts` skill** that tells Cursor's agent when PromptBase can help and how to use it.

Nothing is ever bought for you. For paid prompts, the agent gives you a link to check out on promptbase.com.

## Install

Install PromptBase from the Cursor Marketplace, or [add the server to Cursor in one click](cursor://anysphere.cursor-deeplink/mcp/install?name=promptbase&config=eyJ1cmwiOiJodHRwczovL3Byb21wdGJhc2UuY29tL21jcCJ9).

In Grok Build, install PromptBase from the xAI plugin marketplace.

In Google Antigravity, run `agy plugin install https://github.com/promptbasedev/cursor-plugin`, then open Agent settings → Customizations and click Authenticate next to PromptBase.

The first time the agent uses PromptBase, you'll sign in to your PromptBase account (or create a free one) and approve the connection. You can disconnect any time in your PromptBase account settings.

## Network and credentials

- **Network:** the plugin only connects to the hosted MCP server at `https://promptbase.com/mcp`. It runs no local code, scripts or hooks.
- **Credentials:** none are stored in this repository. Your agent signs in with OAuth (PKCE) the first time it connects, and PromptBase issues it a token for your account.

## Links

- Setup for Claude, ChatGPT and other agents: https://promptbase.com/agents
- Privacy policy: https://promptbase.com/privacy
- Support: hello@promptbase.com

## License

The files in this repository are MIT licensed. The PromptBase service and its prompts are covered by the [PromptBase terms](https://promptbase.com/tandcs).
