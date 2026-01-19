
# Fresh Editor (Unraid Plugin)
<img width="128" height="128" alt="Fresh editor icon." src="https://raw.githubusercontent.com/johnngone/fresh-editor-unraid/main/plugin/fresh-editor.png" />

An Unraid plugin that installs **Fresh**, a modern terminal text editor that “just works”. Fresh is designed to feel immediately familiar while still offering powerful IDE-like features out-the-box.

Upstream project: https://github.com/sinelaw/fresh/
Website: https://getfresh.dev/

<img width="512" alt="Fresh editor screenshot." src="https://getfresh.dev/docs/assets/hero.png" />

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

- Workflows checks for Fresh releases daily
- If new version, downloads the Fresh AppImage
- Extracts the `fresh` binary (no FUSE required)
- Installs it to: `/usr/local/bin/fresh`
- Makes `fresh` available from:
  - Unraid Web Terminal
  - SSH sessions
  - Local console
