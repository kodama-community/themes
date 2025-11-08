# Themes

[简体中文](./README.zh-CN.md) | [English](./README.md)

Themes for [Kodama](https://kodama-community.github.io/). 

# Requirements

- [Kodama](https://kodama-community.github.io/) v0.3.5 or later.

# Available Themes

| Theme File | Theme Name | Style | Description |
| - | - | - | - |
| `forester.html` | `forester` | Light | Inspired by [Forester](https://www.forester-notes.org/) |
| `kodama.html` | `kodama` | Dark | Dark version of `forester` |
| `default.html` | `default` | System | Default theme, `forester` + `kodama` |
| `fuchsia.html` | `fuchsia` | Light | |
| `serena.html` | `serena` | Dark | |
| `zenwritten.html` | `zen light` | Light | Inspired by [Zenwritten][zenwritten] |
| `zenwritten.html` | `zen dark` | Dark | Inspired by [Zenwritten][zenwritten] |
| `zenwritten.html` | `zen` | System | Inspired by [Zenwritten][zenwritten] |
| `moon.html` | `朔望` | System | Inspired by Pink Floyd - The Dark Side of the Moon |
| `moon.html` | `望月` | Light | Inspired by Pink Floyd - The Dark Side of the Moon |
| `moon.html` | `朔月` | Dark | Inspired by Pink Floyd - The Dark Side of the Moon |

# Installation

Download any theme file (e.g. `serena.html`) and place it in the root directory of your [Kodama](https://kodama-community.github.io/) project (e.g. `./serena.html` or `./themes/serena.html`, just make sure it matches the path used in the configuration).

Modify the `themes` field under `[kodama]` in the `Kodama.toml` file to the relative path of the selected theme, e.g.:

```toml
[kodama]
themes = [
  "themes/serena.html", # Make sure it matches the storage location
  "themes/fuchsia.html",
]
```

# Contribution

Any contributions are welcome! If you want to submit a new theme, please refer to the existing theme files.

[kodama]: https://kodama-community.github.io/
[forester]: https://www.forester-notes.org/
[zenwritten]: https://github.com/zenbones-theme/zenbones.nvim
