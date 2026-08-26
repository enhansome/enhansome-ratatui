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
  * [🕹️ Games and Entertainment](#%EF%B8%8F-games-and-entertainment)
  * [🚀 Productivity and Utilities](#-productivity-and-utilities)
  * [🎼 Music and Media](#-music-and-media)
  * [🌐 Networking and Internet](#-networking-and-internet)
  * [👨‍💻 System Administration](#-system-administration)
  * [📟 Embedded](#-embedded)
  * [🌌 Other](#-other)

Aside from those listed here, many other apps and libraries can be easily be found via the reverse dependencies on crates.io and GitHub:

* <https://github.com/ratatui/ratatui/network/dependents> ⭐ 22,389 | 🐛 217 | 🌐 Rust | 📅 2026-08-24
* <https://github.com/fdehau/tui-rs/network/dependents?package_id=UGFja2FnZS0zMjE3MzkzMDMx> ⚠️ Archived
* <https://crates.io/crates/ratatui/reverse_dependencies>
* <https://crates.io/crates/tui/reverse_dependencies>

## 📦 Libraries

### 🏗️ Frameworks

* [ratzilla](https://github.com/orhun/ratzilla) ⭐ 1,433 | 🐛 49 | 🌐 Rust | 📅 2026-07-04 - Build terminal-themed web applications with Ratatui and WebAssembly.
* [mousefood](https://github.com/j-g00da/mousefood) ⭐ 1,316 | 🐛 22 | 🌐 Rust | 📅 2026-08-24 - An embedded-graphics backend for Ratatui.
* [bevy\_ratatui\_camera](https://github.com/cxreiff/bevy_ratatui_camera) ⭐ 338 | 🐛 2 | 🌐 Rust | 📅 2025-11-17 - A bevy plugin for rendering your bevy app to the terminal using ratatui.
* [egui-ratatui](https://github.com/gold-silver-copper/egui_ratatui) ⭐ 206 | 🐛 4 | 🌐 Rust | 📅 2026-04-16 - A ratatui backend that is also an egui widget. Deploy on web with WebAssembly or ship natively with bevy, macroquad, or eframe.
* [ratatuefi](https://github.com/sermuns/ratatuefi) ⭐ 164 | 🐛 0 | 🌐 Rust | 📅 2026-07-06 - Another library providing a ratatui backend for UEFI environments.
* [ratatui-wgpu](https://github.com/Jesterhearts/ratatui-wgpu) ⭐ 130 | 🐛 5 | 🌐 Rust | 📅 2026-08-06 - A wgpu based rendering backend for ratatui.
* [webatui](https://github.com/TylerBloom/webatui) ⭐ 128 | 🐛 4 | 🌐 Rust | 📅 2024-09-30 - An integration between the Yew and Ratatui crates for making TUI-themed WebAssembly webapps.
* [soft\_ratatui](https://github.com/gold-silver-copper/soft_ratatui) ⭐ 105 | 🐛 0 | 🌐 Rust | 📅 2026-04-23 - A software rendering backend for ratatui. No GPU required. TUI everywhere.
* [ratatui-uefi](https://github.com/reubeno/tui-uefi) ⭐ 100 | 🐛 3 | 🌐 Rust | 📅 2026-07-20 - A ratatui backend for use in UEFI environments.
* [schemaui](https://github.com/YuniqueUnic/schemaui) ⭐ 89 | 🐛 4 | 🌐 Rust | 📅 2026-08-24 - Turn JSON Schemas into TUIs and web UIs with real-time validation.
* [rat-salsa](https://github.com/thscharler/rat-salsa) ⭐ 64 | 🐛 5 | 🌐 Rust | 📅 2026-07-03 - An event-queue for ratatui with tasks, timers, application events, focus handling, dialog windows.
* [raclettui](https://github.com/ishrut/raclettui) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-07-29 - A wayland layer shell window implementing the ratatui backend with cpu and wgpu rendering.
* [ratatui-kit](https://github.com/yexiyue/ratatui-kit) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-07-16 - A React-style component framework for Ratatui with hooks, routing, async state, input layers, and reusable components.
* [crepuscularity](https://github.com/tschk/crepuscularity) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2026-08-22 - One UI codebase for desktop, web, mobile, terminal, browser extensions, and embedded devices. Write React JSX or our lightweight DSL, get GPUI, Ratatui, SwiftUI, LVGL, and more. Batteries included.
* [dumo](https://github.com/iddey/dumo) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 - An embedded-graphics backend that is built on [mplusfonts](https://github.com/iddey/mplusfonts) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 and has kanji support.
* [ratatui-minecraft](https://github.com/janTatesa/ratatui-minecraft) ⭐ 16 | 🐛 1 | 🌐 Rust | 📅 2025-06-24 - A ratatui backend that uses [valence-screens](https://github.com/White-145/valence-screens) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-20
* [xnano](https://github.com/hsaeed3/xnano) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-08-20 - A declarative terminal framework for Python built on ratatui & ratzilla.
* [rlt](https://crates.io/crates/rlt) - A universal load testing framework for Rust, with real-time tui support.
* [tui-react](https://crates.io/crates/tui-react) - TUI widgets using a react-like paradigm.
* [tui-realm](https://crates.io/crates/tuirealm) - A ratatui framework inspired by Elm and React.
* [widgetui](https://crates.io/crates/widgetui) - A bevy-like widget system for ratatui and crossterm.

### 🧩 Widgets

* [edtui](https://github.com/preiter93/edtui) ⭐ 153 | 🐛 3 | 🌐 Rust | 📅 2026-08-16 - A TUI based vim-inspired editor widget for ratatui.
* [ratatui-splash-screen](https://github.com/orhun/ratatui-splash-screen) ⭐ 149 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 - A widget to turn any image to a splash screen.
* [ratatui-code-editor](https://github.com/vipmax/ratatui-code-editor) ⭐ 114 | 🐛 6 | 🌐 Rust | 📅 2026-07-07 - A code editor widget for ratatui, syntax highlighting powered by tree-sitter.
* [ratatui-explorer](https://github.com/tatounee/ratatui-explorer) ⭐ 92 | 🐛 3 | 🌐 Rust | 📅 2026-03-06 - A simple library for creating file explorer for ratatui.
* [tui-rain](https://github.com/levilutz/tui-rain) ⭐ 79 | 🐛 4 | 🌐 Rust | 📅 2024-11-30 - A widget to generate various rain effects.
* [tui-menu](https://github.com/shuoli84/tui-menu) ⭐ 55 | 🐛 2 | 🌐 Rust | 📅 2025-12-30 - A menu widget for ratatui ecosystem.
* [ratatui-markdown](https://github.com/celestia-island/ratatui-markdown) ⭐ 42 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A Rust library providing markdown rendering, Mermaid diagrams, syntax highlighting, collapsible JSON/TOML tree views, and a rich hybrid scroll system.
* [term-rustdoc](https://github.com/zjp-CN/term-rustdoc) ⭐ 34 | 🐛 16 | 🌐 Rust | 📅 2025-04-20 - A TUI for Rust docs that aims to improve the UX on tree view and generic code.
* [tui-popup](https://github.com/joshka/tui-popup) ⚠️ Archived - A Popup widget for Ratatui.
* [tui-shimmer](https://github.com/vinhnx/tui-shimmer) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2026-06-06 - Shimmer text effect for Ratatui.
* [tui-globe](https://github.com/d10n/tui-globe) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 - A 3D globe widget rendered with braille.
* [ratatui-stacked-bar](https://github.com/zeqianli/ratatui-stacked-bar) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-04-07 - A stacked area chart widget for ratatui.
* [ratatui-wireframe](https://crates.io/crates/ratatui-wireframe) -  A widget for rendering and rotating 3D wireframe models.
* [hyperrat](https://crates.io/crates/hyperrat) - An OSC 8 link widget for ratatui.
* [malevich](https://crates.io/crates/malevich) - A plotting widget: line, scatter, bar, histogram, heatmap, box plot, violin, and more, with automatic axes and millions of points.
* [ratatui-comfy-tabs](https://crates.io/crates/ratatui-comfy-tabs) - A feature-rich tab navigation for TUI. Highly customizable.
* [ratatui-comfy-toaster](https://crates.io/crates/ratatui-comfy-toaster) - An advanced toast notification engine for Ratatui terminal UI applications.
* [ratatui-image](https://crates.io/crates/ratatui-image) - An image widget for ratatui, supporting sixels and unicode-halfblocks.
* [ratatui-fretboard](https://crates.io/crates/ratatui-fretboard) - A widget for displaying musical note positions on a fretboard.
* [ratatui-textarea](https://crates.io/crates/ratatui-textarea) - A simple yet powerful editor widget for ratatui. Fork of `tui-textarea`.
* [ratatui-toaster](https://crates.io/crates/ratatui-toaster) - An extremely lightweight toast engine for ratatui.
* [ratatui-cheese](https://crates.io/crates/ratatui-cheese) - Bubbletea-inspired widgets for ratatui, including spinner, help, tree, paginator and list.
* [throbber-widgets-tui](https://crates.io/crates/throbber-widgets-tui) - A widget that displays throbber.
* [tui-additions](https://crates.io/crates/tui-additions) - Additions to the rust tui crate.
* [tui-big-text](https://crates.io/crates/tui-big-text) - A simple ratatui widget for displaying big text using the `font8x8` crate.
* [tui-dialog](https://docs.rs/tui-dialog) - A widget for entering a single line of text in a dialog.
* [tui-logger](https://crates.io/crates/tui-logger) - Logger with smart widget for ratatui.
* [tui-nodes](https://crates.io/crates/tui-nodes) - Node graph visualization.
* [tui-overlay](https://crates.io/crates/tui-overlay) - A composable overlay widget with drawers, modals, popovers, and toasts from a single configurable primitive.
* [tui-prompts](https://crates.io/crates/tui-prompts) - A library for building interactive prompts for ratatui.
* [tui-scrollview](https://crates.io/crates/tui-scrollview) - A container that provides a scrolling view at a larger area.
* [tui-skeleton](https://crates.io/crates/tui-skeleton) - A library of placeholder widgets that pulse, sweep, or shimmer while your content loads.
* [tui-tabs](https://crates.io/crates/tui-tabs) - A tab navigation widget with individually bordered boxes and rounded corners.
* [tui-term](https://crates.io/crates/tui-term) - A pseudoterminal widget for ratatui.
* [tui-textarea](https://crates.io/crates/tui-textarea) - A simple yet powerful text editor widget for ratatui and tui-rs.
* [tui-tree-widget](https://crates.io/crates/tui-tree-widget) - Tree widget for ratatui.
* [tui-widget-list](https://crates.io/crates/tui-widget-list) - A versatile list implementation for ratatui.
* [tui-checkbox](https://crates.io/crates/tui-checkbox) - A customizable checkbox widget for ratatui.
* [tui-piechart](https://crates.io/crates/tui-piechart) - A configurable, colorful piechart widget that comes in standard and high resolution.
* [rat-widget](https://crates.io/crates/rat-widget) - Widgets for data-input (text-input, date- and number-input, text-area, checkbox, choice, radiobutton, slider, calendar), structural widgets (view, split, tabbed, multi-page), a table widget for large data-sets, a file-dialog, a menubar+sub-menus, a status-bar and some more. With builtin crossterm event-handling and focus-handling.
* [tui-slider](https://crates.io/crates/tui-slider) - A highly customizable slider widget for both horizontal and vertical orientations.

### 🔧 Utilities

* [tachyonfx](https://github.com/junkdog/tachyonfx) ⭐ 1,289 | 🐛 7 | 🌐 Rust | 📅 2026-07-19 - A shader-like effects library for ratatui.
* [bevy\_ratatui](https://github.com/joshka/bevy_ratatui) ⭐ 165 | 🐛 9 | 🌐 Rust | 📅 2026-08-18 - A Rust crate to use Ratatui in a Bevy App.
* [ratatui-garnish](https://github.com/franklaranja/ratatui-garnish) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2025-10-14 - A powerful composition system for Ratatui widgets.
* [ratatui-interact](https://github.com/Brainwires/ratatui-interact) ⭐ 36 | 🐛 1 | 🌐 Rust | 📅 2026-04-02 - Interactive TUI components for Ratatui with focus management and mouse support.
* [ratatui-macros](https://github.com/kdheepak/ratatui-macros) ⚠️ Archived - Macros for simplifying boilerplate for creating UI using Ratatui.
* [coolor](https://github.com/Canop/coolor) ⭐ 33 | 🐛 2 | 🌐 Rust | 📅 2025-05-09 - Tiny color conversion library for TUI application builders.
* [termprofile](https://github.com/aschey/termprofile) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-08-21 - Detect and handle terminal color/styling support. Supports converting Ratatui color and style objects.
* [tui-syntax-highlight](https://github.com/aschey/tui-syntax-highlight) ⭐ 31 | 🐛 1 | 🌐 Rust | 📅 2026-08-23 - Syntax highlighting for code blocks.
* [ggsci-ratatui](https://github.com/nanxstats/ggsci-rs) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-07-31 - Scientific and sci-fi color palettes from ggsci as Ratatui colors and styles, in truecolor or ANSI-256 mode.
* [ansi-to-tui](https://crates.io/crates/ansi-to-tui) - A library to convert ansi color coded text into `ratatui::text::Text`.
* [color-to-tui](https://crates.io/crates/color-to-tui) - Parse colors and convert them to `ratatui::style::Colors`.
* [opaline](https://crates.io/crates/opaline) - Token-based theme engine for Ratatui with gradients, 20 builtin themes, user theme discovery, and a reusable theme selector widget.
* [ratatui-input-manager](https://crates.io/ratatui-input-manager) - A macro for creating declarative update handlers in Elm style apps, supporting crossterm, termion and termwiz.
* [terminput](https://crates.io/crates/terminput) - An abstraction over various backends that provide input events.
* [tui-input](https://crates.io/crates/tui-input) - A headless input library for TUI apps.
* [tui-pantry](https://crates.io/crates/tui-pantry) - Component-driven development tool for ratatui widgets, similar to Storybook.

### 🔗 Bindings

* [pyratatui](https://github.com/pyratatui/pyratatui) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-06-05 - Python bindings to ratatui, powered by Maturin and PyO3.
* [ex\_ratatui](https://github.com/mcass19/ex_ratatui) ⭐ 112 | 🐛 1 | 🌐 Elixir | 📅 2026-08-25 - Elixir bindings for ratatui.
* [ratatui-ffi](https://github.com/holo-q/ratatui-ffi) ⭐ 53 | 🐛 2 | 🌐 Rust | 📅 2026-06-04 - FFI bindings for ratatui.
* [ratatui-py](https://github.com/holo-q/ratatui-py) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-06-04 - Python bindings for ratatui.
* [Ratatui.cs](https://github.com/holo-q/Ratatui.cs) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2026-06-04 - C# bindings for ratatui.
* [ratatui-ts](https://github.com/holo-q/ratatui-ts) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - TypeScript bindings for ratatui.
* [ratatui-go](https://github.com/holo-q/ratatui-go) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-09-12 - Go bindings for ratatui.
* [ratatui\_ruby](https://sr.ht/~kerrick/ratatui_ruby/) - Ruby bindings for ratatui.

## 💻 Apps

### ⌨️ Development Tools

* [Yazi](https://github.com/sxyazi/yazi) ⭐ 41,685 | 🐛 66 | 🌐 Rust | 📅 2026-08-25 - Blazing fast terminal file manager written in Rust, based on async I/O.
* [gitui](https://github.com/extrawurst/gitui) ⭐ 22,432 | 🐛 342 | 🌐 Rust | 📅 2026-08-04 - Terminal UI for Git.
* [burn](https://github.com/burn-rs/burn) ⭐ 15,816 | 🐛 306 | 🌐 Rust | 📅 2026-08-25 - Comprehensive Deep Learning framework in Rust.
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,292 | 🐛 14 | 🌐 Rust | 📅 2026-08-25 - A database management TUI for Postgres.
* [joshuto](https://github.com/kamiyaa/joshuto) ⭐ 3,723 | 🐛 103 | 🌐 Rust | 📅 2026-08-20 - Ranger-like terminal file manager written in Rust.
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,703 | 🐛 20 | 🌐 Rust | 📅 2026-08-23 - A feature-full TUI API client for your terminal.
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,317 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 - Cross-platform TUI database management tool.
* [wrkflw](https://github.com/bahdotsh/wrkflw) ⭐ 3,304 | 🐛 11 | 🌐 Rust | 📅 2026-07-03 - A TUI for validating and executing GitHub Actions workflows locally.
* [gitu](https://github.com/altsem/gitu) ⭐ 2,891 | 🐛 61 | 🌐 Rust | 📅 2026-08-22 - A TUI Git client inspired by Magit.
* [serie](https://github.com/lusingander/serie) ⭐ 2,051 | 🐛 22 | 🌐 Rust | 📅 2026-08-21 - A rich Git commit graph in your terminal.
* [BitFun](https://github.com/GCWing/BitFun) ⭐ 1,818 | 🐛 127 | 🌐 Rust | 📅 2026-08-26 - An AI coding agent.
* [Stakpak](https://github.com/stakpak/agent) ⭐ 1,751 | 🐛 39 | 🌐 Rust | 📅 2026-07-06 - AI DevOps agent to help you secure, deploy, and maintain production-ready infrastructure.
* [BugStalker](https://github.com/godzie44/BugStalker) ⭐ 1,374 | 🐛 15 | 🌐 Rust | 📅 2026-08-22 - Modern rust debugger for Linux x86-64.
* [openapi-tui](https://github.com/zaghaghi/openapi-tui) ⭐ 1,309 | 🐛 10 | 🌐 Rust | 📅 2026-05-14 - Terminal UI to list, browse and run APIs defined with openapi spec.
* [scooter](https://github.com/thomasschafer/scooter) ⭐ 1,291 | 🐛 19 | 🌐 Rust | 📅 2026-08-22 - Interactive find and replace in the terminal.
* [slumber](https://github.com/LucasPickering/slumber) ⭐ 1,219 | 🐛 9 | 🌐 Rust | 📅 2026-07-04 - Terminal-based HTTP/REST client.
* [desed](https://github.com/SoptikHa2/desed) ⭐ 1,215 | 🐛 7 | 🌐 Rust | 📅 2026-05-16 - Debugging tool for sed scripts.
* [lazyjj](https://github.com/Cretezy/lazyjj) ⭐ 1,199 | 🐛 46 | 🌐 Rust | 📅 2026-03-02 - TUI for the Jujutsu/jj VCS.
* [opencrabs](https://github.com/adolfousier/opencrabs) ⭐ 911 | 🐛 7 | 🌐 Rust | 📅 2026-08-25 - Open-claw inspired orchestration layer for software development.
* [Serpl](https://github.com/yassinebridi/serpl) ⭐ 856 | 🐛 21 | 🌐 Rust | 📅 2026-05-31 - A simple terminal UI for search and replace, ala VS Code.
* [VT Code](https://github.com/vinhnx/vtcode) ⭐ 823 | 🐛 1 | 🌐 Rust | 📅 2026-08-25 - A Semantic Coding Agent.
* [Oatmeal](https://github.com/dustinblackman/oatmeal) ⭐ 770 | 🐛 31 | 🌐 Rust | 📅 2024-06-01 - Terminal UI to chat with large language models (LLM) using different model backends, and integrations with your favourite editors!
* [Maelstrom](https://github.com/maelstrom-software/maelstrom) ⭐ 733 | 🐛 190 | 🌐 Rust | 📅 2025-04-23 - A fast test runner that runs every test in its own container locally or distributed.
* [tenere](https://github.com/pythops/tenere) ⭐ 680 | 🐛 10 | 🌐 Rust | 📅 2026-05-10 - TUI interface for LLMs written in Rust.
* [patent](https://github.com/r14dd/patent) ⭐ 524 | 🐛 7 | 🌐 Rust | 📅 2026-08-24 - A prior-art search for devtool ideas.
  LLM verdict.
* [repgrep](https://github.com/acheronfail/repgrep) ⭐ 524 | 🐛 12 | 🌐 Rust | 📅 2025-06-18 - An interactive replacer for ripgrep that makes it easy to find and replace across files on the command line.
* [pixtuoid](https://github.com/IvanWng97/pixtuoid) ⭐ 453 | 🐛 11 | 🌐 Rust | 📅 2026-08-25 - Live pixel-art office for AI coding agents.
* [tracexec](https://github.com/kxxt/tracexec) ⭐ 437 | 🐛 27 | 🌐 Rust | 📅 2026-08-26 - Tracer for execve{,at} and pre-exec behavior, launcher for debuggers.
* [Yozefu](https://github.com/MAIF/yozefu/) ⭐ 344 | 🐛 17 | 🌐 Rust | 📅 2026-08-18 - A TUI for exploring data of a Kafka cluster.
* [giff](https://github.com/bahdotsh/giff) ⭐ 271 | 🐛 8 | 🌐 Rust | 📅 2026-04-23 - A TUI for Git diffs with interactive rebase support.
* [sabiql](https://github.com/riii111/sabiql) ⭐ 257 | 🐛 7 | 🌐 Rust | 📅 2026-08-25 - A fast, driver-less TUI for browsing, querying, and editing PostgreSQL databases with vim-like keybindings.
* [glim](https://github.com/junkdog/glim) ⭐ 234 | 🐛 16 | 🌐 Rust | 📅 2025-10-13 - Monitor GitLab CI/CD pipelines and projects with style.
* [Livediff](https://github.com/SoCkEt7/Livediff) ⭐ 229 | 🐛 5 | 🌐 Rust | 📅 2026-08-23 - Real-time terminal file diff monitoring TUI.
* [FileSSH](https://github.com/JayanAXHF/filessh) ⭐ 228 | 🐛 3 | 🌐 Rust | 📅 2026-07-25 - A TUI-based file explorer for remote servers.
* [deadbranch](https://github.com/armgabrielyan/deadbranch) ⭐ 227 | 🐛 2 | 🌐 Rust | 📅 2026-03-30 - A TUI for cleaning stale Git branches safely.
* [TermiRs](https://github.com/caelansar/termirs) ⭐ 222 | 🐛 1 | 🌐 Rust | 📅 2026-06-08 - A modern, async SSH terminal client.
* [drydock](https://github.com/yetidevworks/drydock) ⭐ 216 | 🐛 1 | 🌐 Rust | 📅 2026-08-21 - A live dashboard for a fleet of Git repos, showing what's uncommitted, unpushed, and unreleased across all of them.
* [llmtrim](https://github.com/fkiene/llmtrim) ⭐ 216 | 🐛 8 | 🌐 Rust | 📅 2026-08-17 - Local proxy that compresses LLM API requests to cut token cost, with a tabbed status dashboard for per-source cost and context use.
* [claudectl](https://github.com/mercurialsolo/claudectl) ⭐ 197 | 🐛 63 | 🌐 Rust | 📅 2026-07-10 - Mission control for multiple Claude Code sessions with live dashboard, cost tracking, and budget enforcement.
* [toktop](https://github.com/htin1/toktop) ⭐ 172 | 🐛 5 | 🌐 Rust | 📅 2025-12-07 - A LLM usage monitor in terminal.
* [gwm](https://github.com/kbrdn1/gwm-cli) ⭐ 133 | 🐛 32 | 🌐 Rust | 📅 2026-08-25 - A Git worktree manager: CLI and TUI in one binary, native libgit2, per-repo declarative bootstrap, and AI agent session tracking.
* [ratifact](https://github.com/adolfousier/ratifact) ⭐ 89 | 🐛 1 | 🌐 Rust | 📅 2025-11-28 - Track and manage build artifacts from multiple programming languages.
* [rat-commander](https://github.com/dividebysandwich/rat-commander) ⭐ 87 | 🐛 1 | 🌐 Rust | 📅 2026-07-27 - A fully-featured modern spiritual successor to Midnight-Commander with truecolor support and built-in process- and disk-explorer.
* [cargo-selector](https://github.com/lusingander/cargo-selector) ⭐ 73 | 🐛 1 | 🌐 Rust | 📅 2026-08-04 - Cargo subcommand to select and execute binary/example targets.
* [nomad](https://github.com/JosephLai241/nomad) ⭐ 72 | 🐛 9 | 🌐 Rust | 📅 2023-05-10 - Customizable next-gen tree command with Git integration and TUI.
* [tongo](https://github.com/drewzemke/tongo) ⭐ 72 | 🐛 2 | 🌐 Rust | 📅 2026-08-23 - A TUI for MongoDB.
* [git-time-machine](https://github.com/dinakars777/git-time-machine) ⭐ 69 | 🐛 2 | 🌐 Rust | 📅 2026-05-31 - Visual Git reflog TUI for undoing Git mistakes.
* [nereid](https://github.com/bnomei/nereid) ⭐ 63 | 🐛 0 | 🌐 Rust | 📅 2026-07-11 - Create and explore Mermaid diagrams in collaboration with AI agents (TUI + MCP Server).
* [opencode stats](https://github.com/Cateds/opencode-stats) ⭐ 62 | 🐛 2 | 🌐 Rust | 📅 2026-08-04 - A terminal dashboard for OpenCode usage statistics and cost breakdowns.
* [Martty](https://github.com/openma-ai/Martty) ⭐ 60 | 🐛 2 | 🌐 Rust | 📅 2026-08-26 - An extensible Rust/ratatui terminal client for DeepSeek Harness and ACP-compatible coding agents, with plugins, tools, subagents, and durable sessions.
* [ygrep](https://github.com/yetidevworks/ygrep) ⭐ 57 | 🐛 1 | 🌐 Rust | 📅 2026-07-30 - A fast, local, indexed code search tool with a TUI, optimized for AI coding assistants and powered by Tantivy full-text indexing.
* [gimoji](https://github.com/zeenix/gimoji) ⭐ 52 | 🐛 7 | 🌐 Rust | 📅 2026-08-23 - Makes it easy to add emojis to your Git commit messages.
* [thurbox](https://github.com/Thurbeen/thurbox) ⭐ 48 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - A TUI orchestrator for running multiple AI coding agents (Claude Code, Codex, and others) in persistent tmux sessions.
* [commandOK](https://github.com/64bit/commandOK) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2026-06-16 - Spotlight-like command generator for your terminal, supports leading LLM providers.
* [image-auditor](https://github.com/0franco/image-auditor) ⭐ 44 | 🐛 0 | 🌐 Rust | 📅 2026-07-05 - Find & fix Lighthouse image issues (CLS, lazy loading, WebP, srcset) across your codebase.
* [bosun](https://github.com/yetidevworks/bosun) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2026-08-24 - A tmux-native TUI for orchestrating AI coding agent sessions (Claude Code, Codex) with live previews and per-session state.
* [SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) ⭐ 39 | 🐛 2 | 🌐 Rust | 📅 2026-08-20 - Lightning fast terminal native agent harness with tools, extensions and subagents. 15MB, 2ms boot.
* [deputui](https://github.com/twiddler/deputui) ⭐ 36 | 🐛 4 | 🌐 Rust | 📅 2026-08-17 - Review and install NPM package updates.
* [lingora-tui](https://github.com/nigeleke/lingora) ⭐ 35 | 🐛 2 | 🌐 Rust | 📅 2026-08-19 - Browse, compare and validate Fluent i18n files.
* [material](https://github.com/azorng/material) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-08-14 - A material design color palette for the terminal.
* [crmux](https://github.com/maedana/crmux) ⭐ 27 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A TUI viewer for monitoring and managing multiple Claude Code sessions in tmux.
* [amtr](https://github.com/arian-shamaei/anthropometer) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - A btop-style TUI that renders a Claude Code session's live context window as a memory map, with tool and file traffic, cache economics, and a compiled PDF report.
* [blippy](https://github.com/AksharP5/blippy) ⭐ 25 | 🐛 1 | 🌐 Rust | 📅 2026-08-19 - A keyboard-first TUI for GitHub issues and pull requests.
* [TaskUI](https://github.com/thmshmm/taskui) ⭐ 24 | 🐛 1 | 🌐 Rust | 📅 2024-08-11 - Simple Terminal UI for Task / taskfile.dev.
* [Gitside](https://github.com/dev-bhaskar8/gitside) ⭐ 20 | 🐛 10 | 🌐 Rust | 📅 2026-08-15 - A responsive, mouse-friendly Git source-control TUI for full terminals and narrow tmux panes.
* [ratatui-form](https://github.com/DavidLiedle/ratatui-form) ⭐ 20 | 🐛 2 | 🌐 Rust | 📅 2026-04-13 - A form library for ratatui.
* [raymon](https://github.com/bnomei/raymon) ⭐ 18 | 🐛 3 | 🌐 Rust | 📅 2026-07-01 - Ray logging TUI and MCP Server.
* [ilmari](https://github.com/bnomei/ilmari) ⭐ 17 | 🐛 5 | 🌐 Rust | 📅 2026-08-08 - Minimal tmux popup radar to track your agents.
* [Yardlet](https://github.com/zzunkie/yardlet) ⭐ 17 | 🐛 4 | 🌐 Rust | 📅 2026-08-24 - A local AI workbench that turns intent into a verified task queue and drives your installed Claude Code or Codex CLIs as interchangeable workers.
* [agent-console](https://github.com/buhuipao/agent-console) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - A local dashboard for Codex and Claude Code.
* [agx](https://github.com/brevity1swos/agx) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-06-25 - A step-through debugger for AI agent execution traces.
* [trex](https://github.com/blackopsrepl/trex) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-08-06 - A fast tmux session manager with fuzzy finding, per session stats and AI Agent tracking.
* [gmsg](https://github.com/olorikendrick/gmsg) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Generate, edit, and commit AI-powered Git commit messages from a single TUI.
* [stevedore](https://github.com/takumiymd/stevedore) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-07-31 - A fast, keyboard-driven terminal UI for managing Docker containers and Compose stacks.
* [p2pmux](https://github.com/pelazas/p2pmux) ⭐ 10 | 🐛 2 | 🌐 Rust | 📅 2026-08-23 - A peer-to-peer terminal multiplexer where every pane is a PTY on its owner's own machine, with an inbox of the coding agents running across all of them.
* [Reeve](https://github.com/Dancode-188/reeve) ⭐ 7 | 🐛 10 | 🌐 Rust | 📅 2026-08-25 - A terminal cockpit for AI agents: watch a run live, score it, and step in when it goes sideways.
* [Forge](https://github.com/NorviaLabs/forge) ⭐ 6 | 🐛 4 | 🌐 Rust | 📅 2026-08-26 - An AI coding agent that unifies an agent, code editor, and shell in a single keyboard-driven terminal workspace.
* [iris](https://github.com/itzenata/iris-tui) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-07-08 - Live supervisor for every active Claude Code session - status, tokens, estimated cost, and one-pane approval of tool calls.
* [VLE](https://github.com/tuffy/vle) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-08-24 - A lightweight text editor.
* [ComfyGit](https://github.com/comfy-home/ComfyGit) ⭐ 3 | 🐛 7 | 🌐 Rust | 📅 2026-08-09 - All-In-One: Centralised multi-project management, Changelog generator, Version bumper & CLI tool introducing a new ComfyGitFlow.
* [rootle](https://github.com/rootledev/rootle) ⭐ 2 | 🐛 3 | 🌐 Rust | 📅 2026-08-25 - A modal TUI for browsing remote forges (GitHub in-tree, others via stdio providers) with miller columns and syntax-highlighted previews.
* [raygun](https://github.com/yetidevworks/raygun) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-08-04 - A terminal-based receiver for Spatie's Ray debugger, compatible with the Ray HTTP protocol used by PHP, Laravel, and Grav.

### 🕹️ Games and Entertainment

* [GitType](https://github.com/unhappychoice/gittype) ⭐ 1,575 | 🐛 16 | 🌐 Rust | 📅 2026-08-25 - A CLI code-typing game that turns your source code into typing challenges.
* [Chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,160 | 🐛 30 | 🌐 Rust | 📅 2026-08-17 - Terminal-based Chess game.
* [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 729 | 🐛 4 | 🌐 Rust | 📅 2026-08-19 - P2P terminal game about spacepirates playing basketball across the galaxy.
* [plastic](https://github.com/Amjad50/plastic) ⭐ 581 | 🐛 20 | 🌐 Rust | 📅 2026-03-09 - NES emulator with extra ui implemented in ratatui.
* [Dealve](https://github.com/kurama/dealve-tui) ⭐ 244 | 🐛 5 | 🌐 Rust | 📅 2026-05-08 - Browse game deals across Steam, GOG, Humble Bundle, Epic Games, and more from your terminal.
* [minesweep](https://github.com/cpcloud/minesweep-rs) ⚠️ Archived - Terminal-based Minesweeper game.
* [ssHattrick](https://github.com/ricott1/sshattrick) ⭐ 147 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 - Play Hattrick in your terminal over SSH.
* [private\_poker](https://github.com/theOGognf/private_poker) ⭐ 104 | 🐛 0 | 🌐 Rust | 📅 2026-07-13 - A poker library, server, client, and TUI.
* [Battleship.rs](https://github.com/deepu105/battleship-rs) ⭐ 97 | 🐛 4 | 🌐 Rust | 📅 2024-10-16 - Terminal-based Battleship game.
* [astray](https://github.com/Vinermy/astray) ⭐ 86 | 🐛 9 | 🌐 Rust | 📅 2024-08-16 - TUI-based space strategy game.
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 84 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 - Beautiful visualizations of common maze building and graph searching algorithms.
* [sharad-ratatui](https://github.com/ProHaller/sharad_ratatui) ⭐ 68 | 🐛 2 | 🌐 Rust | 📅 2025-07-06 - A text-based Shadowrun role-playing game.
* [crosstui](https://github.com/matrixfrog/crossword) ⭐ 53 | 🐛 12 | 🌐 Rust | 📅 2025-07-31 - Terminal-based crossword puzzle player.
* [tage](https://github.com/jacopograndi/tage) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2024-08-13 - Turn based strategy game with multiplayer, empires and warfare.
* [Snake](https://github.com/kriskw1999/ratatui-snake) ⭐ 45 | 🐛 1 | 🌐 Rust | 📅 2025-03-16 - Simple terminal based snake game.
* [wordl](https://github.com/palerdot/wordl-rs) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2024-03-16 - Terminal-based Wordle game. Web like experience with keyboard hints and guess reveal animations.
* [sxtetris](https://github.com/shixinhuang99/sxtetris) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2025-08-26 - A terminal Tetris game.
* [rust-sadari-cli](https://github.com/24seconds/rust-sadari-cli) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2020-05-11 - Rust sadari game based on terminal! (Ghost leg or Amidakuji in another words).
* [modder-rs](https://github.com/JayanAXHF/modder-rs) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2025-09-20 - A practical TUI to manage and install mods for Minecraft.
* [terminal.pong](https://github.com/IshmamR/terminal.pong) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 - Terminal based ping pong game.
* [chessterm](https://github.com/ronaldsuwandi/chessterm) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2025-02-05 - A Rust-powered chess engine in a terminal.
* [termfarm](https://github.com/indium114/termfarm) ⭐ 25 | 🐛 0 | 🌐 Rust | 📅 2026-08-24 - A simple idle farming game.
* [oxycards](https://github.com/BrookJeynes/oxycards) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-08-01 - Quiz card application built within the terminal.
* [tic-tac-toe](https://github.com/thomas-mauran/tic-tac-toe) ⭐ 18 | 🐛 2 | 🌐 Rust | 📅 2024-10-29 - Terminal-based tic tac toe game.
* [flip7](https://github.com/ilyichv/flip7) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-04-13 - Terminal-based Flip7 game.
* [cgol-tui](https://github.com/jeromeschmied/cgol-tui-rs) ⭐ 13 | 🐛 4 | 🌐 Rust | 📅 2026-07-20 - Conway's Game of Life viewer with a TUI in Rust.
* [game-of-life-rs](https://github.com/kachark/game-of-life-rs) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2021-04-08 - Conway's Game of Life implemented in Rust and visualized with tui-rs.
* [WOPR TUI 2026](https://github.com/ankurCES/WOPR_TUI_2026) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A WarGames-inspired Cold War simulation TUI with AI-powered scenarios, DEFCON escalation, and multi-language intelligence intercepts.
* [a-puzzle-a-day](https://github.com/mrbjarksen/a-puzzle-a-day) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2024-03-15 - Generate and browse all solutions to A-Puzzle-A-Day.
* [sued-rs](https://github.com/Danilo-Guedes/sued-rs) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-08-13 - A horror-themed recreation of SueD, the 2000s Brazilian prank oracle.
* [tetris-tui](https://github.com/Axyl1410/tetris-tui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - Terminal Tetris following the Tetris Guideline.
* [Blackjack](https://github.com/skharchikov/blackjack) ⭐ 6 | 🐛 13 | 🌐 Rust | 📅 2026-08-17 - Multiplayer Blackjack with a WebSocket server and a terminal client.
* [bigbrainwordle](https://github.com/kloki/bigbrainwordle) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2026-02-28 - A tool to help you cheat with the daily wordle.
* [Connect-four](https://github.com/jesper-olsen/connect-four) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-07-20 - Connect-four; interactive game + perfect solver.
* [enimtui](https://codeberg.org/tranzystorekk/enimtui) - Terminal-based minesweeper knockoff.
* [Thardians](https://gitlab.com/thustle/thardians-rs) - Space Invaders for the terminal.

### 🎼 Music and Media

* [spotify-tui](https://github.com/Rigellute/spotify-tui) ⭐ 19,318 | 🐛 306 | 🌐 Rust | 📅 2024-04-04 - (Unmaintained) The original Spotify TUI; see spotatui (direct fork) or spotify-player (independent alternative).
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,123 | 🐛 166 | 🌐 Rust | 📅 2026-07-20 - An independently developed Spotify player with full feature parity.
* [MovieBox-TUI](https://github.com/mesamirh/MovieBox-Tui) ⭐ 1,304 | 🐛 6 | 🌐 Rust | 📅 2026-08-25 - Terminal client for discovering and downloading movies and series, with playback in mpv, VLC, or IINA.
* [spotatui](https://github.com/LargeModGames/spotatui) ⭐ 1,260 | 🐛 27 | 🌐 Rust | 📅 2026-08-25 - Spotify client with native streaming, synced lyrics, and audio visualization. A direct fork of spotify-tui with continued development and new features.
* [bookokrat](https://github.com/bugzmanov/bookokrat) ⭐ 1,105 | 🐛 48 | 🌐 Rust | 📅 2026-08-08 - A full-featured EPUB / PDF e-book reader with Vim keybindings.
* [manga-tui](https://github.com/josueBarretogit/manga-tui) ⭐ 922 | 🐛 22 | 🌐 Rust | 📅 2026-07-13 - Terminal-based manga reader and downloader with image support.
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 773 | 🐛 37 | 🌐 Rust | 📅 2025-03-03 - Listen to music from YouTube in the terminal.
* [managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 760 | 🐛 2 | 🌐 Rust | 📅 2026-07-06 - A TUI and CLI for managing all your Servarrs.
* [scope-tui](https://github.com/alemidev/scope-tui) ⭐ 700 | 🐛 12 | 🌐 Rust | 📅 2026-03-01 - A simple oscilloscope/vectorscope/spectroscope for your terminal.
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 632 | 🐛 10 | 🌐 Rust | 📅 2026-05-29 - Twitch chat in the terminal.
* [NoctaVox](https://github.com/Jaxx497/noctavox) ⭐ 372 | 🐛 3 | 🌐 Rust | 📅 2026-08-22 - A lightweight, customizable TUI music player for local files.
* [asak](https://github.com/chaosprint/asak) ⭐ 371 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 - A cross-platform audio recording/playback CLI tool.
* [fum](https://github.com/qxb3/fum) ⭐ 284 | 🐛 5 | 🌐 Rust | 📅 2026-07-11 - A fully ricable tui-based music client.
* [myx](https://github.com/HaseebKhalid1507/Myx) ⭐ 205 | 🐛 10 | 🌐 Rust | 📅 2026-08-13 - Modern Spotify player for the terminal. With reactive themes.
* [glicol-cli](https://github.com/glicol/glicol-cli) ⭐ 193 | 🐛 13 | 🌐 Rust | 📅 2024-12-09 - Cross-platform music live coding in terminal.
* [mal-cli](https://github.com/L4z3x/mal-cli) ⭐ 159 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 - A TUI for myanimelist.
* [chordflow](https://github.com/timvancann/chordflow) ⭐ 94 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - A tool for practicing improvisation and mastering the guitar neck.
* [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) ⭐ 93 | 🐛 6 | 🌐 Rust | 📅 2026-06-22 - Sample-based, MIDI-controlled virtual pipe organ instrument.
* [ytsub](https://github.com/sarowish/ytsub) ⭐ 89 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - A subscriptions only TUI YouTube client.
* [rs-pug](https://github.com/JustRoccat/rs-pug) ⭐ 66 | 🐛 0 | 🌐 Rust | 📅 2026-08-20 - A Neovim-inspired asynchronous music player with a reactive audio visualizer.
* [roon-tui](https://github.com/TheAppgineer/roon-tui) ⭐ 64 | 🐛 5 | 🌐 Rust | 📅 2024-08-30 - Roon Remote for the terminal.
* [TRNovel](https://github.com/yexiyue/TRNovel) ⭐ 63 | 🐛 2 | 🌐 Rust | 📅 2026-08-24 - A terminal novel reader for local and network novels, with AI-assisted book-source generation and TTS playback.
* [sparkplayer](https://github.com/dividebysandwich/sparkplayer/tree/main) ⭐ 50 | 🐛 1 | 🌐 Rust | 📅 2026-08-18 - A fun terminal based media player with album art and video support.
* [O₂](https://github.com/coignard/o2) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2026-08-12 - Rust port of the ORCΛ esoteric programming language and terminal livecoding environment.
* [serenIT](https://github.com/ElevenJune/serenIT) ⭐ 48 | 🐛 2 | 🌐 Rust | 📅 2025-11-20 - An ambient sound player directly from your terminal.
* [deezer-tui](https://github.com/Tatayoyoh/deezer-tui) ⭐ 47 | 🐛 5 | 🌐 Rust | 📅 2026-08-17 - Deezer music TUI with included background player.
* [lrxed](https://github.com/LunaPresent/lrxed) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2025-11-02 - A TUI application for synchronizing lyrics.
* [trollstov](https://github.com/hikikones/trollstov) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - A music player for the terminal where your files and their metadata are all you need.
* [audium](https://github.com/takashialpha/audium) ⭐ 36 | 🐛 1 | 🌐 Rust | 📅 2026-08-26 - A keyboard-driven music app for people who live in the terminal.
* [bytebeat-rs](https://github.com/chaosprint/bytebeat-rs) ⭐ 30 | 🐛 1 | 🌐 Rust | 📅 2023-12-18 - A TUI for bytebeat.
* [oosc-rs](https://github.com/karasikq/oosc-rs) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-03-04 - An additive wavetable synthesizer for terminal.
* [classfi](https://github.com/carmiac/classfi) ⭐ 20 | 🐛 5 | 🌐 Rust | 📅 2026-07-23 - A focused streaming music player for classical music.
* [tusic](https://github.com/eminfedar/tusic) ⭐ 19 | 🐛 1 | 🌐 Rust | 📅 2026-07-15 - Lightweight TUI Music Player. Play from YouTube or \~/Music folder easily.
* [smyx](https://github.com/ayanchavand/Smyx) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - A sleek, beautiful music player for Navidrome / OpenSubsonic with dynamic themes.
* [readio](https://github.com/hrhrng/readio) ⭐ 7 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - A terminal ebook reader for EPUB, PDF, Markdown, and plain text with optional local text-to-speech.
* [sgram-tui](https://github.com/arian-shamaei/sgram-tui) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - A calibrated spectrogram analyzer for live mic or audio files, with labeled PNG figure export and a headless render mode.
* [ytmusic-tui](https://github.com/WakaTaira/ytmusic-tui) ⭐ 1 | 🐛 11 | 🌐 Rust | 📅 2026-06-19 - TUI client for YouTube Music with vim-style keybindings, spotify-player-inspired navigation, and MPRIS2 support.
* [m-lite](https://github.com/maxiloEmmmm/m-lite) ⚠️ Archived - Listen to music from net163 in the terminal.
* [angry-duiker](https://gitlab.com/fizzizist/angry-duiker-2) - A TUI for streaming music from a DLNA server.

### 🌐 Networking and Internet

* [JocalSend](https://git.kittencollective.com/nebkor/joecalsend) - Peer to peer local file and data transfer, compatible with [LocalSend](https://github.com/localsend/localsend) ⭐ 89,371 | 🐛 1,096 | 🌐 Dart | 📅 2026-08-24
* [vector](https://github.com/vectordotdev/vector) ⭐ 22,456 | 🐛 2,526 | 🌐 Rust | 📅 2026-08-26 - A high-performance observability data pipeline.
* [gping](https://github.com/orf/gping/) ⭐ 12,645 | 🐛 52 | 🌐 Rust | 📅 2026-08-24 - Ping tool with a graph.
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 11,919 | 🐛 55 | 🌐 Rust | 📅 2026-08-01 - Displays network utilization by process.
* [oha](https://github.com/hatoo/oha) ⭐ 10,507 | 🐛 57 | 🌐 Rust | 📅 2026-08-23 - Top-like monitoring tool for HTTP(S) traffic.
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 7,526 | 🐛 77 | 🌐 Rust | 📅 2026-08-25 - Network diagnostic tool.
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 4,932 | 🐛 17 | 🌐 Rust | 📅 2026-08-24 - A cross-platform network monitoring tool with deep packet inspection.
* [termscp](https://github.com/veeso/termscp) ⭐ 3,057 | 🐛 7 | 🌐 Rust | 📅 2026-07-29 - A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB.
* [impala](https://github.com/pythops/impala) ⭐ 2,797 | 🐛 3 | 🌐 Rust | 📅 2026-08-25 - TUI for managing wifi on Linux.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,563 | 🐛 5 | 🌐 Rust | 📅 2026-07-17 - A TUI for sniffing network traffic using eBPF.
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,816 | 🐛 6 | 🌐 Rust | 📅 2026-07-06 - Network scanning tool.
* [AdGuardian-Term](https://github.com/Lissy93/AdGuardian-Term) ⭐ 1,642 | 🐛 13 | 🌐 Rust | 📅 2026-08-14 - Real-time traffic monitoring and statistics for AdGuard Home.
* [dnsglobe](https://github.com/514-labs/dnsglobe) ⭐ 1,101 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - Global DNS propagation checker querying 34 resolvers worldwide, with a world map.
* [adsb\_deku/radar](https://github.com/wcampbell0x2a/adsb_deku#radar-tui) ⭐ 724 | 🐛 25 | 🌐 Rust | 📅 2026-01-04 - TUI for displaying ADS-B data from aircraft.
* [mqttui](https://github.com/EdJoPaTo/mqttui) ⭐ 720 | 🐛 10 | 🌐 Rust | 📅 2026-08-09 - MQTT client for subscribing or publishing to topics.
* [vortix](https://github.com/Harry-kp/vortix) ⭐ 641 | 🐛 31 | 🌐 Rust | 📅 2026-08-22 - Terminal UI for WireGuard and OpenVPN with real-time telemetry, leak detection, and kill switch.
* [unifly](https://github.com/hyperb1iss/unifly) ⭐ 247 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - CLI and TUI for managing Ubiquiti UniFi network controllers with an 8-screen dashboard, live traffic charts, and dual-API coverage.
* [ssh-list](https://github.com/akinoiro/ssh-list) ⭐ 220 | 🐛 5 | 🌐 Rust | 📅 2025-10-27 - SSH connection manager.
* [CuTE](https://github.com/PThorpe92/CuTE) ⚠️ Archived - A libcurl powered HTTP Client with API-key/request mgmt and vim keybindings.
* [wireman](https://github.com/preiter93/wireman) ⭐ 179 | 🐛 6 | 🌐 Rust | 📅 2026-08-22 - A gRPC client for the terminal.
* [vincenzo](https://github.com/gabrieldemian/vincenzo) ⭐ 158 | 🐛 4 | 🌐 Rust | 📅 2026-04-05 - A bittorrent client for the terminal with vim-like keybindings.
* [mullvad-tui](https://github.com/d10n/mullvad-tui) ⭐ 74 | 🐛 0 | 🌐 Rust | 📅 2026-06-24 - A TUI for Mullvad VPN.
* [mxr](https://github.com/planetaryescape/mxr) ⭐ 70 | 🐛 12 | 🌐 Rust | 📅 2026-08-25 - Local-first email client with Vim-style navigation, multi-account sync, and full-text search.
* [rustmission](https://github.com/intuis/rustmission) ⭐ 65 | 🐛 21 | 🌐 Rust | 📅 2026-03-26 - TUI for the Transmission daemon.
* [terminusdm](https://github.com/sumoduduk/terminusdm) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2024-08-22 - Cross Platform Terminal Download Manager.
* [YADB](https://github.com/izya4ka/yadb) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2026-02-24 - A web directory brute-forcing tool.
* [ytunnel](https://github.com/yetidevworks/ytunnel) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2026-08-05 - A TUI-first CLI for managing Cloudflare Tunnels with custom domains.
* [LazyMQTT](https://github.com/ScottFelder/lazymqtt) ⭐ 44 | 🐛 0 | 🌐 Rust | 📅 2026-08-12 - Terminal UI MQTT client with features like saved connections, live topic tree, and message inspector.
* [rrtop](https://github.com/wojciech-zurek/rrtop) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2021-08-05 - Redis monitoring (top like) app. rrtop -> \[r]ust \[r]edis \[top].
* [discovery-rs](https://github.com/JustPretender/discovery-rs) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2025-08-21 - An utility to discover mDNS services on your network.
* [conclusive](https://github.com/mrusme/conclusive) ⚠️ Archived - A command line client for Plausible Analytics.
* [nordvpn-tui](https://github.com/Degra02/nordvpn-tui) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2024-10-08 - A TUI for NordVPN.
* [wiretui](https://github.com/robin-thoene/wiretui) ⭐ 18 | 🐛 4 | 🌐 Rust | 📅 2026-08-03 - A minimal keyboard-driven TUI to manage WireGuard VPN connections.
* [sensor-vision](https://github.com/jcfromsiberia/sensor-vision) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2025-04-26 - TUI Client for TeamViewer IoT MQTT API for managing IoT Sensors and Metrics.
* [tsuchita](https://github.com/kamiyaa/tsuchita) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - Client-server notification center for dbus desktop notifications.
* [yscan](https://github.com/yetidevworks/yscan) ⭐ 6 | 🐛 3 | 🌐 Rust | 📅 2026-08-04 - A TUI-first network scanner with ARP, mDNS, and SSDP discovery.
* [traxor](https://github.com/kristoferssolo/traxor) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-05-14 - A TUI for managing Transmission torrents.

### 🚀 Productivity and Utilities

* [atuin](https://github.com/atuinsh/atuin) ⭐ 31,414 | 🐛 407 | 🌐 Rust | 📅 2026-08-26 - Magical shell history.
* [television](https://github.com/alexpasmantier/television) ⭐ 6,209 | 🐛 83 | 🌐 Rust | 📅 2026-08-16 - A blazingly fast general purpose fuzzy finder for your terminal.
* [linutil](https://github.com/ChrisTitusTech/linutil) ⭐ 5,230 | 🐛 13 | 🌐 Shell | 📅 2026-08-17 - A distro-agnostic toolbox designed to simplify everyday Linux tasks.
* [xan](https://github.com/medialab/xan) ⭐ 4,482 | 🐛 123 | 🌐 Rust | 📅 2026-07-31 - A terminal tool for processing CSV files.
* [binsider](https://github.com/orhun/binsider) ⭐ 4,403 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 - A TUI for analyzing binary files.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 3,941 | 🐛 59 | 🌐 Rust | 📅 2026-07-04 - Command line csv viewer.
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,117 | 🐛 45 | 🌐 Rust | 📅 2024-03-07 - Terminal-based disk space navigator.
* [tabiew](https://github.com/shshemi/tabiew) ⭐ 3,089 | 🐛 17 | 🌐 Rust | 📅 2026-08-25 - A lightweight TUI app to view and query CSV files.
* [bluetui](https://github.com/pythops/bluetui) ⭐ 2,971 | 🐛 21 | 🌐 Rust | 📅 2026-07-17 - A TUI for managing Bluetooth devices.
* [mprocs](https://github.com/pvolok/mprocs) ⭐ 2,701 | 🐛 67 | 🌐 Rust | 📅 2026-08-25 - Run multiple commands in parallel and shows output of each command separately.
* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,110 | 🐛 133 | 🌐 Rust | 📅 2026-08-23 - TUI for the Taskwarrior command-line task manager.
* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,753 | 🐛 14 | 🌐 Rust | 📅 2026-08-10 - Manage your GnuPG keys with ease!.
* [tickrs](https://github.com/tarkah/tickrs) ⭐ 1,683 | 🐛 33 | 🌐 Rust | 📅 2026-05-19 - Stock market ticker in the terminal.
* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,590 | 🐛 35 | 🌐 Rust | 📅 2026-04-07 - Terminal-based typing test.
* [tuxedo](https://github.com/webstonehq/tuxedo) ⭐ 1,586 | 🐛 53 | 🌐 Rust | 📅 2026-08-19 - A fast, keyboard-driven terminal UI for todo.txt.
* [flyline](https://github.com/HalFrgrd/flyline) ⭐ 1,078 | 🐛 27 | 🌐 Rust | 📅 2026-08-24 - A Bash plugin TUI for an enhanced command line writing experience.
* [eilmeldung](https://github.com/christo-auer/eilmeldung) ⭐ 943 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 - A TUI RSS reader based on the news\_flash library inspired by Neovim and co.
* [stu](https://github.com/lusingander/stu) ⭐ 907 | 🐛 15 | 🌐 Rust | 📅 2026-04-30 - A TUI for AWS S3.
* [igrep](https://github.com/konradsz/igrep) ⭐ 842 | 🐛 12 | 🌐 Rust | 📅 2026-02-01 - Interactive Grep.
* [tui-journal](https://github.com/AmmarAbouZor/tui-journal) ⭐ 774 | 🐛 24 | 🌐 Rust | 📅 2026-08-16 - Journaling/Notes-taking terminal-based app.
* [flawz](https://github.com/orhun/flawz) ⭐ 597 | 🐛 15 | 🌐 Rust | 📅 2026-06-13 - A TUI for browsing security vulnerabilities (CVEs).
* [md-tui](https://github.com/henriklovhaug/md-tui) ⭐ 537 | 🐛 19 | 🌐 Rust | 📅 2026-08-18 - Markdown renderer in the terminal.
* [rucola](https://github.com/Linus-Mussmaecher/rucola) ⭐ 524 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - Terminal-based markdown note manager.
* [otree](https://github.com/fioncat/otree) ⭐ 513 | 🐛 3 | 🌐 Rust | 📅 2026-08-17 - A command line tool to view objects (JSON/YAML/TOML) in TUI tree widget.
* [models](https://github.com/arimxyer/models) ⭐ 500 | 🐛 0 | 🌐 Rust | 📅 2026-08-26 - A TUI for browsing AI models, benchmarks, and coding agents.
* [blendr](https://github.com/dmtrKovalenko/blendr) ⭐ 490 | 🐛 6 | 🌐 Rust | 📅 2024-09-01 - The hacker's BLE (bluetooth low energy) browser terminal app.
* [feedr](https://github.com/bahdotsh/feedr) ⭐ 427 | 🐛 8 | 🌐 Rust | 📅 2026-06-11 - A terminal-based RSS/Atom feed reader with a TUI.
* [fsel](https://github.com/Mjoyufull/fsel) ⭐ 413 | 🐛 7 | 🌐 Rust | 📅 2026-08-21 - A TUI app launcher and fuzzy finder for GNU/Linux and BSD.
* [kbt](https://github.com/bloznelis/kbt) ⭐ 392 | 🐛 5 | 🌐 Rust | 📅 2025-11-26 - Keyboard tester in terminal.
* [timr-tui](https://github.com/sectore/timr-tui) ⭐ 369 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - TUI to organize your time: Pomodoro, Countdown, Timer, Event.
* [jwt-ui](https://github.com/jwt-rs/jwt-ui) ⭐ 348 | 🐛 10 | 🌐 Rust | 📅 2026-05-31 - A command line UI for decoding/encoding JSON Web Tokens.
* [tmmpr](https://github.com/tanciaku/tmmpr) ⭐ 347 | 🐛 3 | 🌐 Rust | 📅 2026-05-15 - Terminal mind mapper.
* [blogr](https://github.com/bahdotsh/blogr) ⭐ 345 | 🐛 13 | 🌐 Rust | 📅 2026-06-08 - A terminal-based static site generator with a TUI editor for writing blog posts.
* [rusty-krab-manager](https://github.com/aryakaul/rusty-krab-manager) ⭐ 328 | 🐛 11 | 🌐 Rust | 📅 2026-07-20 - Rime management TUI in Rust.
* [exabind](https://github.com/junkdog/exabind) ⭐ 295 | 🐛 0 | 🌐 Rust | 📅 2026-03-29 - An animated TUI for viewing KDE shortcuts.
* [fzf-make](https://github.com/kyu08/fzf-make) ⭐ 291 | 🐛 44 | 🌐 Rust | 📅 2026-08-22 - A command line tool that executes make target using fuzzy finder with preview window.
* [mirador](https://github.com/jchultarsky/mirador) ⭐ 291 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 - A personal dashboard with world clocks, calendar, weather, tasks, notes, a market watchlist and live CPU and network graphs.
* [ostt](https://github.com/kristoferlund/ostt) ⭐ 290 | 🐛 3 | 🌐 Rust | 📅 2026-08-12 - Open Speech-to-Text recording tool with real-time volume metering and transcription.
* [glues](https://github.com/gluesql/glues) ⭐ 282 | 🐛 16 | 🌐 Rust | 📅 2026-06-02 - A sync-enabled TUI note-taking app with Git, CSV, and JSON support.
* [hexhog](https://github.com/DVDTSB/hexhog) ⭐ 280 | 🐛 9 | 🌐 Rust | 📅 2026-02-16 - TUI Hex Editor/Viewer.
* [Rust-Kanban](https://github.com/yashs662/rust_kanban) ⭐ 269 | 🐛 2 | 🌐 Rust | 📅 2025-02-13 - A kanban board for the terminal.
* [numr](https://github.com/nasedkinpv/numr) ⭐ 262 | 🐛 3 | 🌐 Rust | 📅 2026-07-14 - A natural language calculator with unit/currency conversions and vim-style keybindings.
* [work-tuimer](https://github.com/Kamyil/work-tuimer) ⭐ 261 | 🐛 9 | 🌐 Rust | 📅 2026-05-18 - A TUI for easier time tracking each day, task-per-task with summaries.
* [budget\_tracker\_tui](https://github.com/Feromond/budget_tracker_tui) ⭐ 260 | 🐛 11 | 🌐 Rust | 📅 2026-08-05 - A fast, keyboard-driven TUI for tracking expenses, managing categories, and analyzing your budget with ease.
* [wiper](https://github.com/ikebastuz/wiper) ⭐ 248 | 🐛 12 | 🌐 Rust | 📅 2025-11-14 - Disk space analyzer and cleanup tool.
* [sheetsui](https://github.com/zaphar/sheetsui) ⭐ 246 | 🐛 3 | 🌐 Rust | 📅 2026-03-03 - A terminal based spreadsheet application.
* [matchmaker](https://github.com/Squirreljetpack/matchmaker) ⭐ 238 | 🐛 0 | 🌐 Rust | 📅 2026-08-24 - Fuzzy picker (FZF reboot).
* [neura-hustle-tracker](https://github.com/adolfousier/neura-hustle-tracker) ⭐ 234 | 🐛 0 | 🌐 Rust | 📅 2026-03-16 - A privacy-first TUI to track what apps you use and how long you spend on them.
* [rgx](https://github.com/brevity1swos/rgx) ⭐ 233 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A terminal regex debugger with real-time matching, 3 engines, capture group highlighting, replace mode, and plain-English explanations.
* [oak-keyring](https://github.com/OpenKeyring/oak-keyring) ⭐ 231 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - A local-first password manager that keeps vault management interactive, keyboard-driven, and in the terminal.
* [envx](https://github.com/mikeleppane/envx) ⭐ 228 | 🐛 4 | 🌐 Rust | 📅 2025-09-19 - Environment variable manager for developers, featuring an intuitive TUI.
* [basilk](https://github.com/GabAlpha/basilk) ⭐ 214 | 🐛 11 | 🌐 Rust | 📅 2025-05-24 - A TUI to manage your tasks with minimal kanban logic.
* [splashboard](https://github.com/unhappychoice/splashboard) ⭐ 213 | 🐛 13 | 🌐 Rust | 📅 2026-08-24 - A customizable terminal splash rendered on shell startup or directory updates.
* [Jirust](https://github.com/moali87/jirust) ⭐ 159 | 🐛 6 | 🌐 Rust | 📅 2024-05-29 - A Jira TUI.
* [kanban](https://github.com/fulsomenko/kanban) ⭐ 158 | 🐛 6 | 🌐 Rust | 📅 2026-08-25 - TUI kanban board for projects management with sprint tracking and task prioritization.
* [oracle](https://github.com/yashksaini-coder/oracle) ⭐ 156 | 🐛 0 | 🌐 Rust | 📅 2026-04-02 - A TUI Rust codebase inspector to browse functions, structs, enums, traits, and more.
* [lazy-etherscan](https://github.com/woxjro/lazy-etherscan) ⭐ 153 | 🐛 1 | 🌐 Rust | 📅 2025-04-20 - A Simple Terminal UI for the Ethereum Blockchain Explorer.
* [synd](https://github.com/ymgyt/syndicationd) ⭐ 153 | 🐛 10 | 🌐 Rust | 📅 2026-08-24 - A TUI feed viewer.
* [snipt](https://github.com/snipt/snipt) ⭐ 148 | 🐛 5 | 🌐 Rust | 📅 2026-04-02 - A text snippet expansion tool with a TUI for managing snippets.
* [bbcli](https://github.com/hako/bbcli) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-02 - A terminal-based BBC News reader featuring a compact, numbered list interface with vim-like navigation.
* [fitui](https://github.com/ayanchavand/fitui) ⭐ 141 | 🐛 0 | 🌐 Rust | 📅 2026-07-18 - A terminal-based personal finance tracker and budgeting with TUI.
* [tatuin](https://github.com/panter-dsd/tatuin) ⭐ 137 | 🐛 18 | 🌐 Rust | 📅 2026-08-24 - Task Aggregator TUI for N providers.
* [brew-explorer](https://github.com/cosmincatalin/brew-explorer) ⭐ 136 | 🐛 3 | 🌐 Rust | 📅 2026-05-27 - A TUI for exploring and managing your Homebrew packages with ease.
* [passepartui](https://github.com/kardwen/passepartui) ⭐ 128 | 🐛 4 | 🌐 Rust | 📅 2025-05-07 - A TUI for pass.
* [codemark](https://github.com/DanielCardonaRojas/codemark) ⭐ 121 | 🐛 7 | 🌐 Rust | 📅 2026-08-19 - A semantic code bookmarking system for humans and agents.
* [judo](https://github.com/giacomopiccinini/judo) ⭐ 117 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 - A multi-database TUI for ToDo lists.
* [gitv](https://github.com/jayanaxhf/gitv) ⭐ 115 | 🐛 12 | 🌐 Rust | 📅 2026-08-20 - A beautiful, feature-rich and performant terminal client for GitHub issues.
* [tuistash](https://github.com/edmocosta/tuistash) ⭐ 109 | 🐛 2 | 🌐 Rust | 📅 2026-04-10 - A TUI for monitoring Logstash.
* [chamber](https://github.com/mikeleppane/chamber) ⭐ 103 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A TUI for managing secrets.
* [ddv](https://github.com/lusingander/ddv) ⭐ 102 | 🐛 3 | 🌐 Rust | 📅 2026-04-29 - Terminal DynamoDB viewer.
* [regect](https://github.com/kloki/regect) ⭐ 96 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A regex101 like tool for the cli.
* [vault-tasks](https://github.com/louis-thevenet/vault-tasks) ⭐ 87 | 🐛 11 | 🌐 Rust | 📅 2026-06-05 - TUI Markdown Task Manager.
* [lt](https://github.com/markmarkoh/lt) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2026-01-14 - An unofficial TUI client for Linear.app.
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 83 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 - Terminal presentation program with modern TUI.
* [rdn](https://github.com/apatrushev/rdn) ⭐ 79 | 🐛 0 | 🌐 Rust | 📅 2026-03-17 - Rust port of well known old Dos Navigator.
* [ttypr](https://github.com/hotellogical05/ttypr) ⭐ 77 | 🐛 0 | 🌐 Rust | 📅 2026-03-21 - Terminal typing practice.
* [leetrs](https://github.com/shadowmkj/leetrs) ⭐ 75 | 🐛 10 | 🌐 Rust | 📅 2026-08-25 - A TUI for browsing, testing, and submitting LeetCode problems directly from your terminal.
* [visualvault](https://github.com/mikeleppane/visualvault) ⭐ 64 | 🐛 3 | 🌐 Rust | 📅 2026-08-24 - A TUI for organizing media files.
* [scriptor](https://github.com/giacomopiccinini/scriptor) ⭐ 63 | 🐛 1 | 🌐 Rust | 📅 2026-05-14 - A (medieval) local speech-to-text TUI & CLI.
* [Rex](https://github.com/TheRustyPickle/Rex) ⭐ 62 | 🐛 0 | 🌐 Rust | 📅 2026-07-04 - A TUI for managing Incomes and Expenses.
* [btlescan](https://github.com/ztroop/btlescan) ⭐ 56 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - Bluetooth Low Energy (BTLE) scanner and GATT viewer.
* [kimün](https://github.com/nico2sh/kimun) ⭐ 55 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - A terminal-based Markdown note taking app that combines an interactive TUI with a scriptable CLI for automation.
* [get\_blessed\_rs](https://github.com/josueBarretogit/get_blessed_rs) ⭐ 50 | 🐛 0 | 🌐 Rust | 📅 2024-06-29 - Get the best crates for your rust projects, curated by blessed.rs.
* [td](https://github.com/holly-hacker/td) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A graph-based TUI to-do app.
* [TSHTS](https://github.com/SamuelSchlesinger/tshts) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-05-28 - A terminal based spreadsheet application.
* [dead-ringer](https://github.com/ztroop/dead-ringer) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - Binary diff tool for Hex/ASCII analysis.
* [focusd](https://github.com/bibekbhusal0/focusd) ⭐ 45 | 🐛 1 | 🌐 Rust | 📅 2026-08-25 - A terminal pomodoro timer with daemon, stats, history, streak, and nice interface.
* [meteo-tui](https://github.com/16arpi/meteo-tui) ⭐ 42 | 🐛 2 | 🌐 Rust | 📅 2026-07-21 - French weather app in the command line.
* [invoicepilot](https://github.com/adolfousier/invoicepilot) ⭐ 41 | 🐛 0 | 🌐 Rust | 📅 2026-03-14 - A TUI for automating invoice and bank statement fetching from Gmail to Google Drive.
* [comhad](https://github.com/Eoin-McMahon/Comhad) ⭐ 36 | 🐛 2 | 🌐 Rust | 📅 2026-08-19 - A ranger-style terminal browser for S3, with previews, background transfers, and non-destructive sync.
* [lottie](https://github.com/coignard/lottie) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-08-08 - A terminal screenwriting editor for the Fountain plain-text screenplay format.
* [vib](https://github.com/ayanchavand/vib) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-07-25 - A terminal file browser with LocalSend built in, for managing, organizing and transferring files across devices.
* [flerp](https://github.com/Huseynteymurzade28/flerp) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2026-08-17 - A TUI for exploring and analyzing text files, PDFs and images.
* [alphai-tui](https://github.com/makeev/alphai-tui) ⭐ 25 | 🐛 1 | 🌐 Rust | 📅 2026-08-12 - A stock dashboard with quotes, candlestick charts, AI-scored news and SEC Form 4 insider activity.
* [depot-rs](https://github.com/quietpigeon/depot-rs) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2025-10-04 - A TUI for managing crates.
* [columbus](https://github.com/sivaprakashkrp/columbus) ⭐ 23 | 🐛 1 | 🌐 Rust | 📅 2026-06-15 - A GUI-like TUI file explorer.
* [thesaurust](https://github.com/QuietPigeon2001/thesaurust) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2025-05-07 - A terminal-based dictionary app.
* [absorb](https://github.com/kloki/absorb) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-04-11 - Quickly read a file without moving your eyes.
* [revw](https://github.com/rlelf/revw) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-04 - A vim-like TUI for managing notes and resources.
* [solverforge-calendar](https://github.com/blackopsrepl/solverforge-calendar) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-06 - A TUI calendar with Google Calendar sync and DAG-linked events.
* [pgmon](https://github.com/nbari/pgmon) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-07-01 - A TUI for monitoring PostgresSQL databases.
* [tts-tui](https://github.com/lesleyrs/tts-tui) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2024-01-26 - Text to speech app that reads from clipboard.
* [Respire](https://github.com/ElevenJune/respire) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-06-22 - A breathing app to take a break directly from your terminal.
* [exhaust](https://github.com/heyrict/exhaust) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2020-04-18 - A terminal app for doing exams.
* [quick-note](https://github.com/daniel-valencia-ts/quick-note) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-06-30 - A simple note-taking tool.
* [fastcards](https://github.com/indium114/fastcards) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-08-23 - A CLI spaced-repetition flashcard study tool.
* [traceview](https://github.com/javaLux/traceview) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-06-03 - Tracing and viewing your files and resource landscape.
* [termi](https://github.com/tuna4ll/termi) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-11 - A modal terminal code editor.
* [todolist-rust](https://github.com/ebubekirgungor/todolist-rust) ⚠️ Archived - A terminal-based simple to-do app.
* [void](https://github.com/p6laris/Void) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - A focus app with built-in task management, streak tracking, and customizable break schedules.
* [sc-cli](https://github.com/lnds/sc-cli) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 - A TUI for Shortcut (formerly know as Clubhouse) a project management tool for teams.
* [isw](https://gitlab.com/thom-cameron/isw) - A simple terminal stopwatch application for pomodoro etc.
* [pgtui](https://codeberg.org/kdwarn/pgtui) - A PostgresSQL TUI client that utilizes your terminal text editor for inserts & updates.
* [taskfinder](https://crates.io/crates/taskfinder) - Extract and display tasks from plain text files, hooking into your default terminal-based editor for editing.

### 🤡 Social Media

* [concord](https://github.com/chojs23/concord) ⭐ 1,269 | 🐛 42 | 🌐 Rust | 📅 2026-08-24 - A TUI client for Discord.
* [iamb](https://github.com/ulyssa/iamb) ⭐ 1,269 | 🐛 168 | 🌐 Rust | 📅 2026-08-23 - A matrix chat client with vim keybindings.
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 996 | 🐛 15 | 🌐 Rust | 📅 2026-08-17 - A TUI for Telegram written in Rust.
* [termchat](https://github.com/lemunozm/termchat) ⭐ 588 | 🐛 7 | 🌐 Rust | 📅 2023-11-27 - Terminal chat through the LAN with video streaming and file transfer.
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 163 | 🐛 11 | 🌐 Rust | 📅 2025-12-28 - TUI client for Bluesky.
* [lobtui](https://github.com/pythops/lobtui) ⭐ 121 | 🐛 3 | 🌐 Rust | 📅 2025-05-16 - TUI for lobste.rs website.
* [nostui](https://github.com/akiomik/nostui) ⭐ 68 | 🐛 5 | 🌐 Rust | 📅 2026-08-25 - A TUI client for Nostr.
* [rvIRC](https://github.com/KaraZajac/rvIRC) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2026-05-17 - A TUI client for IRC.
* [omaro](https://github.com/Rolv-Apneseth/omaro) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-08-23 - TUI for the lobste.rs website.
* [Chat-gRPC](https://github.com/Atheer2104/chat-grpc) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2024-08-13 - A Real-time Chat Microservice built in Rust using gRPC, including a TUI client.
* [hnr](https://github.com/prasanthj/hnr) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A terminal UI for Hacker News — browse feeds, read threaded comments, vote, reply, search, and bookmark.

### 👨‍💻 System Administration

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,931 | 🐛 107 | 🌐 Rust | 📅 2026-08-26 - Cross-platform graphical process/system monitor.
* [dua-cli](https://github.com/Byron/dua-cli) ⭐ 6,172 | 🐛 27 | 🌐 Rust | 📅 2026-08-25 - View disk space usage and delete unwanted data, fast.
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,809 | 🐛 13 | 🌐 Rust | 📅 2026-08-25 - Hackable, minimal, and fast TUI file explorer.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,043 | 🐛 40 | 🌐 Rust | 📅 2026-08-25 - Cross-platform monitoring tool for system stats.
* [kmon](https://github.com/orhun/kmon) ⭐ 2,938 | 🐛 23 | 🌐 Rust | 📅 2026-07-31 - Linux Kernel Manager and Activity Monitor.
* [bpftop](https://github.com/Netflix/bpftop) ⭐ 2,702 | 🐛 5 | 🌐 C | 📅 2026-08-01 - Dynamic real-time view of running eBPF programs.
* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,526 | 🐛 3 | 🌐 Rust | 📅 2026-08-26 - A simple and fast dashboard for Kubernetes.
* [caligula](https://github.com/ifd3f/caligula) ⭐ 2,243 | 🐛 51 | 🌐 Rust | 📅 2026-08-24 - A user-friendly, lightweight TUI for disk imaging.
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived - TUI system monitor for Linux.
* [systemctl-tui](https://github.com/rgwood/systemctl-tui) ⭐ 2,038 | 🐛 6 | 🌐 Rust | 📅 2026-07-27 - A fast, simple TUI for interacting with systemd services and their logs.
* [macmon](https://github.com/vladkens/macmon) ⭐ 1,832 | 🐛 14 | 🌐 Rust | 📅 2026-08-04 - Sudoless performance monitoring for Apple Silicon processors.
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 1,820 | 🐛 23 | 🌐 Rust | 📅 2026-08-22 - Simple TUI to view & control Docker containers.
* [systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) ⭐ 1,572 | 🐛 4 | 🌐 Rust | 📅 2026-08-03 - A program for managing systemd services through a TUI.
* [kftui](https://github.com/hcavarsan/kftray/blob/main/README.md#kftui) ⭐ 1,553 | 🐛 19 | 🌐 Rust | 📅 2026-08-25 - A TUI to manage multiple kubectl port-forward commands, with support for UDP and Kubernetes proxy.
* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,462 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to sysctl(8) with a terminal user interface.
* [ducker](https://github.com/robertpsoane/ducker) ⭐ 919 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 - A terminal app for managing Docker containers, inspired by K9s.
* [lazyrsync](https://github.com/westpoint-io/lazyrsync) ⭐ 727 | 🐛 0 | 🌐 Rust | 📅 2026-08-10 - A TUI for rsync: reusable profiles, a dry-run diff preview, and live run progress.
* [purple](https://github.com/erickochen/purple) ⭐ 656 | 🐛 4 | 🌐 Rust | 📅 2026-08-24 - TUI SSH config manager & launcher with fuzzy search, tags, cloud provider sync, tunnels and command snippets for server management.
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 393 | 🐛 11 | 🌐 Rust | 📅 2026-08-22 - TUI for real-time monitoring of Kubernetes resources.
* [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) ⭐ 350 | 🐛 10 | 🌐 Rust | 📅 2026-08-16 - A TUI for controlling and monitoring Framework Computers hardware.
* [logss](https://github.com/todoesverso/logss) ⭐ 297 | 🐛 3 | 🌐 Rust | 📅 2026-06-08 - A simple cli for logs splitting.
* [pumas](https://github.com/graelo/pumas) ⭐ 219 | 🐛 2 | 🌐 Rust | 📅 2026-08-20 - Power Usage Monitor for Apple Silicon.
* [parui](https://github.com/Vonr/parui) ⭐ 217 | 🐛 1 | 🌐 Rust | 📅 2026-01-18 - Simple TUI frontend for paru or yay.
* [erldash](https://github.com/sile/erldash) ⭐ 176 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - A simple, terminal-based Erlang dashboard.
* [mirro-rs](https://github.com/rtkay123/mirro-rs) ⭐ 117 | 🐛 23 | 🌐 Rust | 📅 2026-08-13 - An Arch Linux mirrorlist manager with a TUI.
* [slurmer](https://github.com/wjwei-handsome/Slurmer) ⭐ 110 | 🐛 13 | 🌐 Rust | 📅 2025-11-24 - A TUI for monitoring and managing SLURM jobs.
* [qmassa!](https://github.com/ulissesf/qmassa) ⭐ 107 | 🐛 0 | 🌐 Rust | 📅 2026-07-25 - Displays GPU devices usage stats on Linux.
* [winproc-tui](https://github.com/TX230/winproc-tui) ⭐ 106 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - Process monitoring tool with live metrics, time-series graphs, A/B comparison.
* [b4n](https://github.com/fioletoven/b4n) ⭐ 103 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 - A terminal-based tool for browsing Kubernetes resources.
* [quokka](https://github.com/dutradotdev/quokka) ⭐ 93 | 🐛 2 | 🌐 Rust | 📅 2026-07-27 - A TUI to inspect and tidy a USB-connected iPhone from macOS: storage, apps, media, syslog viewer.
* [tegratop](https://github.com/pythops/tegratop) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 - TUI monitoring tool (top like) for Nvidia jetson boards.
* [thinkfan-tui](https://github.com/karjonas/thinkfan-tui) ⭐ 78 | 🐛 1 | 🌐 Rust | 📅 2026-07-29 - A terminal-based Linux application for fan control and temperature monitoring on ThinkPad laptops.
* [lazyslurm](https://github.com/hill/lazyslurm) ⭐ 77 | 🐛 1 | 🌐 Rust | 📅 2026-08-09 - A lazygit-style terminal UI for Slurm. Monitor jobs, tail logs, and inspect nodes and partitions.
* [journalview](https://github.com/codervijo/journalview) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-05-20 - Journalctl log viewer.
* [napwatch](https://github.com/Tuguberk/napwatch) ⭐ 70 | 🐛 0 | 🌐 Rust | 📅 2026-07-19 - Diagnoses and controls macOS power/battery behavior: dark wakes, Power Nap, live drain rate, and per-process power draw.
* [reeve](https://github.com/yetidevworks/reeve) ⭐ 69 | 🐛 0 | 🌐 Rust | 📅 2026-08-24 - Manages a local web stack as per-user services: Caddy, Apache or nginx, per-vhost PHP-FPM versions, databases, local SSL, and wildcard DNS.
* [kubectl-watch](https://github.com/imuxin/kubectl-watch) ⭐ 64 | 🐛 4 | 🌐 Rust | 📅 2023-10-25 - A kubectl plugin to provide a pretty delta change view of being watched Kubernetes resources.
* [v4l-tui](https://github.com/sermuns/v4l-tui) ⭐ 31 | 🐛 5 | 🌐 Rust | 📅 2026-08-08 - Configure webcams on Linux via Video4Linux. TUI alternative to `v4l2-ctl`.
* [nightlight-tui](https://github.com/umutdinceryananer/nightlightd) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-08-22 - Dashboard for the nightlightd screen colour temperature daemon.
* [Aperture](https://github.com/stylebending/Aperture) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Diagnostic TUI for Windows power users.
* [gentooplz](https://github.com/JustRoccat/gentooplz) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - A live terminal dashboard for what Portage is building in real time.
* [mxmon](https://github.com/yusufmo1/mxmon) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-07-25 - Sudoless Apple Silicon monitor with per-process watts, a live chassis heat map, and a JSON contract for scripts and agents.

### 📟 Embedded

* [Tuitar](https://github.com/orhun/tuitar) ⭐ 526 | 🐛 6 | 🌐 Rust | 📅 2025-12-23 - A portable guitar training tool.
* [ComChan](https://github.com/Vaishnav-Sabari-Girish/ComChan) ⭐ 169 | 🐛 5 | 🌐 Rust | 📅 2026-08-25 - A minimal serial monitor with plotter TUI.
* [Phone-OS](https://github.com/Julien-cpsn/Phone-OS) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A modern Phone OS for ESP32 CYD (Cheap Yellow Display).
* [MTUI](https://github.com/inowattio/mtui) ⭐ 40 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - A very feature-rich Modbus Client.
* [Mnyaoo32](https://github.com/intuis/mnyaoo32) ⭐ 34 | 🐛 1 | 🌐 Rust | 📅 2025-05-10 - An eccentric way to consume IRC messages using ESP32.

### 🌌 Other

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 4,937 | 🐛 14 | 🌐 Rust | 📅 2026-08-25 - A TUI screensaver that visualizes Git commit history in your terminal.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,746 | 🐛 8 | 🌐 Rust | 📅 2026-08-10 - Document viewer for Microsoft Word files.
* [lemurs](https://github.com/coastalwhite/lemurs) ⭐ 1,350 | 🐛 80 | 🌐 Rust | 📅 2026-06-28 - A customizable TUI login manager for Linux and BSD.
* [hwatch](https://github.com/blacknon/hwatch) ⭐ 1,071 | 🐛 10 | 🌐 Rust | 📅 2026-08-10 - Alternative watch command with command history and diffs.
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 694 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 - A nyaa.si tui tool for browsing and downloading torrents.
* [ttysvr](https://github.com/cxreiff/ttysvr) ⭐ 489 | 🐛 4 | 🌐 Rust | 📅 2026-07-04 - Screen saver for your terminal.
* [tgv](https://github.com/zeqianli/tgv) ⭐ 484 | 🐛 12 | 🌐 Rust | 📅 2026-07-26 - Explore human genomes in the terminal.
* [cotp](https://github.com/replydev/cotp) ⭐ 385 | 🐛 6 | 🌐 Rust | 📅 2026-08-25 - Command-line TOTP/HOTP authenticator app.
* [tracker](https://github.com/ShenMian/tracker) ⭐ 315 | 🐛 1 | 🌐 Rust | 📅 2026-07-05 - A terminal-based real-time satellite tracking and orbit prediction application.
* [poketex](https://github.com/ckaznable/poketex) ⭐ 216 | 🐛 0 | 🌐 Rust | 📅 2026-05-05 - Simple Pokedex based on TUI.
* [maccel](https://github.com/Gnarus-G/maccel) ⭐ 197 | 🐛 12 | 🌐 Rust | 📅 2026-08-02 - A mouse acceleration driver for Linux, and a TUI to control some parameters.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 172 | 🐛 2 | 🌐 Rust | 📅 2025-09-17 - A free, simple weather TUI that pulls data without the need for an API key, account, or subscription.
* [theattyr](https://github.com/orhun/theattyr) ⭐ 170 | 🐛 1 | 🌐 Rust | 📅 2024-10-26 - A terminal theater for playing VT100 art and animations.
* [tenki](https://github.com/ckaznable/tenki) ⭐ 167 | 🐛 0 | 🌐 Rust | 📅 2026-07-23 - A tty-clock with weather effect.
* [mlbt](https://github.com/mlb-rs/mlbt) ⭐ 158 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 - A tui for the MLB Statcast API. Watch a live game using Gameday, or check scores, standings, and stats.
* [sigye](https://github.com/am2rican5/sigye) ⭐ 122 | 🐛 1 | 🌐 Rust | 📅 2026-08-13 - A terminal clock with FIGlet fonts, customizable themes, and animated backgrounds.
* [Inertia](https://github.com/aclfe/inertia) ⭐ 112 | 🐛 1 | 🌐 Rust | 📅 2026-07-19 - A 3D physics simulator in your terminal.
* [suzui-rs](https://github.com/thatdevsherry/suzui-rs) ⭐ 107 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Suzuki pre-obd2 engine data viewer.
* [hg-tui](https://github.com/kaixinbaba/hg-tui) ⭐ 97 | 🐛 3 | 🌐 Rust | 📅 2024-09-03 - TUI for viewing the hellogithub.com website.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 91 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [fractouille](https://github.com/PottierLoic/Fractouille) ⭐ 89 | 🐛 2 | 🌐 Rust | 📅 2026-03-19 - A simple fractal explorer running in your terminal.
* [confetty\_rs](https://github.com/Handfish/confetty_rs) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2024-02-08 - Particle system (fireworks, stars) rendered in the terminal.
* [lpl](https://github.com/SOF3/lpl) ⭐ 55 | 🐛 10 | 🌐 Rust | 📅 2025-04-05 - Command-line plotting for real-time CSV and JSON streams.
* [hncli](https://github.com/pierreyoda/hncli) ⭐ 50 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - Hacker News read-only TUI.
* [SeqTUI](https://github.com/ranwez-search/SeqTUI) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-03-10 - A terminal-based viewer and command-line toolkit for molecular sequences.
* [cube timer](https://github.com/paarthmadan/cube) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2021-09-12 - A tui for cube timing, written in Rust.
* [kanash](https://github.com/benoitlx/kanash) ⭐ 35 | 🐛 12 | 🌐 Rust | 📅 2026-08-03 - Learn Kana in your terminal.
* [seqsizzle](https://github.com/ChangqingW/SeqSizzle) ⭐ 25 | 🐛 1 | 🌐 Rust | 📅 2026-08-04 - A pager for viewing FASTQ files with fuzzy matching and coloring.
* [rsfrac](https://github.com/SkwalExe/rsfrac) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-04-23 - Terminal based fractal explorer, including Mandelbrot, Burning Ship, and Julia.
* [cpustate-tui](https://github.com/mkulke/cpustate-tui) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-02-19 - Baremetal program to visualize x86\_64 CPU state.
* [termCA](https://github.com/fabiooo4/termCA) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-03-03 - Interactive TUI Cellular Automata simulator.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
