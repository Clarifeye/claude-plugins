# Clarifeye plugin for Claude Code

Connect Claude Code to your Clarifeye knowledge store.

## What's inside

- **`clarifeye` MCP server** — your Clarifeye instance, with sign-in handled by Claude Code.
- **`clarifeye` skill** — how Claude works with your knowledge store. Invoke it with
  `/clarifeye:clarifeye`, or just ask a question and Claude loads it on its own.

## Install

1. Add the Clarifeye marketplace once:

   ```
   /plugin marketplace add Clarifeye/claude-plugins
   ```

2. Install the plugin:

   ```
   /plugin install clarifeye@clarifeye
   ```

3. When prompted for **Clarifeye MCP URL**, paste the MCP URL shown on your
   organization's **Deploy Settings** page in Clarifeye.

4. On first use, Claude Code opens your browser to sign in to Clarifeye. You can also
   sign in up front from `/mcp`.

## Try it

```
/clarifeye:clarifeye which knowledge stores can I access?
```

## Update

Run `/plugin marketplace update clarifeye` then `/plugin update clarifeye@clarifeye`, or
enable auto-update for the `clarifeye` marketplace under `/plugin` → **Marketplaces**.

## License

The files in this repository (plugin manifest, MCP configuration and skill) are released
under the [Apache License 2.0](LICENSE). Access to the Clarifeye platform itself is not
covered by this license and remains governed by your agreement with Clarifeye.
