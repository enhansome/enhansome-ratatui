<!--lint disable awesome-git-repo-age-->

# Awesome Ratatui with stars

[<img src="https://github.com/ratatui.png" align="right" width="100">](https://ratatui.rs)

Here you will find a list of TUI crates and applications that are made for or using [`ratatui`](https://crates.io/crates/ratatui) and [`tui`](https://crates.io/crates/tui).

<!--lint disable awesome-toc-->

## Contents

* [📦 Libraries](#-libraries)
  * [🏗️ Frameworks](#%EF%B8%8F-frameworks)
  * [🧩 Widgets](#-widgets)
  * [🔧 Utilities](#-utilities)
  * [🔗 Bindings](#-bindings)
* [💻 Apps](#-apps)
  * [⌨️ Development Tools](#%EF%B8%8F-development-tools)
    * [Source Control and Collaboration](#source-control-and-collaboration)
    * [Code Search, Editing, and Review](#code-search-editing-and-review)
    * [APIs, Databases, Build, and Debugging](#apis-databases-build-and-debugging)
  * [🤖 AI and Agents](#-ai-and-agents)
  * [📁 Files, Data, and Documents](#-files-data-and-documents)
  * [🧰 Terminal Workflow](#-terminal-workflow)
  * [🌐 Networking and Internet](#-networking-and-internet)
    * [Network Operations and Infrastructure](#network-operations-and-infrastructure)
    * [Remote Access, APIs, and File Transfer](#remote-access-apis-and-file-transfer)
    * [Communications and Social](#communications-and-social)
  * [👨‍💻 System Administration](#-system-administration)
    * [Monitoring, Diagnostics, and Logs](#monitoring-diagnostics-and-logs)
    * [Containers and Orchestration](#containers-and-orchestration)
    * [OS, Storage, and Package Management](#os-storage-and-package-management)
    * [Batch, Database, and Cluster Operations](#batch-database-and-cluster-operations)
  * [🔌 Hardware and Embedded](#-hardware-and-embedded)
  * [🔐 Security and Identity](#-security-and-identity)
  * [📝 Productivity and Planning](#-productivity-and-planning)
    * [Tasks, Projects, and Calendars](#tasks-projects-and-calendars)
    * [Notes and Journaling](#notes-and-journaling)
    * [Finance and Markets](#finance-and-markets)
    * [Focus, Habits, and Time](#focus-habits-and-time)
  * [📚 Reading and Learning](#-reading-and-learning)
  * [🎵 Music and Media](#-music-and-media)
    * [Music and Audio](#music-and-audio)
    * [Books, Video, and Creative Media](#books-video-and-creative-media)
  * [🎮 Games and Entertainment](#-games-and-entertainment)
  * [🔬 Science, Math, and Exploration](#-science-math-and-exploration)

Aside from those listed here, many other apps and libraries can be easily be found via the reverse dependencies on crates.io and GitHub:

* <https://github.com/ratatui/ratatui/network/dependents> ⭐ 22,614 | 🐛 215 | 🌐 Rust | 📅 2026-09-15
* <https://github.com/fdehau/tui-rs/network/dependents?package_id=UGFja2FnZS0zMjE3MzkzMDMx> ⚠️ Archived
* <https://crates.io/crates/ratatui/reverse_dependencies>
* <https://crates.io/crates/tui/reverse_dependencies>

## 📦 Libraries

### 🏗️ Frameworks

* [burn](https://github.com/burn-rs/burn) ⭐ 15,926 | 🐛 303 | 🌐 Rust | 📅 2026-09-16 - Comprehensive Deep Learning framework in Rust.
* [ratzilla](https://github.com/orhun/ratzilla) ⭐ 1,452 | 🐛 49 | 🌐 Rust | 📅 2026-07-04 - Build terminal-themed web applications with Ratatui and WebAssembly.
* [mousefood](https://github.com/j-g00da/mousefood) ⭐ 1,326 | 🐛 22 | 🌐 Rust | 📅 2026-09-15 - An embedded-graphics backend for Ratatui.
* [bevy\_ratatui\_camera](https://github.com/cxreiff/bevy_ratatui_camera) ⭐ 337 | 🐛 2 | 🌐 Rust | 📅 2025-11-17 - A bevy plugin for rendering your bevy app to the terminal using ratatui.
* [egui-ratatui](https://github.com/gold-silver-copper/egui_ratatui) ⭐ 210 | 🐛 4 | 🌐 Rust | 📅 2026-04-16 - A ratatui backend that is also an egui widget. Deploy on web with WebAssembly or ship natively with bevy, macroquad, or eframe.
* [ratatuefi](https://github.com/sermuns/ratatuefi) ⭐ 165 | 🐛 0 | 🌐 Rust | 📅 2026-07-06 - A Ratatui backend for drawing terminal UIs in pre-boot UEFI environments.
* [ratatui-wgpu](https://github.com/Jesterhearts/ratatui-wgpu) ⭐ 132 | 🐛 5 | 🌐 Rust | 📅 2026-08-06 - A wgpu based rendering backend for ratatui.
* [webatui](https://github.com/TylerBloom/webatui) ⭐ 129 | 🐛 4 | 🌐 Rust | 📅 2024-09-30 - An integration between the Yew and Ratatui crates for making TUI-themed WebAssembly webapps.
* [soft\_ratatui](https://github.com/gold-silver-copper/soft_ratatui) ⭐ 105 | 🐛 0 | 🌐 Rust | 📅 2026-04-23 - A software rendering backend for ratatui. No GPU required. TUI everywhere.
* [ratatui-uefi](https://github.com/reubeno/tui-uefi) ⭐ 100 | 🐛 3 | 🌐 Rust | 📅 2026-08-31 - A Ratatui backend for drawing terminal UIs in pre-boot UEFI environments.
* [schemaui](https://github.com/YuniqueUnic/schemaui) ⭐ 89 | 🐛 2 | 🌐 Rust | 📅 2026-09-15 - Turn JSON Schemas into TUIs and web UIs with real-time validation.
* [rat-salsa](https://github.com/thscharler/rat-salsa) ⭐ 64 | 🐛 5 | 🌐 Rust | 📅 2026-07-03 - An event-queue for ratatui with tasks, timers, application events, focus handling, dialog windows.
* [raclettui](https://github.com/ishrut/raclettui) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-07-29 - A wayland layer shell window implementing the ratatui backend with cpu and wgpu rendering.
* [ratatui-kit](https://github.com/yexiyue/ratatui-kit) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2026-09-09 - A React-style component framework for Ratatui with hooks, routing, async state, input layers, and reusable components.
* [crepuscularity](https://github.com/tschk/crepuscularity) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-09-16 - One UI codebase for desktop, web, mobile, terminal, browser extensions, and embedded devices. Write React JSX or our lightweight DSL, get GPUI, Ratatui, SwiftUI, LVGL, and more. Batteries included.
* [dumo](https://github.com/iddey/dumo) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 - An embedded-graphics backend that is built on [mplusfonts](https://github.com/iddey/mplusfonts) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 and has kanji support.
* [xnano](https://github.com/hsaeed3/xnano) ⭐ 17 | 🐛 6 | 🌐 Python | 📅 2026-09-09 - A declarative terminal framework for Python built on ratatui & ratzilla.
* [ratatui-minecraft](https://github.com/janTatesa/ratatui-minecraft) ⭐ 16 | 🐛 1 | 🌐 Rust | 📅 2025-06-24 - A Ratatui backend for rendering terminal UIs inside Minecraft via [valence-screens](https://github.com/White-145/valence-screens) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-20.
* [rlt](https://crates.io/crates/rlt) - A universal load testing framework for Rust, with real-time tui support.
* [tui-react](https://crates.io/crates/tui-react) - TUI widgets using a react-like paradigm.
* [tui-realm](https://crates.io/crates/tuirealm) - A ratatui framework inspired by Elm and React.
* [widgetui](https://crates.io/crates/widgetui) - A bevy-like widget system for ratatui and crossterm.

### 🧩 Widgets

* [edtui](https://github.com/preiter93/edtui) ⭐ 158 | 🐛 4 | 🌐 Rust | 📅 2026-08-16 - A Vim-inspired terminal editor.
* [ratatui-splash-screen](https://github.com/orhun/ratatui-splash-screen) ⭐ 154 | 🐛 1 | 🌐 Rust | 📅 2026-09-14 - Turns any image into a splash screen.
* [ratatui-code-editor](https://github.com/vipmax/ratatui-code-editor) ⭐ 114 | 🐛 6 | 🌐 Rust | 📅 2026-07-07 - A code editor with syntax highlighting powered by tree-sitter.
* [ratatui-explorer](https://github.com/tatounee/ratatui-explorer) ⭐ 94 | 🐛 3 | 🌐 Rust | 📅 2026-03-06 - A simple file-explorer library.
* [tui-rain](https://github.com/levilutz/tui-rain) ⭐ 79 | 🐛 4 | 🌐 Rust | 📅 2024-11-30 - A widget to generate various rain effects.
* [tui-menu](https://github.com/shuoli84/tui-menu) ⭐ 56 | 🐛 2 | 🌐 Rust | 📅 2025-12-30 - A menu component.
* [ratatui-markdown](https://github.com/celestia-island/ratatui-markdown) ⭐ 46 | 🐛 8 | 🌐 Rust | 📅 2026-09-15 - A Rust library providing markdown rendering, Mermaid diagrams, syntax highlighting, collapsible JSON/TOML tree views, and a rich hybrid scroll system.
* [term-rustdoc](https://github.com/zjp-CN/term-rustdoc) ⭐ 34 | 🐛 16 | 🌐 Rust | 📅 2025-04-20 - A TUI for Rust docs that aims to improve the UX on tree view and generic code.
* [tui-shimmer](https://github.com/vinhnx/tui-shimmer) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2026-06-06 - A shimmer text effect.
* [tui-popup](https://github.com/joshka/tui-popup) ⚠️ Archived - A popup component.
* [tui-globe](https://github.com/d10n/tui-globe) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 - A 3D globe widget rendered in the terminal with Braille characters.
* [ratatui-form](https://github.com/DavidLiedle/ratatui-form) ⭐ 20 | 🐛 2 | 🌐 Rust | 📅 2026-04-13 - A form library.
* [ratatui-stacked-bar](https://github.com/zeqianli/ratatui-stacked-bar) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-04-07 - A stacked area chart.
* [ratatui-tournament](https://github.com/philipgreat/ratatui-tournament) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-07 - A widget for rendering single-elimination tournament brackets in the terminal.
* [hyperrat](https://crates.io/crates/hyperrat) - Clickable terminal links.
* [malevich](https://crates.io/crates/malevich) - A plotting widget: line, scatter, bar, histogram, heatmap, box plot, violin, and more, with automatic axes and millions of points.
* [rat-widget](https://crates.io/crates/rat-widget) - Widgets for data-input (text-input, date- and number-input, text-area, checkbox, choice, radiobutton, slider, calendar), structural widgets (view, split, tabbed, multi-page), a table widget for large data-sets, a file-dialog, a menubar+sub-menus, a status-bar and some more. With builtin crossterm event-handling and focus-handling.
* [ratatui-cheese](https://crates.io/crates/ratatui-cheese) - Bubbletea-inspired widgets, including spinner, help, tree, paginator, and list.
* [ratatui-comfy-tabs](https://crates.io/crates/ratatui-comfy-tabs) - A feature-rich tab navigation for TUI. Highly customizable.
* [ratatui-comfy-toaster](https://crates.io/crates/ratatui-comfy-toaster) - An advanced toast-notification engine for terminal UI applications.
* [ratatui-fretboard](https://crates.io/crates/ratatui-fretboard) - Displays musical note positions on a fretboard.
* [ratatui-image](https://crates.io/crates/ratatui-image) - Displays images using Sixel graphics or Unicode half-blocks.
* [ratatui-textarea](https://crates.io/crates/ratatui-textarea) - A simple yet powerful editor; fork of `tui-textarea`.
* [ratatui-toaster](https://crates.io/crates/ratatui-toaster) - An extremely lightweight toast engine.
* [ratatui-wireframe](https://crates.io/crates/ratatui-wireframe) -  A widget for rendering and rotating 3D wireframe models.
* [ratiform](https://crates.io/crates/ratiform) - A stateful form widget with typed field identifiers, so your data model stays your own, not the library's.
* [throbber-widgets-tui](https://crates.io/crates/throbber-widgets-tui) - A widget that displays throbber.
* [tui-additions](https://crates.io/crates/tui-additions) - Additions to the rust tui crate.
* [tui-big-text](https://crates.io/crates/tui-big-text) - Displays big text using the `font8x8` crate.
* [tui-checkbox](https://crates.io/crates/tui-checkbox) - A customizable checkbox.
* [tui-dialog](https://docs.rs/tui-dialog) - A widget for entering a single line of text in a dialog.
* [tui-input](https://crates.io/crates/tui-input) - A headless input library for TUI apps.
* [tui-logger](https://crates.io/crates/tui-logger) - A logger with a smart log viewer.
* [tui-nodes](https://crates.io/crates/tui-nodes) - Visualize node graphs.
* [tui-overlay](https://crates.io/crates/tui-overlay) - A composable overlay widget with drawers, modals, popovers, and toasts from a single configurable primitive.
* [tui-piechart](https://crates.io/crates/tui-piechart) - A configurable, colorful piechart widget that comes in standard and high resolution.
* [tui-prompts](https://crates.io/crates/tui-prompts) - A library for building interactive prompts.
* [tui-scrollview](https://crates.io/crates/tui-scrollview) - A container that provides a scrolling view at a larger area.
* [tui-skeleton](https://crates.io/crates/tui-skeleton) - A library of placeholder widgets that pulse, sweep, or shimmer while your content loads.
* [tui-slider](https://crates.io/crates/tui-slider) - A highly customizable slider widget for both horizontal and vertical orientations.
* [tui-tabs](https://crates.io/crates/tui-tabs) - A tab navigation widget with individually bordered boxes and rounded corners.
* [tui-term](https://crates.io/crates/tui-term) - Embeds interactive terminal sessions.
* [tui-textarea](https://crates.io/crates/tui-textarea) - A simple yet powerful terminal text editor.
* [tui-tree-widget](https://crates.io/crates/tui-tree-widget) - A tree view.
* [tui-widget-list](https://crates.io/crates/tui-widget-list) - A versatile list implementation.

### 🔧 Utilities

* [tachyonfx](https://github.com/junkdog/tachyonfx) ⭐ 1,295 | 🐛 7 | 🌐 Rust | 📅 2026-09-06 - An animation and visual-effects library for Ratatui applications.
* [bevy\_ratatui](https://github.com/joshka/bevy_ratatui) ⭐ 170 | 🐛 8 | 🌐 Rust | 📅 2026-09-11 - A Rust crate to use Ratatui in a Bevy App.
* [ratatui-garnish](https://github.com/franklaranja/ratatui-garnish) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2025-10-14 - A powerful composition system for Ratatui widgets.
* [ratatui-interact](https://github.com/Brainwires/ratatui-interact) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2026-04-02 - Interactive TUI components for Ratatui with focus management and mouse support.
* [ratatui-macros](https://github.com/kdheepak/ratatui-macros) ⚠️ Archived - Macros for simplifying boilerplate for creating UI using Ratatui.
* [coolor](https://github.com/Canop/coolor) ⭐ 33 | 🐛 2 | 🌐 Rust | 📅 2025-05-09 - Tiny color conversion library for TUI application builders.
* [termprofile](https://github.com/aschey/termprofile) ⭐ 33 | 🐛 2 | 🌐 Rust | 📅 2026-09-12 - Detect and handle terminal color/styling support. Supports converting Ratatui color and style objects.
* [tui-syntax-highlight](https://github.com/aschey/tui-syntax-highlight) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-09-04 - Syntax highlighting for code blocks.
* [ggsci-ratatui](https://github.com/nanxstats/ggsci-rs) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-07-31 - Scientific and sci-fi color palettes from ggsci as Ratatui colors and styles, in truecolor or ANSI-256 mode.
* [ansi-to-tui](https://crates.io/crates/ansi-to-tui) - A library to convert ansi color coded text into `ratatui::text::Text`.
* [color-to-tui](https://crates.io/crates/color-to-tui) - Parse colors and convert them to `ratatui::style::Colors`.
* [opaline](https://crates.io/crates/opaline) - Token-based theme engine for Ratatui with gradients, 20 builtin themes, user theme discovery, and a reusable theme selector widget.
* [ratatui-input-manager](https://crates.io/ratatui-input-manager) - A macro for creating declarative update handlers in Elm style apps, supporting crossterm, termion and termwiz.
* [terminput](https://crates.io/crates/terminput) - An abstraction over various backends that provide input events.
* [tui-pantry](https://crates.io/crates/tui-pantry) - Component-driven development tool for ratatui widgets, similar to Storybook.

### 🔗 Bindings

* [jatatui](https://github.com/oyvindberg/jatatui) ⭐ 286 | 🐛 1 | 🌐 Java | 📅 2026-08-22 - A Java port of ratatui.
* [ex\_ratatui](https://github.com/mcass19/ex_ratatui) ⭐ 115 | 🐛 0 | 🌐 Elixir | 📅 2026-09-14 - Elixir bindings for ratatui.
* [ratatui-ffi](https://github.com/holo-q/ratatui-ffi) ⭐ 53 | 🐛 2 | 🌐 Rust | 📅 2026-06-04 - Foreign Function Interface bindings for Ratatui.
* [ratatui-py](https://github.com/holo-q/ratatui-py) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-06-04 - Python bindings for ratatui.
* [Ratatui.cs](https://github.com/holo-q/Ratatui.cs) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2026-06-04 - C# bindings for ratatui.
* [ratatui-ts](https://github.com/holo-q/ratatui-ts) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - TypeScript bindings for ratatui.
* [ratatui-go](https://github.com/holo-q/ratatui-go) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-09-12 - Go bindings for ratatui.
* [ratatui\_ruby](https://sr.ht/~kerrick/ratatui_ruby/) - Ruby bindings for ratatui.

## 💻 Apps

### ⌨️ Development Tools

#### Source Control and Collaboration

* [gitui](https://github.com/extrawurst/gitui) ⭐ 22,496 | 🐛 344 | 🌐 Rust | 📅 2026-08-04 - Terminal UI for Git.
* [wrkflw](https://github.com/bahdotsh/wrkflw) ⭐ 3,317 | 🐛 13 | 🌐 Rust | 📅 2026-09-08 - A TUI for validating and executing GitHub Actions workflows locally.
* [gitu](https://github.com/altsem/gitu) ⭐ 2,913 | 🐛 60 | 🌐 Rust | 📅 2026-08-22 - A TUI Git client inspired by Magit.
* [serie](https://github.com/lusingander/serie) ⭐ 2,101 | 🐛 25 | 🌐 Rust | 📅 2026-09-08 - A rich Git commit graph in your terminal.
* [lazyjj](https://github.com/Cretezy/lazyjj) ⭐ 1,212 | 🐛 46 | 🌐 Rust | 📅 2026-03-02 - A TUI for the Jujutsu version-control system.
* [drydock](https://github.com/yetidevworks/drydock) ⭐ 301 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - A live dashboard for a fleet of Git repos, showing what's uncommitted, unpushed, and unreleased across all of them.
* [giff](https://github.com/bahdotsh/giff) ⭐ 275 | 🐛 8 | 🌐 Rust | 📅 2026-04-23 - A TUI for Git diffs with interactive rebase support.
* [glim](https://github.com/junkdog/glim) ⭐ 234 | 🐛 17 | 🌐 Rust | 📅 2025-10-13 - Monitor GitLab continuous integration and delivery pipelines and projects.
* [deadbranch](https://github.com/armgabrielyan/deadbranch) ⭐ 230 | 🐛 2 | 🌐 Rust | 📅 2026-03-30 - A TUI for cleaning stale Git branches safely.
* [gwm](https://github.com/kbrdn1/gwm-cli) ⭐ 134 | 🐛 26 | 🌐 Rust | 📅 2026-09-14 - A Git worktree manager: CLI and TUI in one binary, native libgit2, per-repo declarative bootstrap, and AI agent session tracking.
* [gitv](https://github.com/jayanaxhf/gitv) ⭐ 115 | 🐛 12 | 🌐 Rust | 📅 2026-09-10 - A beautiful, feature-rich and performant terminal client for GitHub issues.
* [nomad](https://github.com/JosephLai241/nomad) ⭐ 74 | 🐛 9 | 🌐 Rust | 📅 2023-05-10 - Customizable next-gen tree command with Git integration and TUI.
* [git-time-machine](https://github.com/dinakars777/git-time-machine) ⭐ 71 | 🐛 2 | 🌐 Rust | 📅 2026-05-31 - Visual Git reflog TUI for undoing Git mistakes.
* [gimoji](https://github.com/zeenix/gimoji) ⭐ 52 | 🐛 7 | 🌐 Rust | 📅 2026-09-13 - Makes it easy to add emojis to your Git commit messages.
* [blippy](https://github.com/AksharP5/blippy) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2026-09-08 - A keyboard-first TUI for GitHub issues and pull requests.
* [Gitside](https://github.com/dev-bhaskar8/gitside) ⭐ 20 | 🐛 10 | 🌐 Rust | 📅 2026-08-15 - A responsive, mouse-friendly Git source-control TUI for full terminals and narrow tmux panes.
* [rootle](https://github.com/rootledev/rootle) ⭐ 5 | 🐛 7 | 🌐 Rust | 📅 2026-09-11 - A modal TUI for browsing GitHub and other source-control services with column views and syntax-highlighted previews.
* [ComfyGit](https://github.com/comfy-home/ComfyGit) ⭐ 3 | 🐛 7 | 🌐 Rust | 📅 2026-08-09 - All-In-One: Centralised multi-project management, Changelog generator, Version bumper & CLI tool introducing a new ComfyGitFlow.
* [Livediff](https://github.com/SoCkEt7/Livediff) ⭐ 2 | 🐛 2 | 🌐 Rust | 📅 2026-09-13 - Real-time terminal file diff monitoring TUI.

#### Code Search, Editing, and Review

* [scooter](https://github.com/thomasschafer/scooter) ⭐ 1,295 | 🐛 20 | 🌐 Rust | 📅 2026-09-12 - Interactive find and replace in the terminal.
* [Serpl](https://github.com/yassinebridi/serpl) ⭐ 856 | 🐛 22 | 🌐 Rust | 📅 2026-05-31 - A simple terminal UI for search and replace, ala VS Code.
* [igrep](https://github.com/konradsz/igrep) ⭐ 844 | 🐛 10 | 🌐 Rust | 📅 2026-09-09 - Interactive Grep.
* [repgrep](https://github.com/acheronfail/repgrep) ⭐ 532 | 🐛 1 | 🌐 Rust | 📅 2026-09-02 - An interactive replacer for ripgrep that makes it easy to find and replace across files on the command line.
* [blogr](https://github.com/bahdotsh/blogr) ⭐ 345 | 🐛 13 | 🌐 Rust | 📅 2026-06-08 - A terminal-based static site generator with a TUI editor for writing blog posts.
* [rgx](https://github.com/brevity1swos/rgx) ⭐ 235 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A terminal regex debugger with real-time matching, 3 engines, capture group highlighting, replace mode, and plain-English explanations.
* [oracle](https://github.com/yashksaini-coder/oracle) ⭐ 157 | 🐛 0 | 🌐 Rust | 📅 2026-04-02 - A TUI Rust codebase inspector to browse functions, structs, enums, traits, and more.
* [codemark](https://github.com/DanielCardonaRojas/codemark) ⭐ 122 | 🐛 7 | 🌐 Rust | 📅 2026-08-31 - A semantic code bookmarking system for humans and agents.
* [regect](https://github.com/kloki/regect) ⭐ 96 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A regex101 like tool for the cli.
* [ygrep](https://github.com/yetidevworks/ygrep) ⭐ 58 | 🐛 2 | 🌐 Rust | 📅 2026-09-15 - A fast, local, indexed code-search tool with a TUI for AI coding assistants.
* [image-auditor](https://github.com/0franco/image-auditor) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-07-05 - A TUI for finding and fixing website image-performance issues such as layout shifts, lazy loading, WebP, and responsive images.
* [lingora-tui](https://github.com/nigeleke/lingora) ⭐ 35 | 🐛 3 | 🌐 Rust | 📅 2026-09-14 - Browse, compare and validate Fluent i18n files.
* [termi](https://github.com/tuna4ll/termi) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A modal terminal code editor.
* [VLE](https://github.com/tuffy/vle) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-09-09 - A lightweight text editor.

#### APIs, Databases, Build, and Debugging

* [oha](https://github.com/hatoo/oha) ⭐ 10,548 | 🐛 58 | 🌐 Rust | 📅 2026-09-10 - An HTTP load generator with a real-time terminal UI.
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,331 | 🐛 14 | 🌐 Rust | 📅 2026-08-25 - A database management TUI for Postgres.
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,727 | 🐛 20 | 🌐 Rust | 📅 2026-09-03 - A feature-full TUI API client for your terminal.
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,319 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 - Cross-platform TUI database management tool.
* [BugStalker](https://github.com/godzie44/BugStalker) ⭐ 1,413 | 🐛 15 | 🌐 Rust | 📅 2026-08-22 - Modern rust debugger for Linux x86-64.
* [openapi-tui](https://github.com/zaghaghi/openapi-tui) ⭐ 1,326 | 🐛 9 | 🌐 Rust | 📅 2026-05-14 - A terminal UI for browsing and calling APIs from OpenAPI specifications.
* [desed](https://github.com/SoptikHa2/desed) ⭐ 1,218 | 🐛 7 | 🌐 Rust | 📅 2026-05-16 - Debugging tool for sed scripts.
* [Maelstrom](https://github.com/maelstrom-software/maelstrom) ⭐ 735 | 🐛 190 | 🌐 Rust | 📅 2025-04-23 - A fast test runner that runs every test in its own container locally or distributed.
* [Surfpool](https://github.com/solana-foundation/surfpool) ⭐ 602 | 🐛 58 | 🌐 Rust | 📅 2026-09-05 - A local-first Solana development environment with mainnet state, infrastructure as code and transaction debugging.
* [tracexec](https://github.com/kxxt/tracexec) ⭐ 438 | 🐛 27 | 🌐 Rust | 📅 2026-09-07 - A terminal tool for tracing which programs and commands are executed.
* [sabiql](https://github.com/riii111/sabiql) ⭐ 306 | 🐛 7 | 🌐 Rust | 📅 2026-09-13 - Fast, driverless, Vim-first database TUI with safe editing and ER diagrams.
* [envx](https://github.com/mikeleppane/envx) ⭐ 230 | 🐛 5 | 🌐 Rust | 📅 2025-09-19 - Environment variable manager for developers, featuring an intuitive TUI.
* [wireman](https://github.com/preiter93/wireman) ⭐ 179 | 🐛 6 | 🌐 Rust | 📅 2026-09-12 - A terminal client for calling gRPC services.
* [ratifact](https://github.com/adolfousier/ratifact) ⭐ 90 | 🐛 1 | 🌐 Rust | 📅 2025-11-28 - Track and manage build artifacts from multiple programming languages.
* [tongo](https://github.com/drewzemke/tongo) ⭐ 74 | 🐛 2 | 🌐 Rust | 📅 2026-08-23 - A TUI for MongoDB.
* [cargo-selector](https://github.com/lusingander/cargo-selector) ⭐ 73 | 🐛 1 | 🌐 Rust | 📅 2026-09-02 - Cargo subcommand to select and execute binary/example targets.
* [get\_blessed\_rs](https://github.com/josueBarretogit/get_blessed_rs) ⭐ 50 | 🐛 0 | 🌐 Rust | 📅 2024-06-29 - Get the best crates for your rust projects, curated by blessed.rs.
* [deputui](https://github.com/twiddler/deputui) ⭐ 36 | 🐛 4 | 🌐 Rust | 📅 2026-09-14 - Review and install JavaScript package updates from npm.
* [depot-rs](https://github.com/quietpigeon/depot-rs) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2025-10-04 - A TUI for managing crates.
* [TaskUI](https://github.com/thmshmm/taskui) ⭐ 24 | 🐛 1 | 🌐 Rust | 📅 2024-08-11 - Simple Terminal UI for Task / taskfile.dev.
* [agx](https://github.com/brevity1swos/agx) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-06-25 - A step-through debugger for AI agent execution traces.
* [raygun](https://github.com/yetidevworks/raygun) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-08-04 - A terminal-based receiver for Spatie's Ray debugger, compatible with the Ray HTTP protocol used by PHP, Laravel, and Grav.

### 🤖 AI and Agents

* [BitFun](https://github.com/GCWing/BitFun) ⭐ 2,211 | 🐛 82 | 🌐 Rust | 📅 2026-09-16 - An open-source desktop workspace for general-purpose AI agents.
* [Stakpak](https://github.com/stakpak/agent) ⭐ 1,788 | 🐛 41 | 🌐 Rust | 📅 2026-07-06 - AI DevOps agent to help you secure, deploy, and maintain production-ready infrastructure.
* [opencrabs](https://github.com/adolfousier/opencrabs) ⭐ 939 | 🐛 9 | 🌐 Rust | 📅 2026-09-16 - An all-in-one AI agent for the terminal with TUI, CLI, and daemon modes.
* [VT Code](https://github.com/vinhnx/vtcode) ⭐ 845 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - An open-source Rust coding agent for the terminal.
* [Oatmeal](https://github.com/dustinblackman/oatmeal) ⭐ 771 | 🐛 31 | 🌐 Rust | 📅 2024-06-01 - Terminal UI to chat with large language models (LLM) using different model backends, and integrations with your favourite editors!
* [tenere](https://github.com/pythops/tenere) ⭐ 683 | 🐛 11 | 🌐 Rust | 📅 2026-05-10 - A terminal chat interface for large language models, written in Rust.
* [patent](https://github.com/r14dd/patent) ⭐ 526 | 🐛 5 | 🌐 Rust | 📅 2026-09-14 - A prior-art search for developer-tool ideas with an AI-generated verdict.
* [models](https://github.com/arimxyer/models) ⭐ 509 | 🐛 0 | 🌐 Rust | 📅 2026-09-16 - A TUI for browsing AI models, benchmarks, and coding agents.
* [pixtuoid](https://github.com/IvanWng97/pixtuoid) ⭐ 480 | 🐛 8 | 🌐 Rust | 📅 2026-09-16 - Live pixel-art office for AI coding agents.
* [llmtrim](https://github.com/fkiene/llmtrim) ⭐ 231 | 🐛 12 | 🌐 Rust | 📅 2026-09-15 - A local proxy that compresses large-language-model API requests to reduce token costs, with a dashboard for per-source costs and context usage.
* [claudectl](https://github.com/mercurialsolo/claudectl) ⭐ 199 | 🐛 63 | 🌐 Rust | 📅 2026-07-10 - Mission control for multiple Claude Code sessions with live dashboard, cost tracking, and budget enforcement.
* [toktop](https://github.com/htin1/toktop) ⭐ 174 | 🐛 5 | 🌐 Rust | 📅 2025-12-07 - A terminal dashboard for monitoring OpenAI and Anthropic token usage and costs.
* [Martty](https://github.com/openma-ai/Martty) ⭐ 76 | 🐛 3 | 🌐 Rust | 📅 2026-09-13 - An extensible Rust/ratatui terminal client for DeepSeek Harness and ACP-compatible coding agents, with plugins, tools, subagents, and durable sessions.
* [thurbox](https://github.com/Thurbeen/thurbox) ⭐ 69 | 🐛 2 | 🌐 Rust | 📅 2026-09-16 - A TUI orchestrator for running multiple AI coding agents (Claude Code, Codex, and others) in persistent tmux sessions.
* [opencode stats](https://github.com/Cateds/opencode-stats) ⭐ 66 | 🐛 2 | 🌐 Rust | 📅 2026-08-04 - A terminal dashboard for OpenCode usage statistics and cost breakdowns.
* [nereid](https://github.com/bnomei/nereid) ⭐ 65 | 🐛 0 | 🌐 Rust | 📅 2026-07-11 - Create and explore Mermaid diagrams with AI agents through a terminal UI and Model Context Protocol server.
* [bosun](https://github.com/yetidevworks/bosun) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A tmux-native TUI for orchestrating AI coding agent sessions (Claude Code, Codex) with live previews and per-session state.
* [commandOK](https://github.com/64bit/commandOK) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2026-06-16 - A Spotlight-like terminal command generator powered by major large-language-model providers.
* [SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) ⭐ 40 | 🐛 2 | 🌐 Rust | 📅 2026-09-12 - Lightning fast terminal native agent harness with tools, extensions and subagents. 15MB, 2ms boot.
* [Proqi](https://github.com/oborchers/proqi) ⭐ 29 | 🐛 6 | 🌐 Rust | 📅 2026-09-15 - A terminal-native prompt composer for developers working with coding agents.
* [amtr](https://github.com/arian-shamaei/anthropometer) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-09-09 - A btop-style TUI that renders a Claude Code session's live context window as a memory map, with tool and file traffic, cache economics, and a compiled PDF report.
* [crmux](https://github.com/maedana/crmux) ⭐ 27 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A TUI viewer for monitoring and managing multiple Claude Code sessions in tmux.
* [agent-console](https://github.com/buhuipao/agent-console) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - A local dashboard for Codex and Claude Code.
* [raymon](https://github.com/bnomei/raymon) ⭐ 18 | 🐛 3 | 🌐 Rust | 📅 2026-07-01 - A terminal UI and Model Context Protocol (MCP) server for receiving and searching Ray-style debug logs.
* [ilmari](https://github.com/bnomei/ilmari) ⭐ 17 | 🐛 5 | 🌐 Rust | 📅 2026-08-08 - A tmux popup dashboard for monitoring AI coding agents.
* [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory) ⭐ 17 | 🐛 3 | 🌐 Rust | 📅 2026-09-15 - A local-first memory system for AI agents with SQLite full-text search, auditing, forgetting, consolidation, and a Ratatui operator console.
* [Yardlet](https://github.com/zzunkie/yardlet) ⭐ 17 | 🐛 4 | 🌐 Rust | 📅 2026-09-14 - A local AI workbench that turns intent into a verified task queue and drives your installed Claude Code or Codex CLIs as interchangeable workers.
* [partly-claudy](https://github.com/taho-inc/partly-claudy) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-04-28 - Terminal view of Claude status page (status.claude.com).
* [gmsg](https://github.com/olorikendrick/gmsg) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Generate, edit, and commit AI-powered Git commit messages from a single TUI.
* [hedos](https://github.com/theiskaa/hedos) ⭐ 12 | 🐛 7 | 🌐 Rust | 📅 2026-09-09 - A terminal shelf for the local AI models already on your machine, with a built-in OpenAI-compatible gateway.
* [LimitDeck](https://github.com/rockythink/limitdeck) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-09-12 - A compact, privacy-safe terminal dashboard for AI coding subscription limits.
* [Forge](https://github.com/NorviaLabs/forge) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - An AI coding agent that unifies an agent, code editor, and shell in a single keyboard-driven terminal workspace.
* [Reeve](https://github.com/Dancode-188/reeve) ⭐ 7 | 🐛 9 | 🌐 Rust | 📅 2026-09-06 - A terminal cockpit for AI agents: watch a run live, score it, and step in when it goes sideways.
* [iris](https://github.com/itzenata/iris-tui) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-07-08 - Live supervisor for every active Claude Code session - status, tokens, estimated cost, and one-pane approval of tool calls.

### 📁 Files, Data, and Documents

* [Yazi](https://github.com/sxyazi/yazi) ⭐ 42,221 | 🐛 65 | 🌐 Rust | 📅 2026-09-15 - Blazing fast terminal file manager written in Rust, based on async I/O.
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,822 | 🐛 12 | 🌐 Rust | 📅 2026-09-15 - Hackable, minimal, and fast TUI file explorer.
* [xan](https://github.com/medialab/xan) ⭐ 4,510 | 🐛 119 | 🌐 Rust | 📅 2026-09-15 - A terminal tool for processing CSV files.
* [binsider](https://github.com/orhun/binsider) ⭐ 4,432 | 🐛 38 | 🌐 Rust | 📅 2026-09-13 - A TUI for analyzing binary files.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 3,964 | 🐛 60 | 🌐 Rust | 📅 2026-07-04 - Command line csv viewer.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,753 | 🐛 8 | 🌐 Rust | 📅 2026-08-10 - Document viewer for Microsoft Word files.
* [joshuto](https://github.com/kamiyaa/joshuto) ⭐ 3,728 | 🐛 102 | 🌐 Rust | 📅 2026-08-20 - Ranger-like terminal file manager written in Rust.
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,129 | 🐛 45 | 🌐 Rust | 📅 2024-03-07 - Terminal-based disk space navigator.
* [tabiew](https://github.com/shshemi/tabiew) ⭐ 3,105 | 🐛 17 | 🌐 Rust | 📅 2026-09-15 - A lightweight TUI app to view and query CSV files.
* [stu](https://github.com/lusingander/stu) ⭐ 910 | 🐛 15 | 🌐 Rust | 📅 2026-04-30 - A TUI for AWS S3.
* [md-tui](https://github.com/henriklovhaug/md-tui) ⭐ 550 | 🐛 22 | 🌐 Rust | 📅 2026-09-12 - Markdown renderer in the terminal.
* [otree](https://github.com/fioncat/otree) ⭐ 516 | 🐛 3 | 🌐 Rust | 📅 2026-09-14 - A command line tool to view objects (JSON/YAML/TOML) in TUI tree widget.
* [hexhog](https://github.com/DVDTSB/hexhog) ⭐ 280 | 🐛 8 | 🌐 Rust | 📅 2026-02-16 - TUI Hex Editor/Viewer.
* [wiper](https://github.com/ikebastuz/wiper) ⭐ 249 | 🐛 11 | 🌐 Rust | 📅 2025-11-14 - Disk space analyzer and cleanup tool.
* [sheetsui](https://github.com/zaphar/sheetsui) ⭐ 246 | 🐛 4 | 🌐 Rust | 📅 2026-03-03 - A terminal based spreadsheet application.
* [FileSSH](https://github.com/JayanAXHF/filessh) ⭐ 230 | 🐛 3 | 🌐 Rust | 📅 2026-07-25 - A TUI-based file explorer for remote servers.
* [ddv](https://github.com/lusingander/ddv) ⭐ 102 | 🐛 3 | 🌐 Rust | 📅 2026-04-29 - Terminal DynamoDB viewer.
* [rat-commander](https://github.com/dividebysandwich/rat-commander) ⭐ 95 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - A fully-featured modern spiritual successor to Midnight-Commander with truecolor support and built-in process- and disk-explorer.
* [rdn](https://github.com/apatrushev/rdn) ⭐ 82 | 🐛 0 | 🌐 Rust | 📅 2026-03-17 - Rust port of well known old Dos Navigator.
* [TSHTS](https://github.com/SamuelSchlesinger/tshts) ⭐ 47 | 🐛 0 | 🌐 Rust | 📅 2026-05-28 - A terminal based spreadsheet application.
* [dead-ringer](https://github.com/ztroop/dead-ringer) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - A binary diff tool for comparing files in hexadecimal and ASCII.
* [comhad](https://github.com/Eoin-McMahon/Comhad) ⭐ 37 | 🐛 4 | 🌐 Rust | 📅 2026-09-09 - A ranger-style terminal browser for S3, with previews, background transfers, and non-destructive sync.
* [vib](https://github.com/ayanchavand/vib) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-07-25 - A terminal file browser with LocalSend built in, for managing, organizing and transferring files across devices.
* [flerp](https://github.com/Huseynteymurzade28/flerp) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2026-08-17 - A TUI for exploring and analyzing text files, PDFs and images.
* [columbus](https://github.com/sivaprakashkrp/columbus) ⭐ 23 | 🐛 1 | 🌐 Rust | 📅 2026-06-15 - A GUI-like TUI file explorer.
* [traceview](https://github.com/javaLux/traceview) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-08-26 - Tracing and viewing your files and resource landscape.
* [edamame](https://github.com/mijowi/edamame) ⭐ 4 | 🐛 15 | 🌐 Rust | 📅 2026-09-15 - A Terminal Markdown editor that stays rendered while you edit.

### 🧰 Terminal Workflow

* [atuin](https://github.com/atuinsh/atuin) ⭐ 31,639 | 🐛 417 | 🌐 Rust | 📅 2026-09-16 - A shell history manager with fast search and optional sync.
* [television](https://github.com/alexpasmantier/television) ⭐ 6,272 | 🐛 79 | 🌐 Rust | 📅 2026-09-11 - A blazingly fast general purpose fuzzy finder for your terminal.
* [mprocs](https://github.com/pvolok/mprocs) ⭐ 2,722 | 🐛 68 | 🌐 Rust | 📅 2026-09-13 - Run multiple commands in parallel and shows output of each command separately.
* [flyline](https://github.com/HalFrgrd/flyline) ⭐ 1,278 | 🐛 34 | 🌐 Rust | 📅 2026-09-14 - A Bash plugin TUI for an enhanced command line writing experience.
* [hwatch](https://github.com/blacknon/hwatch) ⭐ 1,079 | 🐛 10 | 🌐 Rust | 📅 2026-08-30 - Alternative watch command with command history and diffs.
* [fsel](https://github.com/Mjoyufull/fsel) ⭐ 423 | 🐛 10 | 🌐 Rust | 📅 2026-09-13 - A TUI app launcher and fuzzy finder for GNU/Linux and BSD.
* [kbt](https://github.com/bloznelis/kbt) ⭐ 392 | 🐛 5 | 🌐 Rust | 📅 2025-11-26 - Keyboard tester in terminal.
* [fzf-make](https://github.com/kyu08/fzf-make) ⭐ 296 | 🐛 45 | 🌐 Rust | 📅 2026-09-10 - A command line tool that executes make target using fuzzy finder with preview window.
* [exabind](https://github.com/junkdog/exabind) ⭐ 295 | 🐛 0 | 🌐 Rust | 📅 2026-03-29 - An animated TUI for viewing KDE shortcuts.
* [matchmaker](https://github.com/Squirreljetpack/matchmaker) ⭐ 236 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A fast, configurable fuzzy searcher for terminal data.
* [splashboard](https://github.com/unhappychoice/splashboard) ⭐ 214 | 🐛 16 | 🌐 Rust | 📅 2026-09-15 - A customizable terminal splash rendered on shell startup or directory updates.
* [snipt](https://github.com/snipt/snipt) ⭐ 149 | 🐛 5 | 🌐 Rust | 📅 2026-04-02 - A text snippet expansion tool with a TUI for managing snippets.
* [sigye](https://github.com/am2rican5/sigye) ⭐ 129 | 🐛 2 | 🌐 Rust | 📅 2026-09-10 - A terminal clock with FIGlet fonts, customizable themes, and animated backgrounds.
* [p2pmux](https://github.com/pelazas/p2pmux) ⭐ 69 | 🐛 3 | 🌐 Rust | 📅 2026-09-07 - A peer-to-peer terminal multiplexer for sharing sessions across machines.
* [material](https://github.com/azorng/material) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-08-14 - A material design color palette for the terminal.
* [absorb](https://github.com/kloki/absorb) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-04-11 - Quickly read a file without moving your eyes.
* [trex](https://github.com/blackopsrepl/trex) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-08-06 - A fast tmux session manager with fuzzy finding, per session stats and AI Agent tracking.

### 🌐 Networking and Internet

#### Network Operations and Infrastructure

* [gping](https://github.com/orf/gping/) ⭐ 12,680 | 🐛 40 | 🌐 Rust | 📅 2026-09-10 - Ping tool with a graph.
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 11,970 | 🐛 54 | 🌐 Rust | 📅 2026-08-01 - Displays network utilization by process.
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 7,927 | 🐛 85 | 🌐 Rust | 📅 2026-09-15 - Network diagnostic tool.
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 5,026 | 🐛 33 | 🌐 Rust | 📅 2026-09-14 - A cross-platform network monitoring tool with deep packet inspection.
* [impala](https://github.com/pythops/impala) ⭐ 2,851 | 🐛 0 | 🌐 Rust | 📅 2026-08-27 - TUI for managing wifi on Linux.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,579 | 🐛 5 | 🌐 Rust | 📅 2026-09-01 - A TUI for sniffing network traffic using eBPF.
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,848 | 🐛 6 | 🌐 Rust | 📅 2026-07-06 - Network scanning tool.
* [AdGuardian-Term](https://github.com/Lissy93/AdGuardian-Term) ⭐ 1,659 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 - Real-time traffic monitoring and statistics for AdGuard Home.
* [dnsglobe](https://github.com/514-labs/dnsglobe) ⭐ 1,158 | 🐛 0 | 🌐 Rust | 📅 2026-09-10 - Global DNS propagation checker querying 34 resolvers worldwide, with a world map.
* [adsb\_deku/radar](https://github.com/wcampbell0x2a/adsb_deku#radar-tui) ⭐ 728 | 🐛 25 | 🌐 Rust | 📅 2026-01-04 - A terminal radar for displaying aircraft positions from Automatic Dependent Surveillance–Broadcast (ADS-B) data.
* [mqttui](https://github.com/EdJoPaTo/mqttui) ⭐ 728 | 🐛 11 | 🌐 Rust | 📅 2026-08-09 - A terminal client for subscribing to and publishing messages over MQTT.
* [vortix](https://github.com/Harry-kp/vortix) ⭐ 648 | 🐛 27 | 🌐 Rust | 📅 2026-09-15 - Terminal UI for WireGuard and OpenVPN with real-time telemetry, leak detection, and kill switch.
* [unifly](https://github.com/hyperb1iss/unifly) ⭐ 257 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - CLI and TUI for managing Ubiquiti UniFi network controllers with an 8-screen dashboard, live traffic charts, and dual-API coverage.
* [streamtop](https://github.com/Jorji49/streamtop) ⭐ 105 | 🐛 8 | 🌐 Rust | 📅 2026-09-12 - A terminal monitor for live video streams with real-time health checks and metrics.
* [mullvad-tui](https://github.com/d10n/mullvad-tui) ⭐ 75 | 🐛 0 | 🌐 Rust | 📅 2026-06-24 - A TUI for Mullvad VPN.
* [ytunnel](https://github.com/yetidevworks/ytunnel) ⭐ 53 | 🐛 0 | 🌐 Rust | 📅 2026-08-05 - A TUI-first CLI for managing Cloudflare Tunnels with custom domains.
* [discovery-rs](https://github.com/JustPretender/discovery-rs) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2025-08-21 - A TUI for discovering services on your local network.
* [nordvpn-tui](https://github.com/Degra02/nordvpn-tui) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2024-10-08 - A TUI for NordVPN.
* [wiretui](https://github.com/robin-thoene/wiretui) ⭐ 18 | 🐛 4 | 🌐 Rust | 📅 2026-08-28 - A minimal keyboard-driven TUI to manage WireGuard VPN connections.
* [dsnitch](https://github.com/infomaniac777/dsnitch) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-09-04 - Real-time network and DNS egress inspector TUI for Docker containers powered by eBPF.
* [sensor-vision](https://github.com/jcfromsiberia/sensor-vision) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2025-04-26 - TUI Client for TeamViewer IoT MQTT API for managing IoT Sensors and Metrics.
* [yscan](https://github.com/yetidevworks/yscan) ⭐ 9 | 🐛 3 | 🌐 Rust | 📅 2026-08-04 - A TUI-first network scanner with ARP, mDNS, and SSDP discovery.
* [LazyMQTT](https://github.com/ScottFelder/lazymqtt) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-08-28 - A keyboard-driven terminal client for browsing and publishing messages over the MQTT messaging protocol.

#### Remote Access, APIs, and File Transfer

* [JocalSend](https://git.kittencollective.com/nebkor/joecalsend) - Peer to peer local file and data transfer, compatible with [LocalSend](https://github.com/localsend/localsend) ⭐ 91,740 | 🐛 1,122 | 🌐 Dart | 📅 2026-09-14
* [termscp](https://github.com/veeso/termscp) ⭐ 3,081 | 🐛 2 | 🌐 Rust | 📅 2026-09-03 - A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB.
* [slumber](https://github.com/LucasPickering/slumber) ⭐ 1,229 | 🐛 9 | 🌐 Rust | 📅 2026-09-02 - Terminal-based HTTP/REST client.
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 695 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 - A nyaa.si tui tool for browsing and downloading torrents.
* [purple](https://github.com/erickochen/purple) ⭐ 693 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 - TUI SSH config manager & launcher with fuzzy search, tags, cloud provider sync, tunnels and command snippets for server management.
* [ssh-list](https://github.com/akinoiro/ssh-list) ⭐ 221 | 🐛 5 | 🌐 Rust | 📅 2025-10-27 - SSH connection manager.
* [TermiRs](https://github.com/caelansar/termirs) ⭐ 221 | 🐛 1 | 🌐 Rust | 📅 2026-06-08 - A modern, async SSH terminal client.
* [CuTE](https://github.com/PThorpe92/CuTE) ⚠️ Archived - A libcurl powered HTTP Client with API-key/request mgmt and vim keybindings.
* [vincenzo](https://github.com/gabrieldemian/vincenzo) ⭐ 159 | 🐛 4 | 🌐 Rust | 📅 2026-04-05 - A bittorrent client for the terminal with vim-like keybindings.
* [lazy-etherscan](https://github.com/woxjro/lazy-etherscan) ⭐ 152 | 🐛 1 | 🌐 Rust | 📅 2025-04-20 - A Simple Terminal UI for the Ethereum Blockchain Explorer.
* [rustmission](https://github.com/intuis/rustmission) ⭐ 65 | 🐛 21 | 🌐 Rust | 📅 2026-03-26 - TUI for the Transmission daemon.
* [terminusdm](https://github.com/sumoduduk/terminusdm) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2024-08-22 - Cross Platform Terminal Download Manager.
* [conclusive](https://github.com/mrusme/conclusive) ⚠️ Archived - A command line client for Plausible Analytics.
* [jdtui](https://github.com/rylos/jdtui) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A TUI for JDownloader 2 over the My.JDownloader API: downloads, link grabber, accounts and settings, from anywhere.
* [traxor](https://github.com/kristoferssolo/traxor) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-05-14 - A TUI for managing Transmission torrents.

#### Communications and Social

* [concord](https://github.com/chojs23/concord) ⭐ 1,509 | 🐛 46 | 🌐 Rust | 📅 2026-09-15 - A TUI client for Discord.
* [iamb](https://github.com/ulyssa/iamb) ⭐ 1,280 | 🐛 130 | 🌐 Rust | 📅 2026-09-15 - A matrix chat client with vim keybindings.
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 1,012 | 🐛 17 | 🌐 Rust | 📅 2026-09-15 - A TUI for Telegram written in Rust.
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 632 | 🐛 10 | 🌐 Rust | 📅 2026-09-02 - Twitch chat in the terminal.
* [termchat](https://github.com/lemunozm/termchat) ⭐ 589 | 🐛 7 | 🌐 Rust | 📅 2023-11-27 - Terminal chat over a local network with video streaming and file transfer.
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 164 | 🐛 11 | 🌐 Rust | 📅 2025-12-28 - TUI client for Bluesky.
* [lobtui](https://github.com/pythops/lobtui) ⭐ 121 | 🐛 3 | 🌐 Rust | 📅 2025-05-16 - TUI for lobste.rs website.
* [mxr](https://github.com/planetaryescape/mxr) ⭐ 73 | 🐛 14 | 🌐 Rust | 📅 2026-09-10 - Local-first email client with Vim-style navigation, multi-account sync, and full-text search.
* [nostui](https://github.com/akiomik/nostui) ⭐ 71 | 🐛 30 | 🌐 Rust | 📅 2026-09-15 - A TUI client for Nostr.
* [youtube-chat-rs](https://github.com/efekrskl/youtube-chat-rs) ⭐ 30 | 🐛 7 | 🌐 Rust | 📅 2026-06-04 - A terminal UI for viewing YouTube live chat.
* [rvIRC](https://github.com/KaraZajac/rvIRC) ⭐ 24 | 🐛 0 | 🌐 Rust | 📅 2026-05-17 - A TUI client for IRC.
* [omaro](https://github.com/Rolv-Apneseth/omaro) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-09-12 - TUI for the lobste.rs website.
* [Chat-gRPC](https://github.com/Atheer2104/chat-grpc) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2024-08-13 - A Real-time Chat Microservice built in Rust using gRPC, including a TUI client.
* [tsuchita](https://github.com/kamiyaa/tsuchita) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - A client-server notification center for desktop notifications on Linux.
* [hnr](https://github.com/prasanthj/hnr) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A terminal UI for Hacker News — browse feeds, read threaded comments, vote, reply, search, and bookmark.

### 👨‍💻 System Administration

#### Monitoring, Diagnostics, and Logs

* [vector](https://github.com/vectordotdev/vector) ⭐ 22,566 | 🐛 2,492 | 🌐 Rust | 📅 2026-09-15 - A high-performance observability data pipeline.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,025 | 🐛 103 | 🌐 Rust | 📅 2026-09-16 - Cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,053 | 🐛 40 | 🌐 Rust | 📅 2026-09-02 - Cross-platform monitoring tool for system stats.
* [kmon](https://github.com/orhun/kmon) ⭐ 2,944 | 🐛 23 | 🌐 Rust | 📅 2026-07-31 - Linux Kernel Manager and Activity Monitor.
* [bpftop](https://github.com/Netflix/bpftop) ⭐ 2,706 | 🐛 5 | 🌐 C | 📅 2026-09-01 - A real-time monitor for Linux eBPF programs, showing runtime, event rate, and CPU usage.
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived - TUI system monitor for Linux.
* [diskwatch](https://github.com/matthart1983/diskwatch) ⭐ 445 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - Single-host, read-only disk diagnostics TUI.
* [logss](https://github.com/todoesverso/logss) ⭐ 297 | 🐛 3 | 🌐 Rust | 📅 2026-06-08 - A simple cli for logs splitting.
* [erldash](https://github.com/sile/erldash) ⭐ 175 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - A simple, terminal-based Erlang dashboard.
* [winproc-tui](https://github.com/TX230/winproc-tui) ⭐ 117 | 🐛 15 | 🌐 Rust | 📅 2026-09-15 - Process monitoring tool with live metrics, time-series graphs, A/B comparison.
* [tuistash](https://github.com/edmocosta/tuistash) ⭐ 109 | 🐛 2 | 🌐 Rust | 📅 2026-04-10 - A TUI for monitoring Logstash.
* [journalview](https://github.com/codervijo/journalview) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-05-20 - A TUI for browsing and filtering systemd journal logs.
* [rrtop](https://github.com/wojciech-zurek/rrtop) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2021-08-05 - Redis monitoring (top like) app. rrtop -> \[r]ust \[r]edis \[top].
* [cpustate-tui](https://github.com/mkulke/cpustate-tui) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-02-19 - A bootable TUI for inspecting x86\_64 CPU state.
* [Aperture](https://github.com/stylebending/Aperture) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Diagnostic TUI for Windows power users.
* [gentooplz](https://github.com/JustRoccat/gentooplz) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - A live terminal dashboard for Gentoo package builds.

#### Containers and Orchestration

* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,534 | 🐛 3 | 🌐 Rust | 📅 2026-09-09 - A simple and fast dashboard for Kubernetes.
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 1,840 | 🐛 23 | 🌐 Rust | 📅 2026-08-22 - Simple TUI to view & control Docker containers.
* [kftui](https://github.com/hcavarsan/kftray/blob/main/README.md#kftui) ⭐ 1,562 | 🐛 3 | 🌐 Rust | 📅 2026-09-16 - A TUI to manage multiple kubectl port-forward commands, with support for UDP and Kubernetes proxy.
* [ducker](https://github.com/robertpsoane/ducker) ⭐ 930 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 - A terminal app for managing Docker containers, inspired by K9s.
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 393 | 🐛 12 | 🌐 Rust | 📅 2026-09-14 - TUI for real-time monitoring of Kubernetes resources.
* [b4n](https://github.com/fioletoven/b4n) ⭐ 106 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - A terminal-based tool for browsing Kubernetes resources.
* [reeve](https://github.com/yetidevworks/reeve) ⭐ 87 | 🐛 1 | 🌐 Rust | 📅 2026-09-16 - Manages a local web stack as per-user services: Caddy, Apache or nginx, per-vhost PHP-FPM versions, databases, local SSL, and wildcard DNS.
* [kubectl-watch](https://github.com/imuxin/kubectl-watch) ⭐ 64 | 🐛 4 | 🌐 Rust | 📅 2023-10-25 - A kubectl plugin to provide a pretty delta change view of being watched Kubernetes resources.
* [stevedore](https://github.com/takumiymd/stevedore) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-09-02 - A fast, keyboard-driven terminal UI for managing Docker containers and Compose stacks.

#### OS, Storage, and Package Management

* [dua-cli](https://github.com/Byron/dua-cli) ⭐ 6,263 | 🐛 0 | 🌐 Rust | 📅 2026-09-12 - View disk space usage and delete unwanted data, fast.
* [linutil](https://github.com/ChrisTitusTech/linutil) ⭐ 5,284 | 🐛 20 | 🌐 Shell | 📅 2026-09-14 - A distro-agnostic toolbox designed to simplify everyday Linux tasks.
* [caligula](https://github.com/ifd3f/caligula) ⭐ 2,328 | 🐛 54 | 🌐 Rust | 📅 2026-09-16 - A user-friendly, lightweight TUI for disk imaging.
* [systemctl-tui](https://github.com/rgwood/systemctl-tui) ⭐ 2,058 | 🐛 6 | 🌐 Rust | 📅 2026-07-27 - A fast, simple TUI for interacting with systemd services and their logs.
* [systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) ⭐ 1,582 | 🐛 5 | 🌐 Rust | 📅 2026-09-13 - A program for managing systemd services through a TUI.
* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,469 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A terminal UI for reading and changing Linux kernel parameters.
* [lemurs](https://github.com/coastalwhite/lemurs) ⭐ 1,355 | 🐛 80 | 🌐 Rust | 📅 2026-06-28 - A customizable TUI login manager for Linux and BSD.
* [lazyrsync](https://github.com/westpoint-io/lazyrsync) ⭐ 823 | 🐛 1 | 🌐 Rust | 📅 2026-08-10 - A TUI for rsync: reusable profiles, a dry-run diff preview, and live run progress.
* [parui](https://github.com/Vonr/parui) ⭐ 218 | 🐛 1 | 🌐 Rust | 📅 2026-01-18 - A TUI frontend for Arch User Repository helpers such as paru and yay.
* [brew-explorer](https://github.com/cosmincatalin/brew-explorer) ⭐ 136 | 🐛 0 | 🌐 Rust | 📅 2026-05-27 - A TUI for exploring and managing your Homebrew packages with ease.
* [mirro-rs](https://github.com/rtkay123/mirro-rs) ⭐ 117 | 🐛 24 | 🌐 Rust | 📅 2026-09-15 - An Arch Linux mirrorlist manager with a TUI.
* [pacman-utils](https://github.com/ankur3-101106/pacman-utils) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-09-09 - A keyboard-driven Arch Linux system manager with pacman, AUR, and reflector tools.
* [dfdisk](https://github.com/tylerstyle/dfdisk) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - Modern forensic disk imaging, damaged media rescue and evidence management.

#### Batch, Database, and Cluster Operations

* [Yozefu](https://github.com/MAIF/yozefu/) ⭐ 345 | 🐛 6 | 🌐 Rust | 📅 2026-08-27 - A TUI for exploring data of a Kafka cluster.
* [slurmer](https://github.com/wjwei-handsome/Slurmer) ⭐ 109 | 🐛 13 | 🌐 Rust | 📅 2025-11-24 - A TUI for monitoring and managing SLURM jobs.
* [lazyslurm](https://github.com/hill/lazyslurm) ⭐ 80 | 🐛 1 | 🌐 Rust | 📅 2026-08-09 - A lazygit-style terminal UI for Slurm. Monitor jobs, tail logs, and inspect nodes and partitions.
* [sqwatch](https://github.com/fedonman/sqwatch) ⭐ 16 | 🐛 42 | 🌐 Rust | 📅 2026-09-06 - A live SLURM queue dashboard.
* [pgmon](https://github.com/nbari/pgmon) ⭐ 14 | 🐛 2 | 🌐 Rust | 📅 2026-07-01 - A TUI for monitoring PostgreSQL databases.
* [pgtui](https://codeberg.org/kdwarn/pgtui) - A PostgreSQL TUI client that uses your terminal editor for inserts and updates.

### 🔌 Hardware and Embedded

* [bluetui](https://github.com/pythops/bluetui) ⭐ 3,006 | 🐛 18 | 🌐 Rust | 📅 2026-08-28 - A TUI for managing Bluetooth devices.
* [macmon](https://github.com/vladkens/macmon) ⭐ 1,885 | 🐛 17 | 🌐 Rust | 📅 2026-08-04 - Sudoless performance monitoring for Apple Silicon processors.
* [blendr](https://github.com/dmtrKovalenko/blendr) ⭐ 495 | 🐛 6 | 🌐 Rust | 📅 2024-09-01 - A terminal UI for browsing, connecting to, and inspecting Bluetooth Low Energy devices.
* [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) ⭐ 356 | 🐛 13 | 🌐 Rust | 📅 2026-09-13 - A TUI for controlling and monitoring Framework Computers hardware.
* [pumas](https://github.com/graelo/pumas) ⭐ 220 | 🐛 4 | 🌐 Rust | 📅 2026-09-15 - Power Usage Monitor for Apple Silicon.
* [maccel](https://github.com/Gnarus-G/maccel) ⭐ 199 | 🐛 12 | 🌐 Rust | 📅 2026-08-02 - A mouse acceleration driver for Linux, and a TUI to control some parameters.
* [ComChan](https://github.com/Vaishnav-Sabari-Girish/ComChan) ⭐ 169 | 🐛 3 | 🌐 Rust | 📅 2026-09-16 - A minimal serial monitor with plotter TUI.
* [qmassa!](https://github.com/ulissesf/qmassa) ⭐ 109 | 🐛 0 | 🌐 Rust | 📅 2026-08-28 - Displays GPU devices usage stats on Linux.
* [suzui-rs](https://github.com/thatdevsherry/suzui-rs) ⭐ 107 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - A terminal viewer for Suzuki engine data over the Suzuki Serial Data Line.
* [quokka](https://github.com/dutradotdev/quokka) ⭐ 103 | 🐛 2 | 🌐 Rust | 📅 2026-07-27 - A TUI to inspect and tidy a USB-connected iPhone from macOS: storage, apps, media, syslog viewer.
* [tegratop](https://github.com/pythops/tegratop) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 - TUI monitoring tool (top like) for Nvidia jetson boards.
* [thinkfan-tui](https://github.com/karjonas/thinkfan-tui) ⭐ 78 | 🐛 1 | 🌐 Rust | 📅 2026-07-29 - A terminal-based Linux application for fan control and temperature monitoring on ThinkPad laptops.
* [napwatch](https://github.com/Tuguberk/napwatch) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-07-19 - Diagnoses and controls macOS power/battery behavior: dark wakes, Power Nap, live drain rate, and per-process power draw.
* [btlescan](https://github.com/ztroop/btlescan) ⭐ 56 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - A terminal UI for scanning Bluetooth Low Energy devices and inspecting their services and characteristics.
* [Phone-OS](https://github.com/Julien-cpsn/Phone-OS) ⭐ 45 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A modern Phone OS for ESP32 CYD (Cheap Yellow Display).
* [MTUI](https://github.com/inowattio/mtui) ⭐ 40 | 🐛 1 | 🌐 Rust | 📅 2026-09-16 - A terminal client for Modbus industrial devices.
* [Mnyaoo32](https://github.com/intuis/mnyaoo32) ⭐ 35 | 🐛 1 | 🌐 Rust | 📅 2025-05-10 - An IRC client for ESP32 devices with a Ratatui-based interface.
* [v4l-tui](https://github.com/sermuns/v4l-tui) ⭐ 31 | 🐛 5 | 🌐 Rust | 📅 2026-09-05 - Configure webcams on Linux via Video4Linux. TUI alternative to `v4l2-ctl`.
* [nightlight-tui](https://github.com/umutdinceryananer/nightlightd) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-08-22 - Dashboard for the nightlightd screen colour temperature daemon.
* [mxmon](https://github.com/yusufmo1/mxmon) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-07-25 - Sudoless Apple Silicon monitor with per-process watts, a live chassis heat map, and a JSON contract for scripts and agents.

### 🔐 Security and Identity

* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,763 | 🐛 14 | 🌐 Rust | 📅 2026-09-14 - A TUI for managing GnuPG encryption keys.
* [flawz](https://github.com/orhun/flawz) ⭐ 607 | 🐛 15 | 🌐 Rust | 📅 2026-06-13 - A TUI for browsing software vulnerabilities from the Common Vulnerabilities and Exposures (CVE) database.
* [cotp](https://github.com/replydev/cotp) ⭐ 385 | 🐛 7 | 🌐 Rust | 📅 2026-09-09 - An encrypted command-line authenticator for time- and counter-based one-time passwords.
* [jwt-ui](https://github.com/jwt-rs/jwt-ui) ⭐ 350 | 🐛 10 | 🌐 Rust | 📅 2026-05-31 - A command line UI for decoding/encoding JSON Web Tokens.
* [oak-keyring](https://github.com/OpenKeyring/oak-keyring) ⭐ 231 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - A local-first password manager that keeps vault management interactive, keyboard-driven, and in the terminal.
* [passepartui](https://github.com/kardwen/passepartui) ⭐ 128 | 🐛 3 | 🌐 Rust | 📅 2025-05-07 - A TUI for managing the pass password store.
* [chamber](https://github.com/mikeleppane/chamber) ⭐ 104 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A TUI for managing secrets.
* [YADB](https://github.com/izya4ka/yadb) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2026-02-24 - A TUI for discovering hidden directories and files on web servers.

### 📝 Productivity and Planning

#### Tasks, Projects, and Calendars

* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,127 | 🐛 132 | 🌐 Rust | 📅 2026-09-13 - TUI for the Taskwarrior command-line task manager.
* [tuxedo](https://github.com/webstonehq/tuxedo) ⭐ 1,662 | 🐛 71 | 🌐 Rust | 📅 2026-09-14 - A fast, keyboard-driven terminal UI for todo.txt.
* [mirador](https://github.com/jchultarsky/mirador) ⭐ 310 | 🐛 1 | 🌐 Rust | 📅 2026-09-15 - A personal dashboard with world clocks, calendar, weather, tasks, notes, a market watchlist and live CPU and network graphs.
* [Rust-Kanban](https://github.com/yashs662/rust_kanban) ⭐ 270 | 🐛 2 | 🌐 Rust | 📅 2025-02-13 - A kanban board for the terminal.
* [basilk](https://github.com/GabAlpha/basilk) ⭐ 215 | 🐛 11 | 🌐 Rust | 📅 2025-05-24 - A TUI to manage your tasks with minimal kanban logic.
* [kanban](https://github.com/fulsomenko/kanban) ⭐ 169 | 🐛 10 | 🌐 Rust | 📅 2026-09-15 - TUI kanban board for projects management with sprint tracking and task prioritization.
* [Jirust](https://github.com/moali87/jirust) ⭐ 160 | 🐛 6 | 🌐 Rust | 📅 2024-05-29 - A Jira TUI.
* [tatuin](https://github.com/panter-dsd/tatuin) ⭐ 139 | 🐛 18 | 🌐 Rust | 📅 2026-09-14 - A terminal task manager that aggregates tasks from multiple providers.
* [judo](https://github.com/giacomopiccinini/judo) ⭐ 119 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 - A multi-database TUI for ToDo lists.
* [vault-tasks](https://github.com/louis-thevenet/vault-tasks) ⭐ 88 | 🐛 11 | 🌐 Rust | 📅 2026-06-05 - TUI Markdown Task Manager.
* [lt](https://github.com/markmarkoh/lt) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2026-01-14 - An unofficial TUI client for Linear.app.
* [td](https://github.com/holly-hacker/td) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A graph-based TUI to-do app.
* [solverforge-calendar](https://github.com/blackopsrepl/solverforge-calendar) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2026-09-02 - A local-first TUI calendar with an AI planning inbox that schedules your to-dos into reviewable proposals, plus Google Calendar sync and .ics import.
* [todolist-rust](https://github.com/ebubekirgungor/todolist-rust) ⚠️ Archived - A terminal-based simple to-do app.
* [sc-cli](https://github.com/lnds/sc-cli) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 - A TUI for Shortcut (formerly know as Clubhouse) a project management tool for teams.
* [taskfinder](https://crates.io/crates/taskfinder) - Extract and display tasks from plain text files, hooking into your default terminal-based editor for editing.

#### Notes and Journaling

* [tui-journal](https://github.com/AmmarAbouZor/tui-journal) ⭐ 783 | 🐛 13 | 🌐 Rust | 📅 2026-09-06 - Journaling/Notes-taking terminal-based app.
* [rucola](https://github.com/Linus-Mussmaecher/rucola) ⭐ 537 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - Terminal-based markdown note manager.
* [tmmpr](https://github.com/tanciaku/tmmpr) ⭐ 349 | 🐛 3 | 🌐 Rust | 📅 2026-05-15 - Terminal mind mapper.
* [glues](https://github.com/gluesql/glues) ⭐ 284 | 🐛 16 | 🌐 Rust | 📅 2026-06-02 - A sync-enabled TUI note-taking app with Git, CSV, and JSON support.
* [kimün](https://github.com/nico2sh/kimun) ⭐ 57 | 🐛 1 | 🌐 Rust | 📅 2026-09-13 - A terminal-based Markdown note taking app that combines an interactive TUI with a scriptable CLI for automation.
* [revw](https://github.com/rlelf/revw) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-04 - A vim-like TUI for managing notes and resources.
* [quick-note](https://github.com/daniel-valencia-ts/quick-note) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-06-30 - A simple note-taking tool.

#### Finance and Markets

* [tickrs](https://github.com/tarkah/tickrs) ⭐ 1,694 | 🐛 33 | 🌐 Rust | 📅 2026-05-19 - Stock market ticker in the terminal.
* [budget-tracker-tui](https://github.com/Feromond/budget-tracker-tui) ⭐ 328 | 🐛 8 | 🌐 Rust | 📅 2026-09-16 - A fast, keyboard-driven TUI for tracking expenses, tracking investments, and analyzing your budget with ease.
* [fitui](https://github.com/ayanchavand/fitui) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-18 - A terminal-based personal finance tracker and budgeting with TUI.
* [Rex](https://github.com/TheRustyPickle/Rex) ⭐ 62 | 🐛 0 | 🌐 Rust | 📅 2026-07-04 - A TUI for managing Incomes and Expenses.
* [invoicepilot](https://github.com/adolfousier/invoicepilot) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-03-14 - A TUI for automating invoice and bank statement fetching from Gmail to Google Drive.
* [alphai-tui](https://github.com/makeev/alphai-tui) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - A stock dashboard with quotes, candlestick charts, AI-scored news and SEC Form 4 insider activity.

#### Focus, Habits, and Time

* [timr-tui](https://github.com/sectore/timr-tui) ⭐ 374 | 🐛 1 | 🌐 Rust | 📅 2026-09-01 - TUI to organize your time: Pomodoro, Countdown, Timer, Event.
* [rusty-krab-manager](https://github.com/aryakaul/rusty-krab-manager) ⭐ 328 | 🐛 11 | 🌐 Rust | 📅 2026-08-30 - A terminal time-management TUI inspired by the Pomodoro technique.
* [work-tuimer](https://github.com/Kamyil/work-tuimer) ⭐ 261 | 🐛 9 | 🌐 Rust | 📅 2026-05-18 - A TUI for easier time tracking each day, task-per-task with summaries.
* [neura-hustle-tracker](https://github.com/adolfousier/neura-hustle-tracker) ⭐ 237 | 🐛 0 | 🌐 Rust | 📅 2026-03-16 - A privacy-first TUI to track what apps you use and how long you spend on them.
* [focusd](https://github.com/bibekbhusal0/focusd) ⭐ 47 | 🐛 2 | 🌐 Rust | 📅 2026-09-01 - A terminal pomodoro timer with daemon, stats, history, streak, and nice interface.
* [sprout](https://github.com/kb019/sprout) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-09-11 - A terminal habit tracker with GitHub-style activity heatmap, streak tracking and goal management.
* [Respire](https://github.com/ElevenJune/respire) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-06-22 - A breathing app to take a break directly from your terminal.
* [void](https://github.com/p6laris/Void) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - A focus app with built-in task management, streak tracking, and customizable break schedules.
* [isw](https://gitlab.com/thom-cameron/isw) - A simple terminal stopwatch application for pomodoro etc.

### 📚 Reading and Learning

* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,595 | 🐛 36 | 🌐 Rust | 📅 2026-04-07 - Terminal-based typing test.
* [eilmeldung](https://github.com/christo-auer/eilmeldung) ⭐ 1,006 | 🐛 4 | 🌐 Rust | 📅 2026-09-12 - A TUI RSS reader based on the news\_flash library inspired by Neovim and co.
* [feedr](https://github.com/bahdotsh/feedr) ⭐ 431 | 🐛 8 | 🌐 Rust | 📅 2026-06-11 - A terminal-based RSS/Atom feed reader with a TUI.
* [ostt](https://github.com/kristoferlund/ostt) ⭐ 295 | 🐛 6 | 🌐 Rust | 📅 2026-09-15 - Open Speech-to-Text recording tool with real-time volume metering and transcription.
* [synd](https://github.com/ymgyt/syndicationd) ⭐ 154 | 🐛 10 | 🌐 Rust | 📅 2026-09-11 - A TUI feed viewer.
* [bbcli](https://github.com/hako/bbcli) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-02 - A terminal-based BBC News reader featuring a compact, numbered list interface with vim-like navigation.
* [hg-tui](https://github.com/kaixinbaba/hg-tui) ⭐ 97 | 🐛 3 | 🌐 Rust | 📅 2024-09-03 - A TUI for browsing and searching HelloGitHub's open-source project directory.
* [leetrs](https://github.com/shadowmkj/leetrs) ⭐ 89 | 🐛 8 | 🌐 Rust | 📅 2026-09-14 - A TUI for browsing, testing, and submitting LeetCode problems directly from your terminal.
* [ttypr](https://github.com/hotellogical05/ttypr) ⭐ 76 | 🐛 0 | 🌐 Rust | 📅 2026-03-21 - Terminal typing practice.
* [scriptor](https://github.com/giacomopiccinini/scriptor) ⭐ 63 | 🐛 1 | 🌐 Rust | 📅 2026-05-14 - A (medieval) local speech-to-text TUI & CLI.
* [hncli](https://github.com/pierreyoda/hncli) ⭐ 50 | 🐛 3 | 🌐 Rust | 📅 2026-09-11 - Hacker News read-only TUI.
* [kanash](https://github.com/benoitlx/kanash) ⭐ 35 | 🐛 12 | 🌐 Rust | 📅 2026-08-03 - Learn Kana in your terminal.
* [thesaurust](https://github.com/QuietPigeon2001/thesaurust) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2025-05-07 - A terminal-based dictionary app.
* [tts-tui](https://github.com/lesleyrs/tts-tui) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2024-01-26 - Text to speech app that reads from clipboard.
* [exhaust](https://github.com/heyrict/exhaust) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2020-04-18 - A terminal app for doing exams.
* [fastcards](https://github.com/indium114/fastcards) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A CLI spaced-repetition flashcard study tool.
* [rsstig](https://github.com/indium114/rsstig) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-09-11 - An unconventional terminal RSS/Atom reader.

### 🎵 Music and Media

#### Music and Audio

* [spotify-tui](https://github.com/Rigellute/spotify-tui) ⭐ 19,350 | 🐛 306 | 🌐 Rust | 📅 2024-04-04 - (Unmaintained) The original Spotify TUI; see spotatui (direct fork) or spotify-player (independent alternative).
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,216 | 🐛 154 | 🌐 Rust | 📅 2026-09-12 - An independently developed Spotify player with full feature parity.
* [spotatui](https://github.com/LargeModGames/spotatui) ⭐ 1,356 | 🐛 34 | 🌐 Rust | 📅 2026-09-15 - Spotify client with native streaming, synced lyrics, and audio visualization. A direct fork of spotify-tui with continued development and new features.
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 773 | 🐛 37 | 🌐 Rust | 📅 2025-03-03 - Listen to music from YouTube in the terminal.
* [scope-tui](https://github.com/alemidev/scope-tui) ⭐ 719 | 🐛 12 | 🌐 Rust | 📅 2026-03-01 - A terminal audio scope with waveform, vector, and frequency views.
* [Tuitar](https://github.com/orhun/tuitar) ⭐ 528 | 🐛 6 | 🌐 Rust | 📅 2025-12-23 - A portable guitar training tool.
* [NoctaVox](https://github.com/Jaxx497/noctavox) ⭐ 378 | 🐛 3 | 🌐 Rust | 📅 2026-08-22 - A lightweight, customizable TUI music player for local files.
* [asak](https://github.com/chaosprint/asak) ⭐ 371 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 - A cross-platform audio recording/playback CLI tool.
* [fum](https://github.com/qxb3/fum) ⭐ 283 | 🐛 5 | 🌐 Rust | 📅 2026-07-11 - A fully ricable tui-based music client.
* [myx](https://github.com/HaseebKhalid1507/Myx) ⭐ 224 | 🐛 9 | 🌐 Rust | 📅 2026-09-09 - Modern Spotify player for the terminal. With reactive themes.
* [glicol-cli](https://github.com/glicol/glicol-cli) ⭐ 195 | 🐛 13 | 🌐 Rust | 📅 2024-12-09 - Cross-platform music live coding in terminal.
* [chordflow](https://github.com/timvancann/chordflow) ⭐ 94 | 🐛 2 | 🌐 Rust | 📅 2026-08-27 - A tool for practicing improvisation and mastering the guitar neck.
* [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) ⭐ 94 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 - Sample-based, MIDI-controlled virtual pipe organ instrument.
* [rs-pug](https://github.com/JustRoccat/rs-pug) ⭐ 68 | 🐛 0 | 🌐 Rust | 📅 2026-08-31 - A Neovim-inspired asynchronous music player with a reactive audio visualizer.
* [roon-tui](https://github.com/TheAppgineer/roon-tui) ⭐ 64 | 🐛 5 | 🌐 Rust | 📅 2024-08-30 - Roon Remote for the terminal.
* [sparkplayer](https://github.com/dividebysandwich/sparkplayer/tree/main) ⭐ 53 | 🐛 2 | 🌐 Rust | 📅 2026-08-18 - A fun terminal based media player with album art and video support.
* [deezer-tui](https://github.com/Tatayoyoh/deezer-tui) ⭐ 49 | 🐛 2 | 🌐 Rust | 📅 2026-09-14 - Deezer music TUI with included background player.
* [O₂](https://github.com/coignard/o2) ⭐ 49 | 🐛 1 | 🌐 Rust | 📅 2026-08-12 - Rust port of the ORCΛ esoteric programming language and terminal livecoding environment.
* [serenIT](https://github.com/ElevenJune/serenIT) ⭐ 48 | 🐛 2 | 🌐 Rust | 📅 2025-11-20 - An ambient sound player directly from your terminal.
* [lrxed](https://github.com/LunaPresent/lrxed) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2025-11-02 - A TUI application for synchronizing lyrics.
* [audium](https://github.com/takashialpha/audium) ⭐ 37 | 🐛 1 | 🌐 Rust | 📅 2026-09-14 - A keyboard-driven music app for people who live in the terminal.
* [trollstov](https://github.com/hikikones/trollstov) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - A music player for the terminal where your files and their metadata are all you need.
* [bytebeat-rs](https://github.com/chaosprint/bytebeat-rs) ⭐ 30 | 🐛 1 | 🌐 Rust | 📅 2023-12-18 - A terminal tool for generating music from bytebeat expressions.
* [oosc-rs](https://github.com/karasikq/oosc-rs) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-03-04 - A terminal synthesizer that builds sounds from layered waveforms.
* [tusic](https://github.com/eminfedar/tusic) ⭐ 21 | 🐛 1 | 🌐 Rust | 📅 2026-07-15 - Lightweight TUI Music Player. Play from YouTube or \~/Music folder easily.
* [classfi](https://github.com/carmiac/classfi) ⭐ 20 | 🐛 5 | 🌐 Rust | 📅 2026-07-23 - A focused streaming music player for classical music.
* [smyx](https://github.com/ayanchavand/Smyx) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - A sleek, beautiful music player for Navidrome / OpenSubsonic with dynamic themes.
* [Youta](https://github.com/vitaly-zdanevich/youta) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - An audio player for YouTube, Yandex Music, podcasts, audiobooks, radio, and local files.
* [ytmusic-tui](https://github.com/WakaTaira/ytmusic-tui) ⭐ 6 | 🐛 11 | 🌐 Rust | 📅 2026-06-19 - A TUI client for YouTube Music with Vim-style navigation and desktop media-control integration.
* [sgram-tui](https://github.com/arian-shamaei/sgram-tui) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - A calibrated spectrogram analyzer for live mic or audio files, with labeled PNG figure export and a headless render mode.
* [m-lite](https://github.com/maxiloEmmmm/m-lite) ⚠️ Archived - An unofficial terminal client for NetEase Cloud Music.
* [angry-duiker](https://gitlab.com/fizzizist/angry-duiker-2) - A TUI for streaming music from network media servers using DLNA.

#### Books, Video, and Creative Media

* [MovieBox-TUI](https://github.com/mesamirh/MovieBox-Tui) ⭐ 1,999 | 🐛 18 | 🌐 Rust | 📅 2026-09-15 - Terminal client for discovering and downloading movies and series, with playback in mpv, VLC, or IINA.
* [bookokrat](https://github.com/bugzmanov/bookokrat) ⭐ 1,145 | 🐛 47 | 🌐 Rust | 📅 2026-09-06 - A full-featured EPUB / PDF e-book reader with Vim keybindings.
* [manga-tui](https://github.com/josueBarretogit/manga-tui) ⭐ 932 | 🐛 24 | 🌐 Rust | 📅 2026-07-13 - Terminal-based manga reader and downloader with image support.
* [managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 769 | 🐛 2 | 🌐 Rust | 📅 2026-07-06 - A TUI and CLI for managing Sonarr, Radarr, and other Servarr applications.
* [mal-cli](https://github.com/L4z3x/mal-cli) ⭐ 160 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 - A terminal client for MyAnimeList.
* [ytsub](https://github.com/sarowish/ytsub) ⭐ 90 | 🐛 2 | 🌐 Rust | 📅 2026-09-07 - A subscriptions only TUI YouTube client.
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 83 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 - Terminal presentation program with modern TUI.
* [TRNovel](https://github.com/yexiyue/TRNovel) ⭐ 66 | 🐛 2 | 🌐 Rust | 📅 2026-08-24 - A terminal novel reader for local and network novels, with AI-assisted book-source generation and TTS playback.
* [visualvault](https://github.com/mikeleppane/visualvault) ⭐ 66 | 🐛 3 | 🌐 Rust | 📅 2026-09-14 - A TUI for organizing media files.
* [lottie](https://github.com/coignard/lottie) ⚠️ Archived - A terminal screenwriting editor for the Fountain plain-text screenplay format.
* [Absotui](https://github.com/pdwaldrop/absotui) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - A fast, keyboard-driven TUI client for Audiobookshelf (self-hosted audiobook/podcast server).
* [red-table](https://github.com/volker-schukai/red-table) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-09-01 - A keyboard-driven terminal image browser for inspecting, comparing, and selecting photos.
* [readio](https://github.com/hrhrng/readio) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - A terminal ebook reader for EPUB, PDF, Markdown, and plain text with optional local text-to-speech.
* [ratslate](https://github.com/azihsoyn/ratslate) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-09-10 - An infinite-canvas whiteboard driven by the mouse.

### 🎮 Games and Entertainment

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 4,980 | 🐛 12 | 🌐 Rust | 📅 2026-09-14 - A TUI screensaver that visualizes Git commit history in your terminal.
* [GitType](https://github.com/unhappychoice/gittype) ⭐ 1,599 | 🐛 16 | 🌐 Rust | 📅 2026-09-14 - A CLI code-typing game that turns your source code into typing challenges.
* [Chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,177 | 🐛 30 | 🌐 Rust | 📅 2026-09-14 - Terminal-based Chess game.
* [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 740 | 🐛 4 | 🌐 Rust | 📅 2026-09-11 - P2P terminal game about spacepirates playing basketball across the galaxy.
* [plastic](https://github.com/Amjad50/plastic) ⭐ 583 | 🐛 20 | 🌐 Rust | 📅 2026-03-09 - NES emulator with extra ui implemented in ratatui.
* [ttysvr](https://github.com/cxreiff/ttysvr) ⭐ 489 | 🐛 4 | 🌐 Rust | 📅 2026-07-04 - Screen saver for your terminal.
* [Dealve](https://github.com/kurama/dealve-tui) ⭐ 246 | 🐛 5 | 🌐 Rust | 📅 2026-05-08 - Browse game deals across Steam, GOG, Humble Bundle, Epic Games, and more from your terminal.
* [minesweep](https://github.com/cpcloud/minesweep-rs) ⚠️ Archived - Terminal-based Minesweeper game.
* [poketex](https://github.com/ckaznable/poketex) ⭐ 218 | 🐛 1 | 🌐 Rust | 📅 2026-05-05 - Simple Pokedex based on TUI.
* [theattyr](https://github.com/orhun/theattyr) ⭐ 172 | 🐛 1 | 🌐 Rust | 📅 2024-10-26 - A terminal theater for playing VT100 text art and animations.
* [mlbt](https://github.com/mlb-rs/mlbt) ⭐ 162 | 🐛 0 | 🌐 Rust | 📅 2026-09-06 - A tui for the MLB Statcast API. Watch a live game using Gameday, or check scores, standings, and stats.
* [ssHattrick](https://github.com/ricott1/sshattrick) ⭐ 146 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 - A multiplayer terminal version of the Hattrick football-management game, playable over SSH.
* [Inertia](https://github.com/aclfe/inertia) ⭐ 116 | 🐛 1 | 🌐 Rust | 📅 2026-07-19 - A 3D physics simulator in your terminal.
* [private\_poker](https://github.com/theOGognf/private_poker) ⭐ 104 | 🐛 0 | 🌐 Rust | 📅 2026-07-13 - A poker library, server, client, and TUI.
* [Battleship.rs](https://github.com/deepu105/battleship-rs) ⭐ 97 | 🐛 4 | 🌐 Rust | 📅 2024-10-16 - Terminal-based Battleship game.
* [confetty\_rs](https://github.com/Handfish/confetty_rs) ⭐ 88 | 🐛 1 | 🌐 Rust | 📅 2024-02-08 - Particle system (fireworks, stars) rendered in the terminal.
* [astray](https://github.com/Vinermy/astray) ⭐ 87 | 🐛 9 | 🌐 Rust | 📅 2024-08-16 - TUI-based space strategy game.
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 83 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 - Beautiful visualizations of common maze building and graph searching algorithms.
* [sharad-ratatui](https://github.com/ProHaller/sharad_ratatui) ⭐ 67 | 🐛 2 | 🌐 Rust | 📅 2025-07-06 - A text-based Shadowrun role-playing game.
* [crosstui](https://github.com/matrixfrog/crossword) ⭐ 53 | 🐛 12 | 🌐 Rust | 📅 2025-07-31 - Terminal-based crossword puzzle player.
* [tage](https://github.com/jacopograndi/tage) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2024-08-13 - Turn based strategy game with multiplayer, empires and warfare.
* [Snake](https://github.com/kriskw1999/ratatui-snake) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2025-03-16 - Simple terminal based snake game.
* [sxtetris](https://github.com/shixinhuang99/sxtetris) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2025-08-26 - A terminal Tetris game.
* [wordl](https://github.com/palerdot/wordl-rs) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2024-03-16 - Terminal-based Wordle game. Web like experience with keyboard hints and guess reveal animations.
* [cube timer](https://github.com/paarthmadan/cube) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2021-09-12 - A tui for cube timing, written in Rust.
* [rust-sadari-cli](https://github.com/24seconds/rust-sadari-cli) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2020-05-11 - Rust sadari game based on terminal! (Ghost leg or Amidakuji in another words).
* [terminal.pong](https://github.com/IshmamR/terminal.pong) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 - Terminal based ping pong game.
* [modder-rs](https://github.com/JayanAXHF/modder-rs) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2025-09-20 - A practical TUI to manage and install mods for Minecraft.
* [chessterm](https://github.com/ronaldsuwandi/chessterm) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2025-02-05 - A Rust-powered chess engine in a terminal.
* [termfarm](https://github.com/indium114/termfarm) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-09-10 - A simple idle farming game.
* [oxycards](https://github.com/BrookJeynes/oxycards) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-08-01 - Quiz card application built within the terminal.
* [tic-tac-toe](https://github.com/thomas-mauran/tic-tac-toe) ⭐ 18 | 🐛 2 | 🌐 Rust | 📅 2024-10-29 - Terminal-based tic tac toe game.
* [flip7](https://github.com/ilyichv/flip7) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-04-13 - Terminal-based Flip7 game.
* [WOPR TUI 2026](https://github.com/ankurCES/WOPR_TUI_2026) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A WarGames-inspired Cold War simulation TUI with AI-powered scenarios, DEFCON escalation, and multi-language intelligence intercepts.
* [cgol-tui](https://github.com/jeromeschmied/cgol-tui-rs) ⭐ 13 | 🐛 3 | 🌐 Rust | 📅 2026-09-02 - Conway's Game of Life viewer with a TUI in Rust.
* [game-of-life-rs](https://github.com/kachark/game-of-life-rs) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2021-04-08 - Conway's Game of Life implemented in Rust and visualized with tui-rs.
* [a-puzzle-a-day](https://github.com/mrbjarksen/a-puzzle-a-day) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2024-03-15 - Generate and browse all solutions to A-Puzzle-A-Day.
* [sued-rs](https://github.com/Danilo-Guedes/sued-rs) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-13 - A horror-themed recreation of SueD, the 2000s Brazilian prank oracle.
* [tetris-tui](https://github.com/Axyl1410/tetris-tui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - Terminal Tetris following the Tetris Guideline.
* [Blackjack](https://github.com/skharchikov/blackjack) ⭐ 6 | 🐛 13 | 🌐 Rust | 📅 2026-08-17 - Multiplayer Blackjack with a WebSocket server and a terminal client.
* [bigbrainwordle](https://github.com/kloki/bigbrainwordle) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2026-02-28 - A tool to help you cheat with the daily wordle.
* [Connect-four](https://github.com/jesper-olsen/connect-four) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-07-20 - Connect-four; interactive game + perfect solver.
* [enimtui](https://codeberg.org/tranzystorekk/enimtui) - Terminal-based minesweeper knockoff.
* [Thardians](https://gitlab.com/thustle/thardians-rs) - Space Invaders for the terminal.

### 🔬 Science, Math, and Exploration

* [tgv](https://github.com/zeqianli/tgv) ⭐ 483 | 🐛 13 | 🌐 Rust | 📅 2026-09-07 - A terminal genome browser with Vim-style navigation.
* [tracker](https://github.com/ShenMian/tracker) ⭐ 316 | 🐛 1 | 🌐 Rust | 📅 2026-07-05 - A terminal-based real-time satellite tracking and orbit prediction application.
* [numr](https://github.com/nasedkinpv/numr) ⭐ 266 | 🐛 3 | 🌐 Rust | 📅 2026-07-14 - A natural language calculator with unit/currency conversions and vim-style keybindings.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 173 | 🐛 2 | 🌐 Rust | 📅 2025-09-17 - A free, simple weather TUI that pulls data without the need for an API key, account, or subscription.
* [tenki](https://github.com/ckaznable/tenki) ⭐ 171 | 🐛 0 | 🌐 Rust | 📅 2026-07-23 - A tty-clock with weather effect.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 92 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [fractouille](https://github.com/PottierLoic/Fractouille) ⭐ 89 | 🐛 2 | 🌐 Rust | 📅 2026-03-19 - A simple fractal explorer running in your terminal.
* [lpl](https://github.com/SOF3/lpl) ⭐ 55 | 🐛 10 | 🌐 Rust | 📅 2025-04-05 - Command-line plotting for real-time CSV and JSON streams.
* [SeqTUI](https://github.com/ranwez-search/SeqTUI) ⭐ 47 | 🐛 0 | 🌐 Rust | 📅 2026-03-10 - A terminal-based viewer and command-line toolkit for molecular sequences.
* [meteo-tui](https://github.com/16arpi/meteo-tui) ⭐ 42 | 🐛 2 | 🌐 Rust | 📅 2026-07-21 - French weather app in the command line.
* [seqsizzle](https://github.com/ChangqingW/SeqSizzle) ⭐ 27 | 🐛 1 | 🌐 Rust | 📅 2026-08-04 - A terminal pager for viewing and searching FASTA and FASTQ DNA sequence files.
* [rsfrac](https://github.com/SkwalExe/rsfrac) ⭐ 22 | 🐛 3 | 🌐 Rust | 📅 2026-04-23 - Terminal based fractal explorer, including Mandelbrot, Burning Ship, and Julia.
* [termCA](https://github.com/fabiooo4/termCA) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-03-03 - Interactive TUI Cellular Automata simulator.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-16._
