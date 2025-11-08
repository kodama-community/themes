# 主题合集

[简体中文](./README.zh-CN.md) | [English](./README.md)

适用于 [Kodama][kodama] 站点的一系列主题.

# 要求

- [Kodama][kodama] v0.3.5 及以上版本.

# 可用主题

| 主题文件 | 主题名 | 风格 | 说明 |
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

# 安装

下载任何主题文件 (如 `serena.html`) 并将其放置在 [Kodama][kodama] 项目的根目录内 (如 `./serena.html` 或者 `./themes/serena.html`, 只要保证与配置时使用的路径一致即可). 

修改 `Kodama.toml` 文件中 `[kodama]` 的 `themes` 字段为所选主题的相对位置, 如: 

```toml
[kodama]
themes = [
  "themes/serena.html", # 注意与存放位置一致
  "themes/fuchsia.html",
]
```

# 贡献此仓库

欢迎任何贡献! 如果你想提交新的主题, 请参考已有的主题文件. 

[kodama]: https://kodama-community.github.io/
[forester]: https://www.forester-notes.org/
[zenwritten]: https://github.com/zenbones-theme/zenbones.nvim
