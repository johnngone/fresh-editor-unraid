
# Fresh Editor (Unraid Plugin)
<img width="128" height="128" alt="Fresh editor icon." src="https://raw.githubusercontent.com/johnngone/fresh-editor-unraid/main/plugin/fresh-editor.png" />

An Unraid plugin that installs **Fresh**, a modern, full-featured terminal text editor with familiar keybindings, mouse support, and IDE-level features.

Upstream project: https://github.com/sinelaw/fresh/
Website: https://getfresh.dev/

<img width="512" alt="Fresh editor screenshot." src="https://raw.githubusercontent.com/sinelaw/fresh/refs/heads/master/docs/fresh-demo2.gif" />

## Installation

### Via Community Applications (recommended)
Search for **Fresh Editor** in the Unraid > Apps and click install.

### Via Manual Install
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
- Extracts the `fresh` binary (avoids FUSE overhead)
- Installs it to: `/usr/local/bin/fresh`
- Makes `fresh` available from:
  - Unraid Web Terminal
  - SSH sessions
  - Local console
