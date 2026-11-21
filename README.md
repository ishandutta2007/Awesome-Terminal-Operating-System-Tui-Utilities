# Awesome-Terminal-Operating-System-Tui-Utilities

# Top Terminal Operating System & TUI Utilities Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Terminal Window Managers, Multiplexers, GPU-Accelerated Terminal Emulators & TUI Application Frameworks*  
**Last updated: November 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Terminal Operating System & TUI Utilities**. These tools transform the command line into a full-featured workspace through modal terminal window management, persistent sessions, agent-aware pane orchestration, GPU-accelerated rendering, and declarative TUI frameworks.

**Examples** include Termius, Warp, Charm Cloud, Textualize, WezTerm, Alacritty, Tabby, Hyper, Tilix, and Guake (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for terminal window managers, multiplexers, cross-platform terminal emulators, and Python/Go/Rust TUI frameworks — ideal for developers, DevOps engineers, sysadmins, and terminal-first power users.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Warp](https://warp.dev)**  
  Modern, Rust-based terminal with integrated AI agent workflows, block-based command output, collaborative Warp Drive notebooks, and team workspace sync.

- **[Termius](https://termius.com)**  
  Cross-platform SSH, Mosh, and SFTP client featuring end-to-end encrypted vault sync, snippet sharing, and team session management across desktop and mobile.

- **[Charm Cloud (`charmbracelet/charm`)](https://charm.sh)**  
  Cloud-backed identity, encrypted key-value storage, and filesystem sync infrastructure designed to power Charm CLI and TUI applications.

- **[Textualize / Textual Web](https://www.textualize.io/)**  
  Platform and tooling ecosystem enabling Python Textual TUI applications to be served and shared effortlessly in web browsers alongside local terminals.

- **[Fig / Amazon Q Developer CLI](https://amazon.com)**  
  Cloud-connected terminal productivity layer adding IDE-style autocomplete, inline AI assistance, and shared team CLI workflows.

- **[Tabby Sync / Cloud Plugins](https://tabby.sh)**  
  Cloud configuration and profile synchronization services for the Tabby terminal emulator across multiple workstations.


## Open-Source GitHub Projects

- **[TUIOS (`Gaurav-Gosain/tuios`)](https://github.com/Gaurav-Gosain/tuios)**  
  Terminal UI Operating System and window manager built in Go on the Charm stack, featuring Vim-like modal controls, BSP tiling, workspaces, persistent daemon sessions, Kitty graphics passthrough, and a unified coding agent Inbox.

- **[Textual (`Textualize/textual`)](https://github.com/Textualize/textual)**  
  Lean, reactive Python application framework with CSS-like styling and an async event loop for building rich user interfaces that run in both terminals and web browsers.

- **[Bubble Tea (`charmbracelet/bubbletea`)](https://github.com)**  
  Powerful, functional Go TUI framework based on The Elm Architecture, paired with Lip Gloss styling and Bubbles components for interactive terminal apps.

- **[Ratatui (`ratatui/ratatui`)](https://github.com)**  
  High-performance Rust library for cooking up rich, lightweight terminal user interfaces with immediate-mode rendering and extensive widget ecosystems.

- **[WezTerm (`wez/wezterm`)](https://github.com)**  
  GPU-accelerated cross-platform terminal emulator and multiplexer written in Rust with Lua configuration, built-in multiplexing, and ligature support.

- **[Alacritty (`alacritty/alacritty`)](https://github.com)**  
  Fast, cross-platform, OpenGL-accelerated terminal emulator written in Rust focused on simplicity, minimal latency, and high frame-rate rendering.

- **[Ghostty (`ghostty-org/ghostty`)](https://github.com)**  
  Fast, feature-rich, cross-platform terminal emulator written in Zig using platform-native UI toolkits, GPU acceleration, and full Kitty graphics protocol support.

- **[Kitty (`kovidgoyal/kitty`)](https://github.com)**  
  Cross-platform, fast, GPU-based terminal emulator supporting programmable kittens, splits, tabs, ligatures, and the standard Kitty graphics protocol.

- **[Tabby (`Eugeny/tabby`)](https://github.com)**  
  Highly configurable, extensible cross-platform terminal emulator, SSH client, and serial console built with modern web technologies and plugin support.

- **[Hyper (`vercel/hyper`)](https://github.com)**  
  Extensible terminal emulator built on HTML, CSS, and JavaScript/Electron with a massive ecosystem of community themes and plugins.

- **[Tilix (`gnunn1/tilix`)](https://github.com)**  
  Tiling terminal emulator for Linux built with GTK3 following the GNOME Human Interface Guidelines, supporting split panes, quake mode, and persistent layouts.

- **[Guake (`Guake/guake`)](https://github.com)**  
  Top-down drop-down terminal emulator for GNOME inspired by classic quake consoles, featuring instant hotkey toggling, multi-tab support, and split panes.

- **[tmux (`tmux/tmux`)](https://github.com)**  
  Ubiquitous terminal multiplexer enabling persistent background sessions, detachable windows, split panes, and scriptable layouts over SSH.

- **[Zellij (`zellij-org/zellij`)](https://github.com)**  
  Modern terminal workspace and multiplexer written in Rust featuring floating panes, WebAssembly plugins, declarative layouts, and discoverable keybinding bars.

- **[Byobu (`dustinkirkland/byobu`)](https://github.com)**  
  Enhancement profile and keybinding wrapper for `tmux` and GNU Screen adding hardware status notifications, toggleable system metrics, and intuitive function-key controls.

- **[Rich & Rich-CLI (`Textualize/rich` & `Textualize/rich-cli`)](https://github.com/Textualize/rich)**  
  Python library and command-line toolbox for rendering syntax-highlighted code, Markdown, tables, progress bars, and tracebacks directly in the terminal.

- **[Trogon (`Textualize/trogon`)](https://github.com/Textualize/trogon)**  
  Utility by Textualize that inspects Python Click or Typer CLIs and auto-generates an interactive Textual TUI form to configure and run commands.

- **[Gum (`charmbracelet/gum`)](https://github.com)**  
  Glamorous shell script helper built on Lip Gloss and Bubbles that adds interactive prompts, fuzzy filters, spinners, and styled headers to Bash/Zsh scripts.

- **[VHS (`charmbracelet/vhs`)](https://github.com)**  
  CLI home video recorder that turns declarative `.tape` files into reproducible GIFs and MP4 demos of terminal applications and TUI workflows.

### Additional Strong Open-Source Options

- **[Terminal File Managers (TUIs)](https://github.com)** like **Yazi (`sxyazi/yazi`)**, **Superfile (`yorukot/superfile`)**, **Ranger**, **lf**, and **nnn** for blazing-fast terminal file navigation with image previews.
- **[Terminal Git & DevOps TUIs](https://github.com)** including **Lazygit**, **GitUI**, **jujutsu / jjui**, **Posting (API client)**, and **atac** for keyboard-driven engineering workflows.
- **[Cross-Platform Shells & Prompts](https://github.com)** such as **Nushell**, **Fish**, **Starship**, **Oh My Posh**, and **Atuin** for structured shell pipelines and synced shell history.
- **[Web-Based Terminal Emulators](https://github.com)** like **ttyd (`tsl0922/ttyd`)**, **GoTTY**, and **xterm.js** for sharing local terminal sessions and TUIs securely over HTTP/WebSockets.
- Many community **Nerd Fonts**, **Catppuccin / Tokyo Night Terminal Themes**, and **Kitty/Sixel Image Viewers** (`chafa`, `viu`, `timg`).

**Frameworks for building custom systems**: Combine **TUIOS** (`Gaurav-Gosain/tuios`) or **Zellij** for modal workspace tiling, **Ghostty** or **WezTerm** for GPU-accelerated rendering, and **Textual**, **Bubble Tea**, or **Ratatui** for building custom terminal applications.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Terminal multiplexers and persistent daemon tools (`tuios`, `tmux`, `zellij`) keep background PTY sessions alive; ensure proper socket permissions and SSH key agent forwarding hygiene on shared servers.
- Self-hosted web terminals (`ttyd`, Textual Web) should always be placed behind strong authentication and TLS encryption when exposed over a network.

---

**Made for terminal power users, CLI developers, systems engineers, and open-source builders.**  
Let's make the terminal workspace faster, smarter, and more open.
