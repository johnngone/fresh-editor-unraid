
# Fresh Editor (Unraid Plugin)
<img width="128" height="128" alt="Fresh editor icon." src="https://raw.githubusercontent.com/johnngone/fresh-editor-unraid/main/plugin/fresh-editor.png" />
<img width="512" alt="Fresh editor screenshot." src="https://getfresh.dev/docs/assets/hero.png" />
An Unraid plugin that installs **Fresh**, a modern terminal text editor you can “just use”.

Fresh is designed to feel immediately familiar while still offering powerful IDE-like features — without modal friction or heavy configuration.

## What is Fresh?

Upstream project: https://github.com/sinelaw/fresh/
Website: https://getfresh.dev/

This plugin simply makes Fresh available **natively on Unraid**.

## Installation

### Via Community Applications (not available yet)
Search for **Fresh Editor** in the Unraid Community Apps store and install like any other plugin.

### Manual Install
From the Unraid Web UI:

**Plugins → Install Plugin**, then paste:
```
https://raw.githubusercontent.com/johnngone/fresh-editor-unraid/main/plugin/fresh-editor.plg
```

### Usage

Open a terminal (Web UI or SSH) and run:

```bash
fresh
```

## What This Plugin Does

- Downloads the official **Fresh AppImage**
- Extracts the `fresh` binary (no FUSE required)
- Installs it to: `/usr/local/bin/fresh`
- Makes `fresh` available from:
  - Unraid Web Terminal
  - SSH sessions
  - Local console
