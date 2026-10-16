# Nara

A cool dark color theme for VS Code and Cursor. Pond-stone blue-grey, sea-foam teal, and lantern gold.

## Install

From this folder:

1. Copy this folder into your editor extensions directory, then reload:
   - Cursor: `~/.cursor/extensions/nara-theme`
   - VS Code: `~/.vscode/extensions/nara-theme`
2. Open the Command Palette → **Preferences: Color Theme** → choose **Nara** or **Nara High Contrast**.

To try it without installing, open this folder in Cursor/VS Code and press F5 (Extension Development Host).

## Tweak

Edit `themes/nara-color-theme.json` or `themes/nara-high-contrast-color-theme.json`:

- `colors` — workbench UI (sidebar, tabs, status bar, terminal)
- `tokenColors` — TextMate syntax scopes
- `semanticTokenColors` — semantic highlighting

Reload the window after changes if the theme is already installed.

## Palette

| Role | Hex |
| --- | --- |
| Background | `#203338` |
| Elevated surface | `#2B3D41` |
| Foreground | `#D7E0DE` |
| Comment | `#48717B` |
| Accent / teal | `#8EC9B8` |
| Keyword / cyan | `#8DDFEF` |
| Storage / purple | `#B49BED` |
| Function / blue | `#72B1F2` |
| Type / gold | `#FFC681` |
| String / moss | `#D9E18B` |
| Number / coral | `#F18D88` |
| Property / rose | `#E47794` |

## Nara High Contrast

Same roles, darker ground, brighter neon tokens.

| Role | Hex |
| --- | --- |
| Background | `#13292E` |
| Elevated surface | `#1D3135` |
| Foreground | `#E0EAE8` |
| Comment | `#6D9FAC` |
| Accent / teal | `#75DAC0` |
| Keyword / cyan | `#3DDCF7` |
| Storage / purple | `#BFA1FF` |
| Function / blue | `#77BBFF` |
| Type / gold | `#FFB85B` |
| String / moss | `#D1DA3B` |
| Number / coral | `#FF938E` |
| Property / rose | `#FF709A` |
