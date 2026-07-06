<div align="center">

# Hi, I'm Jex Hsu

**Automation Systems / Data Collection / Web Reverse Engineering / Developer Tooling**

把重复、脆弱、靠手工维持的流程，做成可以长期运行、可以恢复、可以迁移的工具。

</div>

## About Me

我是 Jex Hsu，一名关注自动化系统、数据采集、Web 逆向和开发效率工具的开发者。我的项目大多从真实工作流出发：把网页数据采集、浏览器网络捕获、关键词拓展、多账号浏览器自动化、参数签名分析、JavaScript 反混淆、桌面 GUI 和环境恢复这些零散环节，整理成可复用、可观测、可维护的工具。

I build practical tools for automation-heavy workflows: crawlers with a clear raw-to-parsed data flow, Chrome DevTools Protocol utilities for network capture, keyword expansion tools backed by search suggestions and proxy rotation, browser automation apps with GUI packaging, and reverse-engineering experiments around signatures, APIs, and JavaScript behavior. I care about the whole path from requirement analysis and architecture to CLI/GUI implementation, session handling, async tasks, packaging, deployment, and machine recovery.

## Current Focus

- Turning one-off browser workflows into repeatable automation systems with state, retries, session handling, and result persistence.
- Building data collection pipelines that separate crawling, raw storage, parsing, cleanup, and downstream use.
- Studying web reverse engineering patterns around request signatures, anti-bot flows, parameter generation, and JavaScript deobfuscation.
- Maintaining a recoverable macOS/Linux development environment with shell, terminal, editor, tmux, Git, and package manifests.

## Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=000)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

### Frontend & Runtime

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Automation, Reverse Engineering & Tooling

![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![PyQt](https://img.shields.io/badge/PyQt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=000)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)

## What I Build

- **Crawlers and aggregators** that collect from multiple sources, preserve raw data, and parse it into cleaner text for later processing.
- **Browser and network tooling** around Chrome DevTools Protocol, HAR generation, remote debugging, and request/response inspection.
- **Keyword and content automation** with recursive search suggestions, proxy/Tor support, streaming output, and long-running task controls.
- **Desktop automation apps** with PyQt interfaces, browser cookie capture, background renewal, licensing, packaging, and operator-friendly result handling.
- **Reverse engineering labs** for signatures, encrypted parameters, anti-bot scripts, API clients, and JavaScript deobfuscation.
- **Personal infrastructure** for restoring development machines across macOS and Linux without rebuilding everything by hand.

## Featured Projects

| Project | Stack | Focus |
| --- | --- | --- |
| [bioscraper](https://github.com/jexhsu/bioscraper) | Python | Biosecurity news crawler and aggregator with source-specific crawlers, parsers, and a raw-data-to-clean-text pipeline. |
| [cdp_capture](https://github.com/jexhsu/cdp_capture) | Python / CDP | Chrome DevTools Protocol network capture tool with live request monitoring, HAR export, format repair, local/remote connection modes, and reusable config. |
| google-sites-tool | Python / PyQt / DrissionPage | Private desktop automation tool for batch Google Sites creation, multi-account scheduling, cookie capture/renewal, streaming result output, and RSA license checks. |
| keyword-collector | Python / PyQt / Tor | Private keyword expansion tool using search suggestion APIs, recursive long-tail discovery, per-keyword TXT output, Tor proxy support, and live runtime statistics. |
| [mashangpa](https://github.com/jexhsu/mashangpa) | Python / JavaScript | Problem clients and solutions covering custom parameter generation, API handling, cryptographic helpers, and JavaScript deobfuscation. |
| [akamai](https://github.com/jexhsu/akamai) / [NetEase-YiDun](https://github.com/jexhsu/NetEase-YiDun) | JavaScript | Reverse engineering experiments around browser-side anti-bot and sensor-style JavaScript flows. |
| dotfiles | Shell / Lua / Vim Script | Private macOS/Linux workstation recovery setup for zsh, tmux persistence, Git defaults, Vim/Neovim, Ghostty, package manifests, and GNOME restore helpers. |

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jexhsu/JexHsu/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jexhsu/JexHsu/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/jexhsu/JexHsu/output/github-snake.svg" alt="GitHub contribution snake animation" />
</picture>

</div>
