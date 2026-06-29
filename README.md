# Cross Platform Terminal (CPT)

A keyboard-driven terminal workspace for Linux and Windows. Organize multiple terminal sessions and file browsers into tabbed views with flexible docking layouts — all without touching the mouse.

## Installation

### Linux

1. Download the latest `cpt-<version>-linux-x86_64.tar.gz` (or `.AppImage`) from the [Releases](../../releases) page.
2. **tar.gz** — extract and run:
   ```sh
   tar -xzf cpt-<version>-linux-x86_64.tar.gz
   ./cpt
   ```
   **AppImage** — make executable and run directly:
   ```sh
   chmod +x cpt-<version>-linux-x86_64.AppImage
   ./cpt-<version>-linux-x86_64.AppImage
   ```

No installation required. The binary is self-contained.

**Configuration** is stored in `~/.config/cpt/`.

### Windows

1. Download `cpt-<version>-windows-x86_64.zip` from the [Releases](../../releases) page.
2. Extract the zip.
3. Run `cpt.exe`.

**Configuration** is stored in `%APPDATA%\cpt\`.

## Features

- **Views** — tabbed workspaces, each with an independent docking layout
- **Terminals** — full PTY terminals with tabs, splits, and zoom
- **File Browser** — lightweight panel for navigating the filesystem
- **Workflows** — named sequences of steps (prepend text, run scripts) that inject into a terminal
- **Keyboard shortcuts** — fully rebindable; all defaults listed in [docs/keyboard-shortcuts.md](docs/keyboard-shortcuts.md)

## Documentation

| Guide | Description |
|-------|-------------|
| [Getting Started](docs/getting-started.md) | First launch, core concepts, basic workflow |
| [Keyboard Shortcuts](docs/keyboard-shortcuts.md) | Full reference of all default key bindings |
| [Customization](docs/customization.md) | Rebinding shortcuts, config file locations |

## Updating

Open **Settings → About** and click **Check for Update**. If a newer version is available, click **Download & Install** — the app will replace itself in place and prompt you to restart.

No manual download or installer needed. The update runs in the background and does not interrupt your session.

## Reporting Issues

Bug reports and feature requests go to the [Issues](../../issues) page. Please include:
- Cross Platform Terminal (CPT) version (shown in the title bar or **Settings → About**)
- What you did, what you expected, what happened
- Any relevant terminal output
