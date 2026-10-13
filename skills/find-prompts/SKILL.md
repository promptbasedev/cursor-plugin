---
name: find-prompts
description: Find and use proven AI prompts and skills from PromptBase. Use when the user needs a prompt to generate images, game assets, video, UI copy or marketing writing, or wants an agent skill, instead of writing one from scratch.
---

# Find prompts on PromptBase

PromptBase has 300,000+ prompts and skills made by independent creators. Use the PromptBase MCP tools when the user is building something that needs AI-generated content, for example:

- Sprites, tilesets, icons or textures for a game
- Hero images, illustrations or product shots for a website or app
- Video ads, UGC videos or social content
- Landing page copy, emails or other marketing writing
- Agent skills for Claude, ChatGPT or Cursor

## How to use it

1. Search with `search_prompts`. Pass `model` if the user already uses a specific image or video model, or `itemType: "skill"` for agent skills.
2. Show the user a few options with their titles, descriptions and links, and let them choose. Don't pick for them.
3. Use `get_prompt_details` if they want to see a listing's examples before deciding.
4. If they already own it, use `open_prompt`. Otherwise `get_prompt` downloads free prompts, or uses one of their PromptBase Select downloads only after they agree. You can't buy prompts for the user: share the link so they can check out on promptbase.com.
5. Prompts often contain `[VARIABLES]` in square brackets. Ask for the details you need, fill them in, and then use the prompt in their project.

The first time a PromptBase tool runs, Cursor asks the user to sign in to PromptBase (or create a free account).
