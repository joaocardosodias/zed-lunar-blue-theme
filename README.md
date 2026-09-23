# Lunar Blue for Zed

A quiet graphite-dark theme for Zed with cool lunar highlights and a focused,
low-noise interface. It is the editor companion to
[Lunar Blue for Omarchy](https://github.com/joaocardosodias/omarchy-lunar-blue-theme).

The theme is original and is not affiliated with or endorsed by Zed Industries.

## Palette

| Role | Color |
| --- | --- |
| Background | `#121316` |
| Deep surface | `#0d0d0f` |
| Raised surface | `#212328` |
| Foreground | `#e8edf5` |
| Muted text | `#818b9d` |
| Primary blue | `#1348dc` |
| Soft highlight | `#8ec5ff` |

`#1348dc` drives focused borders, active controls, selections, icons, and the
terminal blue. `#8ec5ff` is reserved for small text and syntax highlights where
the stronger blue would lose readability against graphite surfaces.

## Install for development

Clone the repository, open Zed's Extensions page, select **Install Dev
Extension**, and choose the repository directory.

For a lightweight local install on Linux or macOS, link the theme file directly:

```bash
mkdir -p ~/.config/zed/themes
ln -s "$(pwd)/themes/lunar-blue.json" ~/.config/zed/themes/lunar-blue.json
```

Open the theme selector with `Ctrl+K`, `Ctrl+T` and choose **Lunar Blue**.

## Included

- Complete Zed UI colors for panels, tabs, borders, controls, and scrollbars.
- Syntax colors for code, markup, diffs, links, and predictive edits.
- Integrated terminal colors matching the Omarchy theme.
- Git, diagnostics, collaboration, search, and document highlight states.

## Typography

Lunar Blue is designed around Zed's own font aliases:

- `.ZedSans` / IBM Plex Sans for the interface.
- `.ZedMono` / Lilex for code and the integrated terminal.
