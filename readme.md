# Feet SourceMod Plugin

A SourceMod plugin for Counter-Strike: Source bhop and KZ servers. Draws a wireframe rectangle at your feet using beam effects, helping you visualize your player hull's ground position.

## Commands

- `sm_feet` — Cycle through display modes:
  - **Disabled** (default)
  - **Enabled (standing/crouching)** — visible whenever you are on the ground
  - **Enabled (standing only)** — visible only when standing on the ground
  - **Enabled (crouching only)** — visible only when crouching on the ground
  - **Always enabled** — visible at all times, including in the air

Your selected mode is saved per-client via cookies and persists across sessions.
