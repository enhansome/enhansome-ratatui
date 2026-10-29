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

* <https://github.com/ratatui/ratatui/network/dependents> ⭐ 23,116 | 🐛 206 | 🌐 Rust | 📅 2026-10-28
* <https://github.com/fdehau/tui-rs/network/dependents?package_id=UGFja2FnZS0zMjE3MzkzMDMx> ⚠️ Archived
* <https://crates.io/crates/ratatui/reverse_dependencies>
* <https://crates.io/crates/tui/reverse_dependencies>

## 📦 Libraries

### 🏗️ Frameworks

* [burn](https://github.com/tracel-ai/burn) ⭐ 16,193 | 🐛 163 | 🌐 Rust | 📅 2026-10-29 - Comprehensive Deep Learning framework in Rust.
* [ratzilla](https://github.com/ratatui/ratzilla) ⭐ 1,476 | 🐛 50 | 🌐 Rust | 📅 2026-10-23 - Build terminal-themed web applications with Ratatui and WebAssembly.
* [mousefood](https://github.com/ratatui/mousefood) ⭐ 1,345 | 🐛 21 | 🌐 Rust | 📅 2026-10-28 - An embedded-graphics backend for Ratatui.
* [bevy\_ratatui\_camera](https://github.com/cxreiff/bevy_ratatui_camera) ⭐ 338 | 🐛 6 | 🌐 Rust | 📅 2025-11-17 - A bevy plugin for rendering your bevy app to the terminal using ratatui.
* [egui-ratatui](https://github.com/gold-silver-copper/egui_ratatui) ⭐ 214 | 🐛 4 | 🌐 Rust | 📅 2026-04-16 - A ratatui backend that is also an egui widget. Deploy on web with WebAssembly or ship natively with bevy, macroquad, or eframe.
* [ratatuefi](https://github.com/sermuns/ratatuefi) ⭐ 165 | 🐛 0 | 🌐 Rust | 📅 2026-07-06 - A Ratatui backend for drawing terminal UIs in pre-boot UEFI environments.
* [ratatui-wgpu](https://github.com/Jesterhearts/ratatui-wgpu) ⭐ 134 | 🐛 5 | 🌐 Rust | 📅 2026-08-06 - A wgpu based rendering backend for ratatui.
* [webatui](https://github.com/TylerBloom/webatui) ⭐ 129 | 🐛 4 | 🌐 Rust | 📅 2024-09-30 - An integration between the Yew and Ratatui crates for making TUI-themed WebAssembly webapps.
* [soft\_ratatui](https://github.com/gold-silver-copper/soft_ratatui) ⭐ 106 | 🐛 0 | 🌐 Rust | 📅 2026-04-23 - A software rendering backend for ratatui. No GPU required. TUI everywhere.
* [ratatui-uefi](https://github.com/reubeno/tui-uefi) ⭐ 103 | 🐛 3 | 🌐 Rust | 📅 2026-08-31 - A Ratatui backend for drawing terminal UIs in pre-boot UEFI environments.
* [schemaui](https://github.com/YuniqueUnic/schemaui) ⭐ 98 | 🐛 2 | 🌐 Rust | 📅 2026-10-19 - Turn JSON Schemas into TUIs and web UIs with real-time validation.
* [rat-salsa](https://github.com/thscharler/rat-salsa) ⭐ 65 | 🐛 9 | 🌐 Rust | 📅 2026-10-29 - An event-queue for ratatui with tasks, timers, application events, focus handling, dialog windows.
* [ratatui-kit](https://github.com/yexiyue/ratatui-kit) ⭐ 55 | 🐛 0 | 🌐 Rust | 📅 2026-10-11 - A React-style component framework for Ratatui with hooks, routing, async state, input layers, and reusable components.
* [crepuscularity](https://github.com/tschk/crepuscularity) ⭐ 46 | 🐛 10 | 🌐 Rust | 📅 2026-10-29 - One UI codebase for desktop, web, mobile, terminal, browser extensions, and embedded devices. Write React JSX or our lightweight DSL, get GPUI, Ratatui, SwiftUI, LVGL, and more. Batteries included.
* [raclettui](https://github.com/ishrut/raclettui) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A wayland layer shell window implementing the ratatui backend with cpu and wgpu rendering.
* [dumo](https://github.com/iddey/dumo) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 - An embedded-graphics backend that is built on [mplusfonts](https://github.com/iddey/mplusfonts) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-03-31 and has kanji support.
* [xnano](https://github.com/hsaeed3/xnano) ⭐ 21 | 🐛 9 | 🌐 Python | 📅 2026-10-26 - A declarative terminal framework for Python built on ratatui & ratzilla.
* [ratatui-minecraft](https://github.com/janTatesa/ratatui-minecraft) ⭐ 16 | 🐛 1 | 🌐 Rust | 📅 2025-06-24 - A Ratatui backend for rendering terminal UIs inside Minecraft via [valence-screens](https://github.com/White-145/valence-screens) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-20.
* [rlt](https://crates.io/crates/rlt) - A universal load testing framework for Rust, with real-time tui support.
* [tui-react](https://crates.io/crates/tui-react) - TUI widgets using a react-like paradigm.
* [tui-realm](https://crates.io/crates/tuirealm) - A ratatui framework inspired by Elm and React.
* [widgetui](https://crates.io/crates/widgetui) - A bevy-like widget system for ratatui and crossterm.

### 🧩 Widgets

* [edtui](https://github.com/preiter93/edtui) ⭐ 162 | 🐛 5 | 🌐 Rust | 📅 2026-10-24 - A Vim-inspired terminal editor.
* [ratatui-splash-screen](https://github.com/orhun/ratatui-splash-screen) ⭐ 158 | 🐛 1 | 🌐 Rust | 📅 2026-10-26 - Turns any image into a splash screen.
* [ratatui-code-editor](https://github.com/vipmax/ratatui-code-editor) ⭐ 120 | 🐛 9 | 🌐 Rust | 📅 2026-07-07 - A code editor with syntax highlighting powered by tree-sitter.
* [ratatui-explorer](https://github.com/tatounee/ratatui-explorer) ⭐ 95 | 🐛 4 | 🌐 Rust | 📅 2026-03-06 - A simple file-explorer library.
* [tui-rain](https://github.com/levilutz/tui-rain) ⭐ 79 | 🐛 4 | 🌐 Rust | 📅 2024-11-30 - A widget to generate various rain effects.
* [tui-menu](https://github.com/shuoli84/tui-menu) ⭐ 57 | 🐛 7 | 🌐 Rust | 📅 2025-12-30 - A menu component.
* [ratatui-markdown](https://github.com/celestia-island/ratatui-markdown) ⭐ 47 | 🐛 1 | 🌐 Rust | 📅 2026-10-26 - A Rust library providing markdown rendering, Mermaid diagrams, syntax highlighting, collapsible JSON/TOML tree views, and a rich hybrid scroll system.
* [term-rustdoc](https://github.com/zjp-CN/term-rustdoc) ⭐ 34 | 🐛 16 | 🌐 Rust | 📅 2025-04-20 - A TUI for Rust docs that aims to improve the UX on tree view and generic code.
* [tui-shimmer](https://github.com/vinhnx/tui-shimmer) ⭐ 30 | 🐛 0 | 🌐 Rust | 📅 2026-10-23 - A shimmer text effect.
* [tui-globe](https://github.com/d10n/tui-globe) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 - A 3D globe widget rendered in the terminal with Braille characters.
* [ratatui-form](https://github.com/DavidLiedle/ratatui-form) ⭐ 21 | 🐛 4 | 🌐 Rust | 📅 2026-04-13 - A form library.
* [ratatui-stacked-bar](https://github.com/zeqianli/ratatui-stacked-bar) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-04-07 - A stacked area chart.
* [ratatui-tournament](https://github.com/philipgreat/ratatui-tournament) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-07 - A widget for rendering single-elimination tournament brackets in the terminal.
* [boxmaid](https://crates.io/crates/boxmaid) - Renders Mermaid diagrams as Unicode or ASCII text with themed, scrollable Ratatui widgets.
* [hyperrat](https://crates.io/crates/hyperrat) - Clickable terminal links.
* [malevich](https://crates.io/crates/malevich) - A plotting widget: line, scatter, bar, histogram, heatmap, box plot, violin, and more, with automatic axes and millions of points.
* [rat-widget](https://crates.io/crates/rat-widget) - Widgets for data-input (text-input, date- and number-input, text-area, checkbox, choice, radiobutton, slider, calendar), structural widgets (view, split, tabbed, multi-page), a table widget for large data-sets, a file-dialog, a menubar+sub-menus, a status-bar and some more. With builtin crossterm event-handling and focus-handling.
* [Ratagrid](https://crates.io/crates/ratagrid) - A typed data grid with sorting, search, selection, column resizing, and client or external pagination.
* [ratatui-cheese](https://crates.io/crates/ratatui-cheese) - Bubbletea-inspired widgets, including spinner, help, tree, paginator, and list.
* [ratatui-comfy-tabs](https://crates.io/crates/ratatui-comfy-tabs) - A feature-rich tab navigation for TUI. Highly customizable.
* [ratatui-comfy-toaster](https://crates.io/crates/ratatui-comfy-toaster) - An advanced toast-notification engine for terminal UI applications.
* [ratatui-fretboard](https://crates.io/crates/ratatui-fretboard) - Displays musical note positions on a fretboard.
* [ratatui-image](https://crates.io/crates/ratatui-image) - Displays images using Sixel graphics or Unicode half-blocks.
* [ratatui-textarea](https://crates.io/crates/ratatui-textarea) - A simple yet powerful editor; fork of `tui-textarea`.
* [ratatui-toaster](https://crates.io/crates/ratatui-toaster) - An extremely lightweight toast engine.
* [ratatui-widgettable](https://crates.io/crates/ratatui-widgettable) - A table widget whose cells can contain arbitrary widgets.
* [ratatui-wireframe](https://crates.io/crates/ratatui-wireframe) -  A widget for rendering and rotating 3D wireframe models.
* [ratiform](https://crates.io/crates/ratiform) - A stateful form widget with typed field identifiers, so your data model stays your own, not the library's.
* [throbber-widgets-tui](https://crates.io/crates/throbber-widgets-tui) - A widget that displays throbber.
* [tui-additions](https://crates.io/crates/tui-additions) - Additions to the rust tui crate.
* [tui-bar-graph](https://crates.io/crates/tui-bar-graph) - A bar graph widget for Ratatui.
* [tui-big-text](https://crates.io/crates/tui-big-text) - Displays big text using the `font8x8` crate.
* [tui-box-text](https://crates.io/crates/tui-box-text) - Displays text surrounded by a box.
* [tui-cards](https://crates.io/crates/tui-cards) - Widgets for displaying cards.
* [tui-equalizer](https://crates.io/crates/tui-equalizer) - An equalizer widget for Ratatui.
* [tui-checkbox](https://crates.io/crates/tui-checkbox) - A customizable checkbox.
* [tui-dialog](https://crates.io/crates/tui-dialog) - A widget for entering a single line of text in a dialog.
* [tui-input](https://crates.io/crates/tui-input) - A headless input library for TUI apps.
* [tui-logger](https://crates.io/crates/tui-logger) - A logger with a smart log viewer.
* [tui-nodes](https://crates.io/crates/tui-nodes) - Visualize node graphs.
* [tui-overlay](https://crates.io/crates/tui-overlay) - A composable overlay widget with drawers, modals, popovers, and toasts from a single configurable primitive.
* [tui-piechart](https://crates.io/crates/tui-piechart) - A configurable, colorful piechart widget that comes in standard and high resolution.
* [tui-popup](https://crates.io/crates/tui-popup) - A popup component.
* [tui-prompts](https://crates.io/crates/tui-prompts) - A library for building interactive prompts.
* [tui-qrcode](https://crates.io/crates/tui-qrcode) - A QR code widget for Ratatui.
* [tui-scrollbar](https://crates.io/crates/tui-scrollbar) - A scrollbar widget for Ratatui.
* [tui-scrollview](https://crates.io/crates/tui-scrollview) - A container that provides a scrolling view at a larger area.
* [tui-skeleton](https://crates.io/crates/tui-skeleton) - A library of placeholder widgets that pulse, sweep, or shimmer while your content loads.
* [tui-slider](https://crates.io/crates/tui-slider) - A highly customizable slider widget for both horizontal and vertical orientations.
* [tui-tabs](https://crates.io/crates/tui-tabs) - A tab navigation widget with individually bordered boxes and rounded corners.
* [tui-term](https://crates.io/crates/tui-term) - Embeds interactive terminal sessions.
* [tui-textarea](https://crates.io/crates/tui-textarea) - A simple yet powerful terminal text editor.
* [tui-tree-widget](https://crates.io/crates/tui-tree-widget) - A tree view.
* [tui-widget-list](https://crates.io/crates/tui-widget-list) - A versatile list implementation.

### 🔧 Utilities

* [tachyonfx](https://github.com/ratatui/tachyonfx) ⭐ 1,313 | 🐛 8 | 🌐 Rust | 📅 2026-10-24 - An animation and visual-effects library for Ratatui applications.
* [bevy\_ratatui](https://github.com/ratatui/bevy_ratatui) ⭐ 173 | 🐛 8 | 🌐 Rust | 📅 2026-10-12 - A Rust crate to use Ratatui in a Bevy App.
* [ratatui-garnish](https://github.com/franklaranja/ratatui-garnish) ⭐ 49 | 🐛 0 | 🌐 Rust | 📅 2025-10-14 - A powerful composition system for Ratatui widgets.
* [ratatui-interact](https://github.com/Brainwires/ratatui-interact) ⭐ 41 | 🐛 1 | 🌐 Rust | 📅 2026-04-02 - Interactive TUI components for Ratatui with focus management and mouse support.
* [coolor](https://github.com/Canop/coolor) ⭐ 33 | 🐛 2 | 🌐 Rust | 📅 2025-05-09 - Tiny color conversion library for TUI application builders.
* [termprofile](https://github.com/aschey/termprofile) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - Detect and handle terminal color/styling support. Supports converting Ratatui color and style objects.
* [tui-syntax-highlight](https://github.com/aschey/tui-syntax-highlight) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-10-28 - Syntax highlighting for code blocks.
* [ggsci-ratatui](https://github.com/nanxstats/ggsci-rs) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-07-31 - Scientific and sci-fi color palettes from ggsci as Ratatui colors and styles, in truecolor or ANSI-256 mode.
* [ratatui-wasm](https://github.com/yunuservices/ratatui-wasm) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-10-12 - Load Ratatui widgets from WebAssembly plugins at runtime, with host-controlled capabilities and fuel and memory limits.
* [ansi-to-tui](https://crates.io/crates/ansi-to-tui) - A library to convert ansi color coded text into `ratatui::text::Text`.
* [color-to-tui](https://crates.io/crates/color-to-tui) - Parse colors and convert them to `ratatui::style::Colors`.
* [opaline](https://crates.io/crates/opaline) - Token-based theme engine for Ratatui with gradients, 20 builtin themes, user theme discovery, and a reusable theme selector widget.
* [ratatui-input-manager](https://crates.io/crates/ratatui-input-manager) - A macro for creating declarative update handlers in Elm style apps, supporting crossterm, termion and termwiz.
* [terminput](https://crates.io/crates/terminput) - An abstraction over various backends that provide input events.
* [tui-pantry](https://crates.io/crates/tui-pantry) - Component-driven development tool for ratatui widgets, similar to Storybook.

### 🔗 Bindings

* [jatatui](https://github.com/oyvindberg/jatatui) ⭐ 289 | 🐛 2 | 🌐 Java | 📅 2026-08-22 - A Java port of ratatui.
* [pyratatui](https://github.com/programmersd21/pyratatui) ⭐ 173 | 🐛 0 | 🌐 Rust | 📅 2026-09-18 - Python bindings for Ratatui, implemented in Rust with PyO3.
* [ex\_ratatui](https://github.com/mcass19/ex_ratatui) ⭐ 128 | 🐛 0 | 🌐 Elixir | 📅 2026-10-27 - Elixir bindings for ratatui.
* [ratatui-ffi](https://github.com/holo-q/ratatui-ffi) ⭐ 56 | 🐛 2 | 🌐 Rust | 📅 2026-06-04 - Foreign Function Interface bindings for Ratatui.
* [ratatui-py](https://github.com/holo-q/ratatui-py) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2026-06-04 - Python bindings for ratatui.
* [Ratatui.cs](https://github.com/holo-q/Ratatui.cs) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2026-06-04 - C# bindings for ratatui.
* [ratatui-ts](https://github.com/holo-q/ratatui-ts) ⭐ 14 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - TypeScript bindings for ratatui.
* [ratatui-go](https://github.com/holo-q/ratatui-go) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-09-12 - Go bindings for ratatui.
* [ratatui\_ruby](https://sr.ht/~kerrick/ratatui_ruby/) - Ruby bindings for ratatui.

## 💻 Apps

### ⌨️ Development Tools

#### Source Control and Collaboration

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,609 | 🐛 354 | 🌐 Rust | 📅 2026-10-06 - Terminal UI for Git.
* [wrkflw](https://github.com/bahdotsh/wrkflw) ⭐ 3,336 | 🐛 15 | 🌐 Rust | 📅 2026-09-08 - A TUI for validating and executing GitHub Actions workflows locally.
* [gitu](https://github.com/altsem/gitu) ⭐ 2,942 | 🐛 61 | 🌐 Rust | 📅 2026-10-28 - A TUI Git client inspired by Magit.
* [serie](https://github.com/lusingander/serie) ⭐ 2,167 | 🐛 24 | 🌐 Rust | 📅 2026-10-25 - A rich Git commit graph in your terminal.
* [lazyjj](https://github.com/Cretezy/lazyjj) ⭐ 1,227 | 🐛 45 | 🌐 Rust | 📅 2026-09-24 - A TUI for the Jujutsu version-control system.
* [drydock](https://github.com/yetidevworks/drydock) ⭐ 323 | 🐛 0 | 🌐 Rust | 📅 2026-10-19 - A live dashboard for a fleet of Git repos, showing what's uncommitted, unpushed, and unreleased across all of them.
* [giff](https://github.com/bahdotsh/giff) ⭐ 276 | 🐛 9 | 🌐 Rust | 📅 2026-04-23 - A TUI for Git diffs with interactive rebase support.
* [deadbranch](https://github.com/armgabrielyan/deadbranch) ⭐ 235 | 🐛 2 | 🌐 Rust | 📅 2026-03-30 - A TUI for cleaning stale Git branches safely.
* [Livediff](https://github.com/SoCkEt7/Livediff) ⭐ 235 | 🐛 9 | 🌐 Rust | 📅 2026-10-25 - Real-time terminal file diff monitoring TUI.
* [glim](https://github.com/junkdog/glim) ⭐ 232 | 🐛 16 | 🌐 Rust | 📅 2025-10-13 - Monitor GitLab continuous integration and delivery pipelines and projects.
* [gwm](https://github.com/kbrdn1/gwm-cli) ⭐ 149 | 🐛 18 | 🌐 Rust | 📅 2026-10-27 - A Git worktree manager: CLI and TUI in one binary, native libgit2, per-repo declarative bootstrap, and AI agent session tracking.
* [gitv](https://github.com/jayanaxhf/gitv) ⭐ 117 | 🐛 12 | 🌐 Rust | 📅 2026-09-24 - A beautiful, feature-rich and performant terminal client for GitHub issues.
* [nomad](https://github.com/JosephLai241/nomad) ⭐ 76 | 🐛 9 | 🌐 Rust | 📅 2023-05-10 - Customizable next-gen tree command with Git integration and TUI.
* [git-time-machine](https://github.com/dinakars777/git-time-machine) ⭐ 72 | 🐛 2 | 🌐 Rust | 📅 2026-05-31 - Visual Git reflog TUI for undoing Git mistakes.
* [gimoji](https://github.com/zeenix/gimoji) ⭐ 52 | 🐛 7 | 🌐 Rust | 📅 2026-10-28 - Makes it easy to add emojis to your Git commit messages.
* [blippy](https://github.com/AksharP5/blippy) ⭐ 25 | 🐛 1 | 🌐 Rust | 📅 2026-10-27 - A keyboard-first TUI for GitHub issues and pull requests.
* [Gitside](https://github.com/dev-bhaskar8/gitside) ⭐ 21 | 🐛 10 | 🌐 Rust | 📅 2026-08-15 - A responsive, mouse-friendly Git source-control TUI for full terminals and narrow tmux panes.
* [forgetop](https://github.com/magna-nz/forgetop) ⭐ 17 | 🐛 4 | 🌐 Rust | 📅 2026-10-15 - Pull requests, work items, and CI pipelines from GitHub, GitLab, Azure DevOps, Bitbucket, Linear, and Jira in one queue.
* [gitty](https://github.com/VedangP57/gitty) ⭐ 16 | 🐛 1 | 🌐 Rust | 📅 2026-10-19 - A terminal Git client with the GitHub Desktop experience: history, line staging, fetch, pull and push.
* [rootle](https://github.com/rootledev/rootle) ⭐ 5 | 🐛 7 | 🌐 Rust | 📅 2026-10-23 - A modal TUI for browsing GitHub and other source-control services with column views and syntax-highlighted previews.
* [runline](https://github.com/programmersd21/runline) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-10-12 - A keyboard-first terminal client for watching and acting on GitHub Actions runs.
* [ComfyGit](https://github.com/comfy-home/ComfyGit) ⭐ 3 | 🐛 7 | 🌐 Rust | 📅 2026-10-25 - All-In-One: Centralised multi-project management, Changelog generator, Version bumper & CLI tool introducing a new ComfyGitFlow.
* [git-barber](https://github.com/rekurt/git-barber) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-10-14 - A TUI for cleaning up merged Git branches, including squash and rebase merges.

#### Code Search, Editing, and Review

* [scooter](https://github.com/thomasschafer/scooter) ⭐ 1,304 | 🐛 13 | 🌐 Rust | 📅 2026-10-26 - Interactive find and replace in the terminal.
* [Serpl](https://github.com/yassinebridi/serpl) ⭐ 864 | 🐛 19 | 🌐 Rust | 📅 2026-10-10 - A simple terminal UI for search and replace, ala VS Code.
* [igrep](https://github.com/konradsz/igrep) ⭐ 847 | 🐛 10 | 🌐 Rust | 📅 2026-09-09 - Interactive Grep.
* [repgrep](https://github.com/acheronfail/repgrep) ⭐ 543 | 🐛 1 | 🌐 Rust | 📅 2026-09-02 - An interactive replacer for ripgrep that makes it easy to find and replace across files on the command line.
* [blogr](https://github.com/bahdotsh/blogr) ⭐ 343 | 🐛 13 | 🌐 Rust | 📅 2026-06-08 - A terminal-based static site generator with a TUI editor for writing blog posts.
* [Mitos](https://github.com/mitos-editor/mitos) ⭐ 316 | 🐛 92 | 🌐 Rust | 📅 2026-10-29 - A selection-first modal text editor with multiple selections, built-in language server support, and Tree-sitter syntax highlighting.
* [rgx](https://github.com/brevity1swos/rgx) ⭐ 242 | 🐛 0 | 🌐 Rust | 📅 2026-10-27 - A terminal regex debugger with real-time matching, 3 engines, capture group highlighting, replace mode, and plain-English explanations.
* [Rustlens](https://github.com/yashksaini-coder/Rustlens) ⭐ 157 | 🐛 0 | 🌐 Rust | 📅 2026-04-02 - A TUI Rust codebase inspector to browse functions, structs, enums, traits, and more.
* [codemark](https://github.com/DanielCardonaRojas/codemark) ⭐ 136 | 🐛 14 | 🌐 Rust | 📅 2026-10-29 - A semantic code bookmarking system for humans and agents.
* [regect](https://github.com/kloki/regect) ⭐ 97 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A regex101 like tool for the cli.
* [ygrep](https://github.com/yetidevworks/ygrep) ⭐ 63 | 🐛 2 | 🌐 Rust | 📅 2026-10-21 - A fast, local, indexed code-search tool with a TUI for AI coding assistants.
* [image-auditor](https://github.com/0franco/image-auditor) ⭐ 45 | 🐛 0 | 🌐 Rust | 📅 2026-07-05 - A TUI for finding and fixing website image-performance issues such as layout shifts, lazy loading, WebP, and responsive images.
* [lingora-tui](https://github.com/nigeleke/lingora) ⭐ 35 | 🐛 2 | 🌐 Rust | 📅 2026-10-26 - Browse, compare and validate Fluent i18n files.
* [blur](https://github.com/castlesp5/blur) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-10-17 - A Vim-inspired terminal text editor written in Rust.
* [termi](https://github.com/tuna4ll/termi) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-09-17 - A modal terminal code editor.
* [VLE](https://github.com/tuffy/vle) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A lightweight text editor.
* [declutter](https://github.com/NikolajMosbaek/declutter-diff) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-10-22 - A diff viewer for reviewing AI-written code that hides comments, tests, imports, logging and formatting changes with one key each.

#### APIs, Databases, Build, and Debugging

* [oha](https://github.com/hatoo/oha) ⭐ 10,645 | 🐛 58 | 🌐 Rust | 📅 2026-10-26 - An HTTP load generator with a real-time terminal UI.
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,389 | 🐛 15 | 🌐 Rust | 📅 2026-10-29 - A database management TUI for Postgres.
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,742 | 🐛 20 | 🌐 Rust | 📅 2026-10-19 - A feature-full TUI API client for your terminal.
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,326 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 - Cross-platform TUI database management tool.
* [hotpath-rs](https://github.com/hotpath-rs/hotpath) ⭐ 1,911 | 🐛 8 | 🌐 Rust | 📅 2026-10-29 - A Rust profiler for CPU, memory, async, SQL, I/O, and lock contention with a live TUI dashboard.
* [BugStalker](https://github.com/godzie44/BugStalker) ⭐ 1,426 | 🐛 16 | 🌐 Rust | 📅 2026-10-10 - Modern rust debugger for Linux x86-64.
* [openapi-tui](https://github.com/zaghaghi/openapi-tui) ⭐ 1,345 | 🐛 10 | 🌐 Rust | 📅 2026-05-14 - A terminal UI for browsing and calling APIs from OpenAPI specifications.
* [desed](https://github.com/SoptikHa2/desed) ⭐ 1,220 | 🐛 8 | 🌐 Rust | 📅 2026-05-16 - Debugging tool for sed scripts.
* [Maelstrom](https://github.com/maelstrom-software/maelstrom) ⭐ 736 | 🐛 188 | 🌐 Rust | 📅 2026-09-26 - A fast test runner that runs every test in its own container locally or distributed.
* [Surfpool](https://github.com/solana-foundation/surfpool) ⭐ 619 | 🐛 62 | 🌐 Rust | 📅 2026-10-28 - A local-first Solana development environment with mainnet state, infrastructure as code and transaction debugging.
* [tracexec](https://github.com/kxxt/tracexec) ⭐ 447 | 🐛 26 | 🌐 Rust | 📅 2026-10-26 - A terminal tool for tracing which programs and commands are executed.
* [sabiql](https://github.com/riii111/sabiql) ⭐ 317 | 🐛 8 | 🌐 Rust | 📅 2026-10-24 - Fast, driverless, Vim-first database TUI with safe editing and ER diagrams.
* [envx](https://github.com/mikeleppane/envx) ⭐ 233 | 🐛 6 | 🌐 Rust | 📅 2025-09-19 - Environment variable manager for developers, featuring an intuitive TUI.
* [wireman](https://github.com/preiter93/wireman) ⭐ 181 | 🐛 8 | 🌐 Rust | 📅 2026-10-21 - A terminal client for calling gRPC services.
* [ratifact](https://github.com/adolfousier/ratifact) ⭐ 92 | 🐛 0 | 🌐 Rust | 📅 2026-09-21 - Track and manage build artifacts from multiple programming languages.
* [tongo](https://github.com/drewzemke/tongo) ⭐ 75 | 🐛 3 | 🌐 Rust | 📅 2026-10-29 - A TUI for MongoDB.
* [cargo-selector](https://github.com/lusingander/cargo-selector) ⭐ 74 | 🐛 1 | 🌐 Rust | 📅 2026-09-02 - Cargo subcommand to select and execute binary/example targets.
* [get\_blessed\_rs](https://github.com/josueBarretogit/get_blessed_rs) ⭐ 50 | 🐛 0 | 🌐 Rust | 📅 2024-06-29 - Get the best crates for your rust projects, curated by blessed.rs.
* [deputui](https://github.com/twiddler/deputui) ⭐ 37 | 🐛 5 | 🌐 Rust | 📅 2026-09-28 - Review and install JavaScript package updates from npm.
* [depot-rs](https://github.com/quietpigeon/depot-rs) ⭐ 25 | 🐛 2 | 🌐 Rust | 📅 2025-10-04 - A TUI for managing crates.
* [TaskUI](https://github.com/thmshmm/taskui) ⭐ 24 | 🐛 1 | 🌐 Rust | 📅 2024-08-11 - Simple Terminal UI for Task / taskfile.dev.
* [therapist](https://github.com/M-Komorek/therapist) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-10-19 - A lightweight TUI log viewer for multi-GB files with vim keys, grep tabs and phrase highlights.
* [agx](https://github.com/brevity1swos/agx) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-10-27 - A step-through debugger for AI agent execution traces.
* [raygun](https://github.com/yetidevworks/raygun) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-10-16 - A terminal-based receiver for Spatie's Ray debugger, compatible with the Ray HTTP protocol used by PHP, Laravel, and Grav.

### 🤖 AI and Agents

* [OpenBitFun](https://github.com/GCWing/OpenBitFun) ⭐ 3,305 | 🐛 126 | 🌐 Rust | 📅 2026-10-29 - An open-source desktop workspace for general-purpose AI agents.
* [Stakpak](https://github.com/stakpak/agent) ⭐ 1,836 | 🐛 44 | 🌐 Rust | 📅 2026-07-06 - AI DevOps agent to help you secure, deploy, and maintain production-ready infrastructure.
* [opencrabs](https://github.com/opencrabs/opencrabs) ⭐ 1,017 | 🐛 0 | 🌐 Rust | 📅 2026-10-29 - An all-in-one AI agent for the terminal with TUI, CLI, and daemon modes.
* [herdr-reviewr](https://github.com/persiyanov/herdr-reviewr) ⭐ 957 | 🐛 50 | 🌐 Rust | 📅 2026-10-28 - A code-review pane for coding agents.
* [VT Code](https://github.com/vinhnx/vtcode) ⭐ 894 | 🐛 2 | 🌐 Rust | 📅 2026-10-26 - An open-source Rust coding agent for the terminal.
* [Oatmeal](https://github.com/dustinblackman/oatmeal) ⭐ 771 | 🐛 30 | 🌐 Rust | 📅 2024-06-01 - Terminal UI to chat with large language models (LLM) using different model backends, and integrations with your favourite editors!
* [tenere](https://github.com/pythops/tenere) ⭐ 686 | 🐛 11 | 🌐 Rust | 📅 2026-05-10 - A terminal chat interface for large language models, written in Rust.
* [patent](https://github.com/r14dd/patent) ⭐ 558 | 🐛 6 | 🌐 Rust | 📅 2026-10-26 - A prior-art search for developer-tool ideas with an AI-generated verdict.
* [pixtuoid](https://github.com/IvanWng97/pixtuoid) ⭐ 525 | 🐛 3 | 🌐 Rust | 📅 2026-10-29 - Live pixel-art office for AI coding agents.
* [models](https://github.com/reyamira/models) ⭐ 517 | 🐛 8 | 🌐 Rust | 📅 2026-10-29 - A TUI for browsing AI models, benchmarks, and coding agents.
* [claude-code-rust](https://github.com/srothgan/claude-code-rust) ⭐ 273 | 🐛 2 | 🌐 Rust | 📅 2026-10-27 - A native terminal interface for Claude Code that renders inline into the terminal's scrollback.
* [llmtrim](https://github.com/fkiene/llmtrim) ⭐ 258 | 🐛 12 | 🌐 Rust | 📅 2026-10-20 - A local proxy that compresses large-language-model API requests to reduce token costs, with a dashboard for per-source costs and context usage.
* [claudectl](https://github.com/mercurialsolo/claudectl) ⭐ 203 | 🐛 101 | 🌐 Rust | 📅 2026-10-23 - Mission control for multiple Claude Code sessions with live dashboard, cost tracking, and budget enforcement.
* [toktop](https://github.com/htin1/toktop) ⭐ 174 | 🐛 5 | 🌐 Rust | 📅 2025-12-07 - A terminal dashboard for monitoring OpenAI and Anthropic token usage and costs.
* [thurbox](https://github.com/Thurbeen/thurbox) ⭐ 115 | 🐛 18 | 🌐 Rust | 📅 2026-10-28 - A TUI orchestrator for running multiple AI coding agents (Claude Code, Codex, and others) in persistent tmux sessions.
* [Martty](https://github.com/openma-ai/Martty) ⭐ 81 | 🐛 8 | 🌐 Rust | 📅 2026-10-27 - An extensible Rust/ratatui terminal client for DeepSeek Harness and ACP-compatible coding agents, with plugins, tools, subagents, and durable sessions.
* [opencode stats](https://github.com/Cateds/opencode-stats) ⭐ 79 | 🐛 4 | 🌐 Rust | 📅 2026-08-04 - A terminal dashboard for OpenCode usage statistics and cost breakdowns.
* [voff](https://github.com/orhun/voff) ⭐ 75 | 🐛 2 | 🌐 Rust | 📅 2026-10-28 - A workflow builder for coding agents with coordinated teams, parallel task execution, and live workflow monitoring.
* [coven](https://github.com/OpenCoven/coven) ⭐ 73 | 🐛 101 | 🌐 Rust | 📅 2026-10-28 - Local-first runtime and TUI for running Codex, Claude Code, and other coding agents as project-scoped PTY sessions.
* [nereid](https://github.com/bnomei/nereid) ⭐ 68 | 🐛 0 | 🌐 Rust | 📅 2026-07-11 - Create and explore Mermaid diagrams with AI agents through a terminal UI and Model Context Protocol server.
* [hedos](https://github.com/theiskaa/hedos) ⭐ 56 | 🐛 3 | 🌐 Rust | 📅 2026-10-24 - A terminal shelf for the local AI models already on your machine, with a built-in OpenAI-compatible gateway.
* [SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) ⭐ 52 | 🐛 9 | 🌐 Rust | 📅 2026-10-29 - Lightning fast terminal native agent harness with tools, extensions and subagents. 15MB, 2ms boot.
* [bosun](https://github.com/yetidevworks/bosun) ⭐ 47 | 🐛 1 | 🌐 Rust | 📅 2026-10-26 - A tmux-native TUI for orchestrating AI coding agent sessions (Claude Code, Codex) with live previews and per-session state.
* [commandOK](https://github.com/64bit/commandOK) ⭐ 45 | 🐛 1 | 🌐 Rust | 📅 2026-06-16 - A Spotlight-like terminal command generator powered by major large-language-model providers.
* [Proqi](https://github.com/oborchers/proqi) ⭐ 43 | 🐛 10 | 🌐 Rust | 📅 2026-10-25 - A terminal-native prompt composer for developers working with coding agents.
* [agent-console](https://github.com/buhuipao/agent-console) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-10-14 - A local dashboard for Codex and Claude Code.
* [amtr](https://github.com/arian-shamaei/anthropometer) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-10-15 - A btop-style TUI that renders a Claude Code session's live context window as a memory map, with tool and file traffic, cache economics, and a compiled PDF report.
* [crmux](https://github.com/maedana/crmux) ⭐ 28 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - A TUI viewer for monitoring and managing multiple Claude Code sessions in tmux.
* [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-09-17 - A local-first memory system for AI agents with SQLite full-text search, auditing, forgetting, consolidation, and a Ratatui operator console.
* [raymon](https://github.com/bnomei/raymon) ⭐ 18 | 🐛 3 | 🌐 Rust | 📅 2026-07-01 - A terminal UI and Model Context Protocol (MCP) server for receiving and searching Ray-style debug logs.
* [ilmari](https://github.com/bnomei/ilmari) ⭐ 17 | 🐛 5 | 🌐 Rust | 📅 2026-08-08 - A tmux popup dashboard for monitoring AI coding agents.
* [gmsg](https://github.com/olorikendrick/gmsg) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Generate, edit, and commit AI-powered Git commit messages from a single TUI.
* [partly-claudy](https://github.com/taho-inc/partly-claudy) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-04-28 - Terminal view of Claude status page (status.claude.com).
* [LimitDeck](https://github.com/rockythink/limitdeck) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-09-20 - A compact, privacy-safe terminal dashboard for AI coding subscription limits.
* [Reeve](https://github.com/Dancode-188/reeve) ⭐ 9 | 🐛 9 | 🌐 Rust | 📅 2026-09-06 - A terminal cockpit for AI agents: watch a run live, score it, and step in when it goes sideways.
* [cc-code](https://github.com/cc-claws/cc-code) ⭐ 8 | 🐛 44 | 🌐 Rust | 📅 2026-10-29 - Fast, lightweight Claude Code alternative built in Rust with Ratatui TUI, ACP protocol support, and multi-model compatibility.
* [Forge](https://github.com/NorviaLabs/forge) ⭐ 8 | 🐛 7 | 🌐 Rust | 📅 2026-10-29 - An AI coding agent that unifies an agent, code editor, and shell in a single keyboard-driven terminal workspace.
* [lumen](https://github.com/blackopsrepl/lumen) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2026-10-28 - Runs a ratatui app as an agent session and gives a human a live cell-grid view of it.
* [iris](https://github.com/itzenata/iris-tui) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-07-08 - Live supervisor for every active Claude Code session - status, tokens, estimated cost, and one-pane approval of tool calls.
* [Borg](https://github.com/adelphidata/borg) ⭐ 5 | 🐛 2 | 🌐 Rust | 📅 2026-10-28 - A security-first personal AI assistant with a Ratatui chat TUI, long-term memory, scheduled tasks, and a self-healing daemon.
* [tapin](https://github.com/Thevi99/tapin) ⭐ 5 | 🐛 1 | 🌐 Rust | 📅 2026-10-15 - An inbox for your AI coding agents (Claude Code, Codex): approve requests, answer questions, and jump to the agent's pane.
* [savras](https://github.com/Marijusaj/savras) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - A side panel that sees every Claude Code session you have running: which are waiting on you, working, or done, with their PRs and context used.
* [claudash](https://github.com/jguajardo/claudash) ⭐ 3 | 🐛 4 | 🌐 Rust | 📅 2026-10-17 - The control room for Claude Code.
* [mindfork](https://github.com/vshylov/mindfork-rs) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-10-29 - A terminal AI chat with a memory and a self-model, on local models through llama.cpp or Ollama, or in the cloud.
* [wryme](https://github.com/adiled/wryme) ⭐ 2 | 🐛 6 | 🌐 Rust | 📅 2026-10-28 - That calm window where agents come to meet you, as a TUI and desktop app.
* [orbit-cli](https://github.com/dwaddle/orbit-cli) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-10-21 - An autonomous AI coding agent and Model Context Protocol (MCP) client powered by OpenRouter, featuring a split-pane TUI, Vim modal editing, AST compile guards, and multi-agent DAG workflows.
* [token-monitor](https://github.com/xzy9565/token-monitor) ⭐ 0 | 🐛 2 | 🌐 Rust | 📅 2026-10-29 - Terminal dashboard and rate-limit scheduler for AI coding subscriptions and token ledgers.

### 📁 Files, Data, and Documents

* [Yazi](https://github.com/sxyazi/yazi) ⭐ 43,098 | 🐛 66 | 🌐 Rust | 📅 2026-10-28 - Blazing fast terminal file manager written in Rust, based on async I/O.
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,847 | 🐛 7 | 🌐 Rust | 📅 2026-10-26 - Hackable, minimal, and fast TUI file explorer.
* [xan](https://github.com/medialab/xan) ⭐ 4,543 | 🐛 133 | 🌐 Rust | 📅 2026-10-23 - A terminal tool for processing CSV files.
* [binsider](https://github.com/orhun/binsider) ⭐ 4,501 | 🐛 37 | 🌐 Rust | 📅 2026-10-25 - A TUI for analyzing binary files.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 4,025 | 🐛 60 | 🌐 Rust | 📅 2026-07-04 - Command line csv viewer.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,781 | 🐛 14 | 🌐 Rust | 📅 2026-08-10 - Document viewer for Microsoft Word files.
* [joshuto](https://github.com/kamiyaa/joshuto) ⭐ 3,740 | 🐛 101 | 🌐 Rust | 📅 2026-10-26 - Ranger-like terminal file manager written in Rust.
* [tabiew](https://github.com/shshemi/tabiew) ⭐ 3,178 | 🐛 22 | 🌐 Rust | 📅 2026-10-29 - A lightweight TUI app to view and query CSV files.
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,147 | 🐛 47 | 🌐 Rust | 📅 2024-03-07 - Terminal-based disk space navigator.
* [stu](https://github.com/lusingander/stu) ⭐ 922 | 🐛 15 | 🌐 Rust | 📅 2026-04-30 - A TUI for AWS S3.
* [md-tui](https://github.com/henriklovhaug/md-tui) ⭐ 555 | 🐛 16 | 🌐 Rust | 📅 2026-10-25 - Markdown renderer in the terminal.
* [otree](https://github.com/fioncat/otree) ⭐ 524 | 🐛 3 | 🌐 Rust | 📅 2026-10-19 - A command line tool to view objects (JSON/YAML/TOML) in TUI tree widget.
* [hexhog](https://github.com/DVDTSB/hexhog) ⭐ 281 | 🐛 8 | 🌐 Rust | 📅 2026-02-16 - TUI Hex Editor/Viewer.
* [wiper](https://github.com/ikebastuz/wiper) ⭐ 250 | 🐛 11 | 🌐 Rust | 📅 2026-09-30 - Disk space analyzer and cleanup tool.
* [sheetsui](https://github.com/zaphar/sheetsui) ⭐ 246 | 🐛 4 | 🌐 Rust | 📅 2026-10-28 - A terminal based spreadsheet application.
* [FileSSH](https://github.com/JayanAXHF/filessh) ⭐ 234 | 🐛 3 | 🌐 Rust | 📅 2026-07-25 - A TUI-based file explorer for remote servers.
* [rat-commander](https://github.com/dividebysandwich/rat-commander) ⭐ 115 | 🐛 3 | 🌐 Rust | 📅 2026-10-12 - A fully-featured modern spiritual successor to Midnight-Commander with truecolor support and built-in process- and disk-explorer.
* [edamame](https://github.com/mijowi/edamame) ⭐ 111 | 🐛 15 | 🌐 Rust | 📅 2026-10-29 - A Terminal Markdown editor that stays rendered while you edit.
* [ddv](https://github.com/lusingander/ddv) ⭐ 103 | 🐛 3 | 🌐 Rust | 📅 2026-04-29 - Terminal DynamoDB viewer.
* [rdn](https://github.com/apatrushev/rdn) ⭐ 83 | 🐛 0 | 🌐 Rust | 📅 2026-03-17 - Rust port of well known old Dos Navigator.
* [TSHTS](https://github.com/SamuelSchlesinger/tshts) ⭐ 57 | 🐛 0 | 🌐 Rust | 📅 2026-05-28 - A terminal based spreadsheet application.
* [comhad](https://github.com/Eoin-McMahon/Comhad) ⭐ 51 | 🐛 5 | 🌐 Rust | 📅 2026-10-21 - A ranger-style terminal browser for S3, with previews, background transfers, and non-destructive sync.
* [dead-ringer](https://github.com/ztroop/dead-ringer) ⭐ 47 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - A binary diff tool for comparing files in hexadecimal and ASCII.
* [vib](https://github.com/ayanchavand/vib) ⭐ 35 | 🐛 1 | 🌐 Rust | 📅 2026-07-25 - A terminal file browser with LocalSend built in, for managing, organizing and transferring files across devices.
* [flerp](https://github.com/Huseynteymurzade28/flerp) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2026-10-16 - A TUI for exploring and analyzing text files, PDFs and images.
* [columbus](https://github.com/sivaprakashkrp/columbus) ⭐ 24 | 🐛 1 | 🌐 Rust | 📅 2026-06-15 - A GUI-like TUI file explorer.
* [FileView](https://github.com/Hiro-Chiba/fileview) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A terminal file browser with image previews, Git status, search, and an MCP server.
* [rada](https://github.com/FormikaDesk/rada-fm) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A terminal file manager that shows a plan before every operation, with a journal, undo and crash recovery.
* [traceview](https://github.com/javaLux/traceview) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-26 - Tracing and viewing your files and resource landscape.
* [norte](https://github.com/compilando/norte) ⭐ 4 | 🐛 10 | 🌐 Rust | 📅 2026-10-18 - Two-pane file manager on one Rust core: terminal, native window, CLI and MCP server for AI agents with scoped permissions.
* [rustfm](https://github.com/CanReader/rustfm) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-10-10 - Terminal file manager with a sidebar, multiple panels, live preview, and a task queue for file operations.
* [Xylem](https://github.com/andrelnfernandes/xylem) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2026-10-29 - An XTree/ZTreeWin-style file manager with a directory tree, tagging, batch operations, a built-in terminal and Git.

### 🧰 Terminal Workflow

* [atuin](https://github.com/atuinsh/atuin) ⭐ 32,121 | 🐛 430 | 🌐 Rust | 📅 2026-10-29 - A shell history manager with fast search and optional sync.
* [television](https://github.com/alexpasmantier/television) ⭐ 6,392 | 🐛 85 | 🌐 Rust | 📅 2026-10-18 - A blazingly fast general purpose fuzzy finder for your terminal.
* [dekit](https://github.com/pvolok/dekit) ⭐ 2,782 | 🐛 48 | 🌐 Rust | 📅 2026-10-25 - Run multiple commands in parallel and shows output of each command separately.
* [flyline](https://github.com/HalFrgrd/flyline) ⭐ 1,366 | 🐛 47 | 🌐 Rust | 📅 2026-10-26 - A Bash plugin TUI for an enhanced command line writing experience.
* [hwatch](https://github.com/blacknon/hwatch) ⭐ 1,092 | 🐛 10 | 🌐 Rust | 📅 2026-08-30 - Alternative watch command with command history and diffs.
* [fsel](https://github.com/Mjoyufull/fsel) ⭐ 481 | 🐛 2 | 🌐 Rust | 📅 2026-10-26 - A TUI app launcher and fuzzy finder for GNU/Linux and BSD.
* [kbt](https://github.com/bloznelis/kbt) ⭐ 391 | 🐛 5 | 🌐 Rust | 📅 2025-11-26 - Keyboard tester in terminal.
* [fzf-make](https://github.com/kyu08/fzf-make) ⭐ 309 | 🐛 49 | 🌐 Rust | 📅 2026-10-23 - A command line tool that executes make target using fuzzy finder with preview window.
* [exabind](https://github.com/junkdog/exabind) ⭐ 293 | 🐛 0 | 🌐 Rust | 📅 2026-03-29 - An animated TUI for viewing KDE shortcuts.
* [matchmaker](https://github.com/Squirreljetpack/matchmaker) ⭐ 239 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A fast, configurable fuzzy searcher for terminal data.
* [splashboard](https://github.com/unhappychoice/splashboard) ⭐ 228 | 🐛 13 | 🌐 Rust | 📅 2026-10-29 - A customizable terminal splash rendered on shell startup or directory updates.
* [snipt](https://github.com/snipt/snipt) ⭐ 150 | 🐛 5 | 🌐 Rust | 📅 2026-04-02 - A text snippet expansion tool with a TUI for managing snippets.
* [sigye](https://github.com/am2rican5/sigye) ⭐ 137 | 🐛 5 | 🌐 Rust | 📅 2026-10-22 - A terminal clock with FIGlet fonts, customizable themes, and animated backgrounds.
* [suvadu](https://github.com/AppachiTech/suvadu) ⭐ 124 | 🐛 2 | 🌐 Rust | 📅 2026-10-20 - Shell history for Zsh and Bash with a searchable TUI, AI coding agent sessions and an MCP server.
* [p2pmux](https://github.com/pelazas/p2pmux) ⭐ 74 | 🐛 47 | 🌐 Rust | 📅 2026-10-28 - A peer-to-peer terminal multiplexer for sharing sessions across machines.
* [material](https://github.com/azorng/material) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2026-08-14 - A material design color palette for the terminal.
* [absorb](https://github.com/kloki/absorb) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-04-11 - Quickly read a file without moving your eyes.
* [trex](https://github.com/blackopsrepl/trex) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-09-28 - A fast tmux session manager with fuzzy finding, per session stats and AI Agent tracking.
* [noble](https://github.com/MertSoylu/noble) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A HUD terminal workspace with tabs and splits, git projects, system sensors and AI coding quota in one screen.

### 🌐 Networking and Internet

#### Network Operations and Infrastructure

* [gping](https://github.com/orf/gping/) ⭐ 12,726 | 🐛 43 | 🌐 Rust | 📅 2026-10-06 - Ping tool with a graph.
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 12,035 | 🐛 57 | 🌐 Rust | 📅 2026-08-01 - Displays network utilization by process.
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 8,117 | 🐛 77 | 🌐 Rust | 📅 2026-10-26 - Network diagnostic tool.
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 5,189 | 🐛 29 | 🌐 Rust | 📅 2026-10-28 - A cross-platform network monitoring tool with deep packet inspection.
* [impala](https://github.com/pythops/impala) ⭐ 2,887 | 🐛 1 | 🌐 Rust | 📅 2026-10-07 - TUI for managing wifi on Linux.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,602 | 🐛 5 | 🌐 Rust | 📅 2026-10-18 - A TUI for sniffing network traffic using eBPF.
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,891 | 🐛 6 | 🌐 Rust | 📅 2026-07-06 - Network scanning tool.
* [AdGuardian-Term](https://github.com/Lissy93/AdGuardian-Term) ⭐ 1,679 | 🐛 0 | 🌐 Rust | 📅 2026-10-21 - Real-time traffic monitoring and statistics for AdGuard Home.
* [dnsglobe](https://github.com/514-labs/dnsglobe) ⭐ 1,348 | 🐛 2 | 🌐 Rust | 📅 2026-09-10 - Global DNS propagation checker querying 34 resolvers worldwide, with a world map.
* [mqttui](https://github.com/EdJoPaTo/mqttui) ⭐ 741 | 🐛 13 | 🌐 Rust | 📅 2026-10-28 - A terminal client for subscribing to and publishing messages over MQTT.
* [adsb\_deku/radar](https://github.com/wcampbell0x2a/adsb_deku#radar-tui) ⭐ 731 | 🐛 25 | 🌐 Rust | 📅 2026-01-04 - A terminal radar for displaying aircraft positions from Automatic Dependent Surveillance–Broadcast (ADS-B) data.
* [vortix](https://github.com/Harry-kp/vortix) ⭐ 725 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - Terminal UI for WireGuard and OpenVPN with real-time telemetry, leak detection, and kill switch.
* [unifly](https://github.com/hyperb1iss/unifly) ⭐ 272 | 🐛 2 | 🌐 Rust | 📅 2026-10-25 - CLI and TUI for Ubiquiti UniFi networks with live traffic charts, topology, firewall views, an offline demo fleet, and an agent skill.
* [streamtop](https://github.com/Jorji49/streamtop) ⭐ 122 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A terminal monitor for live video streams with real-time health checks and metrics.
* [wtfi2](https://github.com/kanywst/wtfi2) ⭐ 98 | 🐛 6 | 🌐 Rust | 📅 2026-10-28 - Live network-path diagnostic that pinpoints where your Wi-Fi connection breaks (link, gateway, DNS, WAN) and how to fix it.
* [mullvad-tui](https://github.com/d10n/mullvad-tui) ⭐ 79 | 🐛 0 | 🌐 Rust | 📅 2026-06-24 - A TUI for Mullvad VPN.
* [ytunnel](https://github.com/yetidevworks/ytunnel) ⭐ 59 | 🐛 1 | 🌐 Rust | 📅 2026-08-05 - A TUI-first CLI for managing Cloudflare Tunnels with custom domains.
* [discovery-rs](https://github.com/JustPretender/discovery-rs) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2025-08-21 - A TUI for discovering services on your local network.
* [nordvpn-tui](https://github.com/Degra02/nordvpn-tui) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2024-10-08 - A TUI for NordVPN.
* [wiretui](https://github.com/robin-thoene/wiretui) ⭐ 18 | 🐛 4 | 🌐 Rust | 📅 2026-10-11 - A minimal keyboard-driven TUI to manage WireGuard VPN connections.
* [prt](https://github.com/rekurt/prt) ⭐ 15 | 🐛 3 | 🌐 Rust | 📅 2026-10-24 - A TUI for monitoring network ports, inspecting owning processes, and managing SSH tunnels.
* [FlowLens](https://github.com/power4j/flowlens) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-10-16 - A cross-platform network traffic analyzer with process, IP, and outbound-domain attribution.
* [LazyMQTT](https://github.com/ScottFelder/lazymqtt) ⭐ 12 | 🐛 1 | 🌐 Rust | 📅 2026-10-22 - A keyboard-driven terminal client for browsing and publishing messages over the MQTT messaging protocol.
* [yscan](https://github.com/yetidevworks/yscan) ⭐ 11 | 🐛 4 | 🌐 Rust | 📅 2026-08-04 - A TUI-first network scanner with ARP, mDNS, and SSDP discovery.
* [dsnitch](https://github.com/infomaniac777/dsnitch) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-09-04 - Real-time network and DNS egress inspector TUI for Docker containers powered by eBPF.
* [sensor-vision](https://github.com/jcfromsiberia/sensor-vision) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2025-04-26 - TUI Client for TeamViewer IoT MQTT API for managing IoT Sensors and Metrics.

#### Remote Access, APIs, and File Transfer

* [JocalSend](https://git.kittencollective.com/nebkor/joecalsend) - Peer to peer local file and data transfer, compatible with [LocalSend](https://github.com/localsend/localsend) ⭐ 96,364 | 🐛 1,011 | 🌐 Dart | 📅 2026-10-29
* [termscp](https://github.com/veeso/termscp) ⭐ 3,141 | 🐛 9 | 🌐 Rust | 📅 2026-10-19 - A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB.
* [slumber](https://github.com/LucasPickering/slumber) ⭐ 1,231 | 🐛 9 | 🌐 Rust | 📅 2026-10-28 - Terminal-based HTTP/REST client.
* [purple](https://github.com/erickochen/purple) ⭐ 762 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - TUI SSH config manager & launcher with fuzzy search, tags, cloud provider sync, tunnels and command snippets for server management.
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 715 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 - A nyaa.si tui tool for browsing and downloading torrents.
* [TermiRs](https://github.com/caelansar/termirs) ⭐ 226 | 🐛 2 | 🌐 Rust | 📅 2026-06-08 - A modern, async SSH terminal client.
* [ssh-list](https://github.com/akinoiro/ssh-list) ⭐ 223 | 🐛 5 | 🌐 Rust | 📅 2025-10-27 - SSH connection manager.
* [vincenzo](https://github.com/gabrieldemian/vincenzo) ⭐ 159 | 🐛 4 | 🌐 Rust | 📅 2026-04-05 - A bittorrent client for the terminal with vim-like keybindings.
* [lazy-etherscan](https://github.com/woxjro/lazy-etherscan) ⭐ 151 | 🐛 1 | 🌐 Rust | 📅 2025-04-20 - A Simple Terminal UI for the Ethereum Blockchain Explorer.
* [rustmission](https://github.com/intuis/rustmission) ⭐ 66 | 🐛 21 | 🌐 Rust | 📅 2026-03-26 - TUI for the Transmission daemon.
* [bunflared](https://github.com/mirkobozzetto/bunflared) ⭐ 56 | 🐛 0 | 🌐 Rust | 📅 2026-10-18 - Share localhost on a temporary public HTTPS link through a Cloudflare quick tunnel, with a live traffic dashboard.
* [terminusdm](https://github.com/sumoduduk/terminusdm) ⭐ 51 | 🐛 0 | 🌐 Rust | 📅 2024-08-22 - Cross Platform Terminal Download Manager.
* [jdtui](https://github.com/rylos/jdtui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A TUI for JDownloader 2 over the My.JDownloader API: downloads, link grabber, accounts and settings, from anywhere.
* [traxor](https://github.com/kristoferssolo/traxor) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-05-14 - A TUI for managing Transmission torrents.

#### Communications and Social

* [concord](https://github.com/chojs23/concord) ⭐ 1,637 | 🐛 67 | 🌐 Rust | 📅 2026-10-23 - A TUI client for Discord.
* [iamb](https://github.com/ulyssa/iamb) ⭐ 1,315 | 🐛 116 | 🌐 Rust | 📅 2026-10-26 - A matrix chat client with vim keybindings.
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 1,030 | 🐛 15 | 🌐 Rust | 📅 2026-10-26 - A TUI for Telegram written in Rust.
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 633 | 🐛 8 | 🌐 Rust | 📅 2026-10-25 - Twitch chat in the terminal.
* [termchat](https://github.com/lemunozm/termchat) ⭐ 591 | 🐛 7 | 🌐 Rust | 📅 2023-11-27 - Terminal chat over a local network with video streaming and file transfer.
* [tincan](https://github.com/bilalyazicioglu/tincan-cli) ⭐ 223 | 🐛 42 | 🌐 Rust | 📅 2026-10-28 - Peer-to-peer voice and text chat with no server.
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 164 | 🐛 11 | 🌐 Rust | 📅 2025-12-28 - TUI client for Bluesky.
* [lobtui](https://github.com/pythops/lobtui) ⭐ 121 | 🐛 3 | 🌐 Rust | 📅 2025-05-16 - TUI for lobste.rs website.
* [mxr](https://github.com/planetaryescape/mxr) ⭐ 72 | 🐛 9 | 🌐 Rust | 📅 2026-10-29 - Local-first email client with Vim-style navigation, multi-account sync, and full-text search.
* [nostui](https://github.com/akiomik/nostui) ⭐ 72 | 🐛 31 | 🌐 Rust | 📅 2026-10-26 - A TUI client for Nostr.
* [faro](https://github.com/harababurel/faro) ⭐ 49 | 🐛 0 | 🌐 Rust | 📅 2026-10-26 - An unofficial Signal client for the terminal, built for tmux and SSH.
* [youtube-chat-rs](https://github.com/efekrskl/youtube-chat-rs) ⭐ 31 | 🐛 7 | 🌐 Rust | 📅 2026-06-04 - A terminal UI for viewing YouTube live chat.
* [rvIRC](https://github.com/KaraZajac/rvIRC) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2026-05-17 - A TUI client for IRC.
* [omaro](https://github.com/Rolv-Apneseth/omaro) ⭐ 22 | 🐛 6 | 🌐 Rust | 📅 2026-10-24 - TUI for the lobste.rs website.
* [Chat-gRPC](https://github.com/Atheer2104/chat-grpc) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2024-08-13 - A Real-time Chat Microservice built in Rust using gRPC, including a TUI client.
* [hopchat](https://github.com/bahdotsh/hopchat) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-10-23 - Offline, end-to-end encrypted chat for your local network, with no server, internet or accounts.
* [tsuchita](https://github.com/kamiyaa/tsuchita) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - A client-server notification center for desktop notifications on Linux.
* [hnr](https://github.com/prasanthj/hnr) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A terminal UI for Hacker News — browse feeds, read threaded comments, vote, reply, search, and bookmark.
* [Franking](https://github.com/blackopsrepl/Franking) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A TUI email client with an app-owned IMAP/SMTP engine, PGP and S/MIME, and a local maildir backend.
* [rail](https://github.com/vitosans/rail) ⭐ 2 | 🐛 2 | 🌐 Rust | 📅 2026-10-27 - A local-first terminal mail client for Gmail and Microsoft 365.

### 👨‍💻 System Administration

#### Monitoring, Diagnostics, and Logs

* [vector](https://github.com/vectordotdev/vector) ⭐ 22,776 | 🐛 2,557 | 🌐 Rust | 📅 2026-10-28 - A high-performance observability data pipeline.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,137 | 🐛 109 | 🌐 Rust | 📅 2026-10-28 - Cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,065 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - Cross-platform monitoring tool for system stats.
* [kmon](https://github.com/orhun/kmon) ⭐ 2,964 | 🐛 23 | 🌐 Rust | 📅 2026-09-21 - Linux Kernel Manager and Activity Monitor.
* [bpftop](https://github.com/jfernandez/bpftop) ⭐ 2,710 | 🐛 5 | 🌐 C | 📅 2026-09-01 - A real-time monitor for Linux eBPF programs, showing runtime, event rate, and CPU usage.
* [diskwatch](https://github.com/matthart1983/diskwatch) ⭐ 542 | 🐛 1 | 🌐 Rust | 📅 2026-10-27 - Single-host, read-only disk diagnostics TUI.
* [logss](https://github.com/todoesverso/logss) ⭐ 296 | 🐛 3 | 🌐 Rust | 📅 2026-06-08 - A simple cli for logs splitting.
* [erldash](https://github.com/sile/erldash) ⭐ 177 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - A simple, terminal-based Erlang dashboard.
* [winproc-tui](https://github.com/TX230/winproc-tui) ⭐ 122 | 🐛 0 | 🌐 Rust | 📅 2026-10-27 - Process monitoring tool with live metrics, time-series graphs, A/B comparison.
* [tuistash](https://github.com/edmocosta/tuistash) ⭐ 109 | 🐛 2 | 🌐 Rust | 📅 2026-04-10 - A TUI for monitoring Logstash.
* [journalview](https://github.com/codervijo/journalview) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-05-20 - A TUI for browsing and filtering systemd journal logs.
* [orbit-tui](https://github.com/ziuus/orbit-tui) ⭐ 59 | 🐛 8 | 🌐 Rust | 📅 2026-10-22 - Keyboard-driven terminal system dashboard (\~3MB, 0.5% CPU) with CPU, memory, disk, network, GPU, processes, and audio visualizer.
* [rrtop](https://github.com/wojciech-zurek/rrtop) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2021-08-05 - Redis monitoring (top like) app. rrtop -> \[r]ust \[r]edis \[top].
* [toptop](https://github.com/ur-grue/toptop) ⭐ 19 | 🐛 4 | 🌐 Rust | 📅 2026-09-21 - System monitor with a local-inference view: live tokens/sec, GPU compute-vs-bandwidth, VRAM-spill verdicts.
* [cpustate-tui](https://github.com/mkulke/cpustate-tui) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-02-19 - A bootable TUI for inspecting x86\_64 CPU state.
* [Aperture](https://github.com/stylebending/Aperture) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - Diagnostic TUI for Windows power users.
* [vTUI](https://github.com/noclue/vtui) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-10-17 - Explore vSphere in style, with vCenter and ESXi both included.
* [gentooplz](https://github.com/JustRoccat/gentooplz) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - A live terminal dashboard for Gentoo package builds.

#### Containers and Orchestration

* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,559 | 🐛 5 | 🌐 Rust | 📅 2026-10-14 - A simple and fast dashboard for Kubernetes.
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 2,041 | 🐛 29 | 🌐 Rust | 📅 2026-08-22 - Simple TUI to view & control Docker containers.
* [kftui](https://github.com/hcavarsan/kftray/blob/main/README.md#kftui) ⭐ 1,575 | 🐛 13 | 🌐 Rust | 📅 2026-10-29 - A TUI to manage multiple kubectl port-forward commands, with support for UDP and Kubernetes proxy.
* [ducker](https://github.com/robertpsoane/ducker) ⭐ 926 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 - A terminal app for managing Docker containers, inspired by K9s.
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 401 | 🐛 12 | 🌐 Rust | 📅 2026-10-29 - TUI for real-time monitoring of Kubernetes resources.
* [b4n](https://github.com/fioletoven/b4n) ⭐ 109 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A terminal-based tool for browsing Kubernetes resources.
* [reeve](https://github.com/yetidevworks/reeve) ⭐ 95 | 🐛 0 | 🌐 Rust | 📅 2026-10-11 - Manages a local web stack as per-user services: Caddy, Apache or nginx, per-vhost PHP-FPM versions, databases, local SSL, and wildcard DNS.
* [kubectl-watch](https://github.com/imuxin/kubectl-watch) ⭐ 64 | 🐛 4 | 🌐 Rust | 📅 2023-10-25 - A kubectl plugin to provide a pretty delta change view of being watched Kubernetes resources.
* [stevedore](https://github.com/takumiymd/stevedore) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-09-02 - A fast, keyboard-driven terminal UI for managing Docker containers and Compose stacks.

#### OS, Storage, and Package Management

* [dua-cli](https://github.com/Byron/dua-cli) ⭐ 6,397 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - View disk space usage and delete unwanted data, fast.
* [linutil](https://github.com/ChrisTitusTech/linutil) ⭐ 5,338 | 🐛 27 | 🌐 Shell | 📅 2026-10-14 - A distro-agnostic toolbox designed to simplify everyday Linux tasks.
* [caligula](https://github.com/ifd3f/caligula) ⭐ 2,421 | 🐛 55 | 🌐 Rust | 📅 2026-10-28 - A user-friendly, lightweight TUI for disk imaging.
* [systemctl-tui](https://github.com/rgwood/systemctl-tui) ⭐ 2,090 | 🐛 6 | 🌐 Rust | 📅 2026-10-03 - A fast, simple TUI for interacting with systemd services and their logs.
* [systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) ⭐ 1,596 | 🐛 1 | 🌐 Rust | 📅 2026-10-18 - A program for managing systemd services through a TUI.
* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,473 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A terminal UI for reading and changing Linux kernel parameters.
* [lemurs](https://github.com/coastalwhite/lemurs) ⭐ 1,360 | 🐛 80 | 🌐 Rust | 📅 2026-10-16 - A customizable TUI login manager for Linux and BSD.
* [lazyrsync](https://github.com/westpoint-io/lazyrsync) ⭐ 972 | 🐛 0 | 🌐 Rust | 📅 2026-10-22 - A TUI for rsync: reusable profiles, a dry-run diff preview, and live run progress.
* [parui](https://github.com/Vonr/parui) ⭐ 217 | 🐛 1 | 🌐 Rust | 📅 2026-10-21 - A TUI frontend for Arch User Repository helpers such as paru and yay.
* [brew-explorer](https://github.com/cosmincatalin/brew-explorer) ⭐ 136 | 🐛 0 | 🌐 Rust | 📅 2026-05-27 - A TUI for exploring and managing your Homebrew packages with ease.
* [mirro-rs](https://github.com/rtkay123/mirro-rs) ⭐ 117 | 🐛 12 | 🌐 Rust | 📅 2026-10-25 - An Arch Linux mirrorlist manager with a TUI.
* [pacman-utils](https://github.com/ankur3-101106/pacman-utils) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-10-15 - A keyboard-driven Arch Linux system manager with pacman, AUR, and reflector tools.
* [settings-tui](https://github.com/ziuus/settings-tui) ⭐ 8 | 🐛 4 | 🌐 Rust | 📅 2026-10-26 - Universal Linux Settings Center for your terminal (D-Bus, PipeWire, BlueZ, Hyprland, systemd).
* [dfdisk](https://github.com/tylerstyle/dfdisk) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-10-17 - Modern forensic disk imaging, damaged media rescue and evidence management.

#### Batch, Database, and Cluster Operations

* [Yozefu](https://github.com/MAIF/yozefu/) ⭐ 353 | 🐛 5 | 🌐 Rust | 📅 2026-08-27 - A TUI for exploring data of a Kafka cluster.
* [slurmer](https://github.com/wjwei-handsome/Slurmer) ⭐ 109 | 🐛 13 | 🌐 Rust | 📅 2025-11-24 - A TUI for monitoring and managing SLURM jobs.
* [lazyslurm](https://github.com/hill/lazyslurm) ⭐ 87 | 🐛 2 | 🌐 Rust | 📅 2026-08-09 - A lazygit-style terminal UI for Slurm. Monitor jobs, tail logs, and inspect nodes and partitions.
* [sqwatch](https://github.com/fedonman/sqwatch) ⭐ 17 | 🐛 18 | 🌐 Rust | 📅 2026-10-01 - A live SLURM queue dashboard.
* [pgmon](https://github.com/nbari/pgmon) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A TUI for monitoring PostgreSQL databases.
* [pgtui](https://codeberg.org/kdwarn/pgtui) - A PostgreSQL TUI client that uses your terminal editor for inserts and updates.

### 🔌 Hardware and Embedded

* [bluetui](https://github.com/pythops/bluetui) ⭐ 3,066 | 🐛 10 | 🌐 Rust | 📅 2026-10-24 - A TUI for managing Bluetooth devices.
* [macmon](https://github.com/vladkens/macmon) ⭐ 2,063 | 🐛 12 | 🌐 Rust | 📅 2026-10-23 - Sudoless performance monitoring for Apple Silicon processors.
* [blendr](https://github.com/dmtrKovalenko/blendr) ⭐ 497 | 🐛 5 | 🌐 Rust | 📅 2026-10-26 - A terminal UI for browsing, connecting to, and inspecting Bluetooth Low Energy devices.
* [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) ⭐ 360 | 🐛 11 | 🌐 Rust | 📅 2026-10-18 - A TUI for controlling and monitoring Framework Computers hardware.
* [nviwatch](https://github.com/msminhas93/nviwatch) ⭐ 241 | 🐛 7 | 🌐 Rust | 📅 2026-08-06 - Interactive TUI for monitoring NVIDIA GPU metrics, processes, and power, with bar and tabbed graph views.
* [pumas](https://github.com/graelo/pumas) ⭐ 221 | 🐛 2 | 🌐 Rust | 📅 2026-10-15 - Power Usage Monitor for Apple Silicon.
* [maccel](https://github.com/Gnarus-G/maccel) ⭐ 210 | 🐛 14 | 🌐 Rust | 📅 2026-08-02 - A mouse acceleration driver for Linux, and a TUI to control some parameters.
* [ComChan](https://github.com/Vaishnav-Sabari-Girish/ComChan) ⭐ 177 | 🐛 5 | 🌐 Rust | 📅 2026-10-29 - A minimal serial monitor with plotter TUI.
* [qmassa!](https://github.com/ulissesf/qmassa) ⭐ 111 | 🐛 0 | 🌐 Rust | 📅 2026-10-13 - Displays GPU devices usage stats on Linux.
* [quokka](https://github.com/dutradotdev/quokka) ⭐ 110 | 🐛 2 | 🌐 Rust | 📅 2026-07-27 - A TUI to inspect and tidy a USB-connected iPhone from macOS: storage, apps, media, syslog viewer.
* [suzui-rs](https://github.com/thatdevsherry/suzui-rs) ⭐ 107 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - A terminal viewer for Suzuki engine data over the Suzuki Serial Data Line.
* [tegratop](https://github.com/pythops/tegratop) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 - TUI monitoring tool (top like) for Nvidia jetson boards.
* [thinkfan-tui](https://github.com/karjonas/thinkfan-tui) ⭐ 80 | 🐛 1 | 🌐 Rust | 📅 2026-07-29 - A terminal-based Linux application for fan control and temperature monitoring on ThinkPad laptops.
* [napwatch](https://github.com/Tuguberk/napwatch) ⭐ 75 | 🐛 0 | 🌐 Rust | 📅 2026-07-19 - Diagnoses and controls macOS power/battery behavior: dark wakes, Power Nap, live drain rate, and per-process power draw.
* [btlescan](https://github.com/ztroop/btlescan) ⭐ 58 | 🐛 0 | 🌐 Rust | 📅 2026-03-01 - A terminal UI for scanning Bluetooth Low Energy devices and inspecting their services and characteristics.
* [Phone-OS](https://github.com/Julien-cpsn/Phone-OS) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A modern Phone OS for ESP32 CYD (Cheap Yellow Display).
* [MTUI](https://github.com/inowattio/mtui) ⭐ 41 | 🐛 3 | 🌐 Rust | 📅 2026-10-27 - A terminal client for Modbus industrial devices.
* [Mnyaoo32](https://github.com/intuis/mnyaoo32) ⭐ 35 | 🐛 1 | 🌐 Rust | 📅 2025-05-10 - An IRC client for ESP32 devices with a Ratatui-based interface.
* [v4l-tui](https://github.com/sermuns/v4l-tui) ⭐ 31 | 🐛 5 | 🌐 Rust | 📅 2026-09-19 - Configure webcams on Linux via Video4Linux. TUI alternative to `v4l2-ctl`.
* [nightlight-tui](https://github.com/umutdinceryananer/nightlightd) ⭐ 20 | 🐛 1 | 🌐 Rust | 📅 2026-10-08 - Dashboard for the nightlightd screen colour temperature daemon.
* [mxmon](https://github.com/yusufmo1/mxmon) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-07-25 - Sudoless Apple Silicon monitor with per-process watts, a live chassis heat map, and a JSON contract for scripts and agents.

### 🔐 Security and Identity

* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,777 | 🐛 14 | 🌐 Rust | 📅 2026-10-26 - A TUI for managing GnuPG encryption keys.
* [flawz](https://github.com/orhun/flawz) ⭐ 618 | 🐛 15 | 🌐 Rust | 📅 2026-10-23 - A TUI for browsing software vulnerabilities from the Common Vulnerabilities and Exposures (CVE) database.
* [cotp](https://github.com/replydev/cotp) ⭐ 393 | 🐛 2 | 🌐 Rust | 📅 2026-10-26 - An encrypted command-line authenticator for time- and counter-based one-time passwords.
* [jwt-ui](https://github.com/jwt-rs/jwt-ui) ⭐ 353 | 🐛 11 | 🌐 Rust | 📅 2026-05-31 - A command line UI for decoding/encoding JSON Web Tokens.
* [oak-keyring](https://github.com/OpenKeyring/oak-keyring) ⭐ 236 | 🐛 0 | 🌐 Rust | 📅 2026-08-07 - A local-first password manager that keeps vault management interactive, keyboard-driven, and in the terminal.
* [passepartui](https://github.com/kardwen/passepartui) ⭐ 129 | 🐛 3 | 🌐 Rust | 📅 2025-05-07 - A TUI for managing the pass password store.
* [chamber](https://github.com/mikeleppane/chamber) ⭐ 105 | 🐛 1 | 🌐 Rust | 📅 2025-09-06 - A TUI for managing secrets.
* [YADB](https://github.com/izya4ka/yadb) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2026-02-24 - A TUI for discovering hidden directories and files on web servers.

### 📝 Productivity and Planning

#### Tasks, Projects, and Calendars

* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,153 | 🐛 128 | 🌐 Rust | 📅 2026-10-25 - TUI for the Taskwarrior command-line task manager.
* [tuxedo](https://github.com/webstonehq/tuxedo) ⭐ 1,890 | 🐛 85 | 🌐 Rust | 📅 2026-10-26 - A fast, keyboard-driven terminal UI for todo.txt.
* [mirador](https://github.com/jchultarsky/mirador) ⭐ 326 | 🐛 2 | 🌐 Rust | 📅 2026-10-24 - A personal dashboard with world clocks, calendar, weather, tasks, notes, a market watchlist and live CPU and network graphs.
* [Rust-Kanban](https://github.com/yashs662/rust_kanban) ⭐ 273 | 🐛 2 | 🌐 Rust | 📅 2025-02-13 - A kanban board for the terminal.
* [aven](https://github.com/raine/aven) ⭐ 217 | 🐛 7 | 🌐 Rust | 📅 2026-10-29 - A local-first task manager for power users and agents, with a keyboard-driven TUI and agent-first CLI.
* [basilk](https://github.com/GabAlpha/basilk) ⭐ 215 | 🐛 11 | 🌐 Rust | 📅 2025-05-24 - A TUI to manage your tasks with minimal kanban logic.
* [kanban](https://github.com/kanban-rs/kanban) ⭐ 188 | 🐛 9 | 🌐 Rust | 📅 2026-10-18 - TUI kanban board for projects management with sprint tracking and task prioritization.
* [Jirust](https://github.com/Code-Militia/jirust) ⭐ 160 | 🐛 6 | 🌐 Rust | 📅 2024-05-29 - A Jira TUI.
* [tatuin](https://github.com/panter-dsd/tatuin) ⭐ 145 | 🐛 18 | 🌐 Rust | 📅 2026-10-26 - A terminal task manager that aggregates tasks from multiple providers.
* [judo](https://github.com/giacomopiccinini/judo) ⭐ 125 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 - A multi-database TUI for ToDo lists.
* [vault-tasks](https://github.com/louis-thevenet/vault-tasks) ⭐ 89 | 🐛 11 | 🌐 Rust | 📅 2026-06-05 - TUI Markdown Task Manager.
* [lt](https://github.com/markmarkoh/lt) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2026-01-14 - An unofficial TUI client for Linear.app.
* [td](https://github.com/holly-hacker/td) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-05-19 - A graph-based TUI to-do app.
* [Planner123](https://github.com/blackopsrepl/Planner123) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-09-29 - A local-first TUI calendar with an AI planning inbox that schedules your to-dos into reviewable proposals, plus Google Calendar sync and .ics import.
* [RetireTui](https://github.com/kenianbei/retiretui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A local-first retirement planner for the terminal.
* [sc-cli](https://github.com/lnds/sc-cli) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 - A TUI for Shortcut (formerly know as Clubhouse) a project management tool for teams.
* [linear-tui](https://github.com/solcreek/linear-tui) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-10-27 - A Linear client that gets all its data from linearctl's JSON interface.
* [taskfinder](https://crates.io/crates/taskfinder) - Extract and display tasks from plain text files, hooking into your default terminal-based editor for editing.

#### Notes and Journaling

* [tui-journal](https://github.com/AmmarAbouZor/tui-journal) ⭐ 790 | 🐛 15 | 🌐 Rust | 📅 2026-10-25 - Journaling/Notes-taking terminal-based app.
* [rucola](https://github.com/Linus-Mussmaecher/rucola) ⭐ 548 | 🐛 2 | 🌐 Rust | 📅 2026-10-18 - Terminal-based markdown note manager.
* [tmmpr](https://github.com/tanciaku/tmmpr) ⭐ 352 | 🐛 3 | 🌐 Rust | 📅 2026-05-15 - Terminal mind mapper.
* [glues](https://github.com/gluesql/glues) ⭐ 284 | 🐛 16 | 🌐 Rust | 📅 2026-06-02 - A sync-enabled TUI note-taking app with Git, CSV, and JSON support.
* [kimün](https://github.com/nico2sh/kimun) ⭐ 64 | 🐛 1 | 🌐 Rust | 📅 2026-10-20 - A terminal-based Markdown note taking app that combines an interactive TUI with a scriptable CLI for automation.
* [revw](https://github.com/rlelf/revw) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-04 - A vim-like TUI for managing notes and resources.
* [quick-note](https://github.com/daniel-valencia-ts/quick-note) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-06-30 - A simple note-taking tool.
* [writui](https://github.com/aakashns/writui) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2026-10-19 - A Markdown writing app with an encrypted local vault, named versions, and mouse and keyboard controls.
* [MDDock](https://mddock.com) - Local-first Markdown notes app with a full ratatui TUI (live rendering, mermaid, grep) and an MCP server so AI agents read the same notes.

#### Finance and Markets

* [tickrs](https://github.com/tarkah/tickrs) ⭐ 1,710 | 🐛 33 | 🌐 Rust | 📅 2026-05-19 - Stock market ticker in the terminal.
* [budget-tracker-tui](https://github.com/Feromond/budget-tracker-tui) ⭐ 380 | 🐛 9 | 🌐 Rust | 📅 2026-10-05 - A fast, keyboard-driven TUI for tracking expenses, tracking investments, and analyzing your budget with ease.
* [fitui](https://github.com/ayanchavand/fitui) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-18 - A terminal-based personal finance tracker and budgeting with TUI.
* [alphai-tui](https://github.com/makeev/alphai-tui) ⭐ 88 | 🐛 1 | 🌐 Rust | 📅 2026-10-27 - A stock dashboard with quotes, candlestick charts, AI-scored news and SEC Form 4 insider activity.
* [Rex](https://github.com/TheRustyPickle/Rex) ⭐ 64 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A TUI for managing Incomes and Expenses.
* [invoicepilot](https://github.com/adolfousier/invoicepilot) ⭐ 44 | 🐛 0 | 🌐 Rust | 📅 2026-03-14 - A TUI for automating invoice and bank statement fetching from Gmail to Google Drive.

#### Focus, Habits, and Time

* [timr-tui](https://github.com/sectore/timr-tui) ⭐ 384 | 🐛 0 | 🌐 Rust | 📅 2026-10-22 - TUI to organize your time: Pomodoro, Countdown, Timer, Event.
* [rusty-krab-manager](https://github.com/aryakaul/rusty-krab-manager) ⭐ 327 | 🐛 12 | 🌐 Rust | 📅 2026-08-30 - A terminal time-management TUI inspired by the Pomodoro technique.
* [work-tuimer](https://github.com/Kamyil/work-tuimer) ⭐ 262 | 🐛 9 | 🌐 Rust | 📅 2026-05-18 - A TUI for easier time tracking each day, task-per-task with summaries.
* [hustle-tracker](https://github.com/adolfousier/hustle-tracker) ⭐ 237 | 🐛 0 | 🌐 Rust | 📅 2026-03-16 - A privacy-first TUI to track what apps you use and how long you spend on them.
* [sprout](https://github.com/kb019/sprout) ⭐ 62 | 🐛 0 | 🌐 Rust | 📅 2026-10-02 - A terminal habit tracker with GitHub-style activity heatmap, streak tracking and goal management.
* [focusd](https://github.com/bibekbhusal0/focusd) ⭐ 49 | 🐛 2 | 🌐 Rust | 📅 2026-10-11 - A terminal pomodoro timer with daemon, stats, history, streak, and nice interface.
* [Respire](https://github.com/ElevenJune/respire) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-06-22 - A breathing app to take a break directly from your terminal.
* [Tomatui](https://github.com/Hiro-Chiba/tomatui) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - A terminal Pomodoro timer with a one-line mode, a full-screen display, and local focus statistics.
* [void](https://github.com/p6laris/Void) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-09-29 - A focus app with built-in task management, streak tracking, and customizable break schedules.
* [isw](https://gitlab.com/thom-cameron/isw) - A simple terminal stopwatch application for pomodoro etc.

### 📚 Reading and Learning

* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,606 | 🐛 36 | 🌐 Rust | 📅 2026-10-13 - Terminal-based typing test.
* [eilmeldung](https://github.com/christo-auer/eilmeldung) ⭐ 1,041 | 🐛 6 | 🌐 Rust | 📅 2026-10-28 - A TUI RSS reader based on the news\_flash library inspired by Neovim and co.
* [feedr](https://github.com/bahdotsh/feedr) ⭐ 449 | 🐛 8 | 🌐 Rust | 📅 2026-06-11 - A terminal-based RSS/Atom feed reader with a TUI.
* [ostt](https://github.com/kristoferlund/ostt) ⭐ 306 | 🐛 3 | 🌐 Rust | 📅 2026-10-26 - Open Speech-to-Text recording tool with real-time volume metering and transcription.
* [synd](https://github.com/ymgyt/syndicationd) ⭐ 155 | 🐛 12 | 🌐 Rust | 📅 2026-10-26 - A TUI feed viewer.
* [bbcli](https://github.com/hako/bbcli) ⭐ 142 | 🐛 0 | 🌐 Rust | 📅 2026-07-02 - A terminal-based BBC News reader featuring a compact, numbered list interface with vim-like navigation.
* [hg-tui](https://github.com/kaixinbaba/hg-tui) ⭐ 97 | 🐛 3 | 🌐 Rust | 📅 2024-09-03 - A TUI for browsing and searching HelloGitHub's open-source project directory.
* [leetrs](https://github.com/shadowmkj/leetrs) ⭐ 92 | 🐛 15 | 🌐 Rust | 📅 2026-10-28 - A TUI for browsing, testing, and submitting LeetCode problems directly from your terminal.
* [ttypr](https://github.com/tanciaku/ttypr) ⭐ 76 | 🐛 0 | 🌐 Rust | 📅 2026-03-21 - Terminal typing practice.
* [scriptor](https://github.com/giacomopiccinini/scriptor) ⭐ 63 | 🐛 1 | 🌐 Rust | 📅 2026-05-14 - A (medieval) local speech-to-text TUI & CLI.
* [hncli](https://github.com/pierreyoda/hncli) ⭐ 51 | 🐛 2 | 🌐 Rust | 📅 2026-10-24 - Hacker News read-only TUI.
* [kanash](https://github.com/benoitlx/kanash) ⭐ 35 | 🐛 12 | 🌐 Rust | 📅 2026-08-03 - Learn Kana in your terminal.
* [cargo-thesaurust](https://github.com/quietpigeon/cargo-thesaurust) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2025-05-07 - A terminal-based dictionary app.
* [keybr-tui](https://github.com/y0sif/keybr-tui) ⭐ 16 | 🐛 2 | 🌐 Rust | 📅 2026-10-20 - Adaptive touch-typing practice that finds the keys slowing you down and drills them, a port of the keybr.com algorithm.
* [tts-tui](https://github.com/lesleyrs/tts-tui) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2024-01-26 - Text to speech app that reads from clipboard.
* [exhaust](https://github.com/heyrict/exhaust) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2020-04-18 - A terminal app for doing exams.
* [fastcards](https://github.com/indium114/fastcards) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-10-26 - A CLI spaced-repetition flashcard study tool.
* [rsstig](https://github.com/indium114/rsstig) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-21 - An unconventional terminal RSS/Atom reader.
* [herdfold](https://github.com/azihsoyn/herdfold) ⭐ 1 | 🐛 1 | 🌐 Rust | 📅 2026-10-23 - A book reader that lays long text out as facing pages, with notes, vertical Japanese, and an AI agent to ask.

### 🎵 Music and Media

#### Music and Audio

* [spotify-tui](https://github.com/Rigellute/spotify-tui) ⭐ 19,404 | 🐛 306 | 🌐 Rust | 📅 2024-04-04 - (Unmaintained) The original Spotify TUI; see spotatui (direct fork) or spotify-player (independent alternative).
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,287 | 🐛 171 | 🌐 Rust | 📅 2026-09-19 - An independently developed Spotify player with full feature parity.
* [spotatui](https://github.com/LargeModGames/spotatui) ⭐ 1,777 | 🐛 35 | 🌐 Rust | 📅 2026-10-28 - Spotify client with native streaming, synced lyrics, and audio visualization. A direct fork of spotify-tui with continued development and new features.
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 776 | 🐛 38 | 🌐 Rust | 📅 2025-03-03 - Listen to music from YouTube in the terminal.
* [scope-tui](https://github.com/alemidev/scope-tui) ⭐ 748 | 🐛 10 | 🌐 Rust | 📅 2026-10-21 - A terminal audio scope with waveform, vector, and frequency views.
* [Tuitar](https://github.com/orhun/tuitar) ⭐ 531 | 🐛 6 | 🌐 Rust | 📅 2025-12-23 - A portable guitar training tool.
* [NoctaVox](https://github.com/Jaxx497/noctavox) ⭐ 382 | 🐛 3 | 🌐 Rust | 📅 2026-10-12 - A lightweight, customizable TUI music player for local files.
* [asak](https://github.com/chaosprint/asak) ⭐ 371 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 - A cross-platform audio recording/playback CLI tool.
* [fum](https://github.com/qxb3/fum) ⭐ 283 | 🐛 6 | 🌐 Rust | 📅 2026-07-11 - A fully ricable tui-based music client.
* [myx](https://github.com/HaseebKhalid1507/Myx) ⭐ 261 | 🐛 24 | 🌐 Rust | 📅 2026-10-07 - Modern Spotify player for the terminal. With reactive themes.
* [glicol-cli](https://github.com/glicol/glicol-cli) ⭐ 194 | 🐛 15 | 🌐 Rust | 📅 2024-12-09 - Cross-platform music live coding in terminal.
* [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) ⭐ 96 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 - Sample-based, MIDI-controlled virtual pipe organ instrument.
* [chordflow](https://github.com/timvancann/chordflow) ⭐ 93 | 🐛 2 | 🌐 Rust | 📅 2026-08-27 - A tool for practicing improvisation and mastering the guitar neck.
* [rs-pug](https://github.com/JustRoccat/rs-pug) ⭐ 75 | 🐛 0 | 🌐 Rust | 📅 2026-10-26 - A Neovim-inspired asynchronous music player with a reactive audio visualizer.
* [roon-tui](https://github.com/TheAppgineer/roon-tui) ⭐ 63 | 🐛 5 | 🌐 Rust | 📅 2024-08-30 - Roon Remote for the terminal.
* [gtm](https://github.com/prjctimg/gtm) ⭐ 62 | 🐛 2 | 🌐 Rust | 📅 2026-10-28 - Feature rich audio player built for terminal enthusiasts.
* [O₂](https://github.com/coignard/o2) ⭐ 54 | 🐛 5 | 🌐 Rust | 📅 2026-10-20 - Rust port of the ORCΛ esoteric programming language and terminal livecoding environment.
* [sparkplayer](https://github.com/dividebysandwich/sparkplayer/tree/main) ⭐ 54 | 🐛 2 | 🌐 Rust | 📅 2026-09-19 - A fun terminal based media player with album art and video support.
* [deezer-tui](https://github.com/Tatayoyoh/deezer-tui) ⭐ 52 | 🐛 2 | 🌐 Rust | 📅 2026-10-22 - Deezer music TUI with included background player.
* [serenIT](https://github.com/ElevenJune/serenIT) ⭐ 48 | 🐛 2 | 🌐 Rust | 📅 2025-11-20 - An ambient sound player directly from your terminal.
* [lrxed](https://github.com/LunaPresent/lrxed) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2025-11-02 - A TUI application for synchronizing lyrics.
* [audium](https://github.com/takashialpha/audium) ⭐ 37 | 🐛 1 | 🌐 Rust | 📅 2026-10-24 - A keyboard-driven music app for people who live in the terminal.
* [trollstov](https://github.com/hikikones/troll) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-10-29 - A music player for the terminal where your files and their metadata are all you need.
* [bytebeat-rs](https://github.com/chaosprint/bytebeat-rs) ⭐ 30 | 🐛 1 | 🌐 Rust | 📅 2023-12-18 - A terminal tool for generating music from bytebeat expressions.
* [miditui](https://github.com/pinkpixel-dev/miditui) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2026-09-20 - A terminal MIDI player and multi-track piano roll visualizer with SoundFont synthesis.
* [oosc-rs](https://github.com/karasikq/oosc-rs) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-03-04 - A terminal synthesizer that builds sounds from layered waveforms.
* [classfi](https://github.com/carmiac/classfi) ⭐ 21 | 🐛 5 | 🌐 Rust | 📅 2026-07-23 - A focused streaming music player for classical music.
* [tusic](https://github.com/eminfedar/tusic) ⭐ 21 | 🐛 1 | 🌐 Rust | 📅 2026-07-15 - Lightweight TUI Music Player. Play from YouTube or \~/Music folder easily.
* [smyx](https://github.com/ayanchavand/Smyx) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - A sleek, beautiful music player for Navidrome / OpenSubsonic with dynamic themes.
* [Youta](https://github.com/vitaly-zdanevich/youta) ⭐ 13 | 🐛 6 | 🌐 Rust | 📅 2026-10-20 - An audio player for YouTube, Yandex Music, podcasts, audiobooks, radio, and local files.
* [ytmusic-tui](https://github.com/WakaTaira/ytmusic-tui) ⭐ 9 | 🐛 12 | 🌐 Rust | 📅 2026-06-19 - A TUI client for YouTube Music with Vim-style navigation and desktop media-control integration.
* [sgram-tui](https://github.com/arian-shamaei/sgram-tui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - A calibrated spectrogram analyzer for live mic or audio files, with labeled PNG figure export and a headless render mode.
* [Oscilla](https://github.com/Noven-Signal/Oscilla) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-10-07 - A lightweight TUI music player for local audio playback, featuring smooth 60 FPS visualizations.
* [angry-duiker](https://gitlab.com/fizzizist/angry-duiker-2) - A TUI for streaming music from network media servers using DLNA.

#### Books, Video, and Creative Media

* [MovieBox-TUI](https://github.com/mesamirh/MovieBox-Tui) ⭐ 2,669 | 🐛 13 | 🌐 Rust | 📅 2026-10-29 - Terminal client for discovering and downloading movies and series, with playback in mpv, VLC, or IINA.
* [bookokrat](https://github.com/bugzmanov/bookokrat) ⭐ 1,261 | 🐛 49 | 🌐 Rust | 📅 2026-10-21 - A full-featured EPUB / PDF e-book reader with Vim keybindings.
* [manga-tui](https://github.com/josueBarretogit/manga-tui) ⭐ 952 | 🐛 25 | 🌐 Rust | 📅 2026-10-28 - Terminal-based manga reader and downloader with image support.
* [managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 793 | 🐛 2 | 🌐 Rust | 📅 2026-10-14 - A TUI and CLI for managing Sonarr, Radarr, and other Servarr applications.
* [mal-cli](https://github.com/L4z3x/mal-cli) ⭐ 163 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 - A terminal client for MyAnimeList.
* [ytsub](https://github.com/sarowish/ytsub) ⭐ 96 | 🐛 3 | 🌐 Rust | 📅 2026-10-27 - A subscriptions only TUI YouTube client.
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 84 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 - Terminal presentation program with modern TUI.
* [TRNovel](https://github.com/yexiyue/TRNovel) ⭐ 78 | 🐛 5 | 🌐 Rust | 📅 2026-10-15 - A terminal novel reader for local and network novels, with AI-assisted book-source generation and TTS playback.
* [tubetui](https://github.com/polblancoo/tubetui) ⭐ 71 | 🐛 3 | 🌐 Rust | 📅 2026-10-25 - A YouTube client with tabs, subscriptions, and video embedded in kitty via mpv.
* [visualvault](https://github.com/mikeleppane/visualvault) ⭐ 67 | 🐛 3 | 🌐 Rust | 📅 2026-10-26 - A TUI for organizing media files.
* [Grimoire](https://github.com/kelsierbot/GrimoireTUI) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2026-09-28 - A cozy writing desk for novels.
* [Absotui](https://github.com/pdwaldrop/absotui) ⭐ 27 | 🐛 0 | 🌐 Rust | 📅 2026-10-24 - A fast, keyboard-driven TUI client for Audiobookshelf (self-hosted audiobook/podcast server).
* [red-table](https://github.com/volker-schukai/red-table) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-10-23 - A keyboard-driven terminal image browser for inspecting, comparing, and selecting photos.
* [readio](https://github.com/hrhrng/readio) ⭐ 13 | 🐛 2 | 🌐 Rust | 📅 2026-09-23 - A terminal ebook reader for EPUB, PDF, Markdown, and plain text with optional local text-to-speech.
* [ratslate](https://github.com/azihsoyn/ratslate) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-12 - An infinite-canvas whiteboard driven by the mouse.

### 🎮 Games and Entertainment

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 5,240 | 🐛 9 | 🌐 Rust | 📅 2026-10-29 - A TUI screensaver that visualizes Git commit history in your terminal.
* [GitType](https://github.com/unhappychoice/gittype) ⭐ 1,650 | 🐛 18 | 🌐 Rust | 📅 2026-10-28 - A CLI code-typing game that turns your source code into typing challenges.
* [Chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,213 | 🐛 35 | 🌐 Rust | 📅 2026-10-23 - Terminal-based Chess game.
* [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 754 | 🐛 6 | 🌐 Rust | 📅 2026-10-24 - P2P terminal game about spacepirates playing basketball across the galaxy.
* [plastic](https://github.com/Amjad50/plastic) ⭐ 586 | 🐛 20 | 🌐 Rust | 📅 2026-03-09 - NES emulator with extra ui implemented in ratatui.
* [ttysvr](https://github.com/cxreiff/ttysvr) ⭐ 488 | 🐛 4 | 🌐 Rust | 📅 2026-07-04 - Screen saver for your terminal.
* [Dealve](https://github.com/kurama/dealve-tui) ⭐ 249 | 🐛 5 | 🌐 Rust | 📅 2026-05-08 - Browse game deals across Steam, GOG, Humble Bundle, Epic Games, and more from your terminal.
* [poketex](https://github.com/ckaznable/poketex) ⭐ 220 | 🐛 0 | 🌐 Rust | 📅 2026-09-21 - Simple Pokedex based on TUI.
* [theattyr](https://github.com/orhun/theattyr) ⭐ 172 | 🐛 1 | 🌐 Rust | 📅 2024-10-26 - A terminal theater for playing VT100 text art and animations.
* [mlbt](https://github.com/mlb-rs/mlbt) ⭐ 169 | 🐛 0 | 🌐 Rust | 📅 2026-09-06 - A tui for the MLB Statcast API. Watch a live game using Gameday, or check scores, standings, and stats.
* [ssHattrick](https://github.com/ricott1/sshattrick) ⭐ 146 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 - A multiplayer terminal version of the Hattrick football-management game, playable over SSH.
* [pokeductor](https://github.com/Huseynteymurzade28/pokeductor) ⭐ 132 | 🐛 2 | 🌐 Rust | 📅 2026-10-27 - A terminal Pokédex and evolution analyzer with sprite cards.
* [Inertia](https://github.com/aclfe/inertia) ⭐ 120 | 🐛 1 | 🌐 Rust | 📅 2026-07-19 - A 3D physics simulator in your terminal.
* [private\_poker](https://github.com/theOGognf/private_poker) ⭐ 106 | 🐛 0 | 🌐 Rust | 📅 2026-07-13 - A poker library, server, client, and TUI.
* [Battleship.rs](https://github.com/deepu105/battleship-rs) ⭐ 97 | 🐛 4 | 🌐 Rust | 📅 2024-10-16 - Terminal-based Battleship game.
* [confetty\_rs](https://github.com/Handfish/confetty_rs) ⭐ 91 | 🐛 1 | 🌐 Rust | 📅 2024-02-08 - Particle system (fireworks, stars) rendered in the terminal.
* [astray](https://github.com/ekosachev/astray) ⭐ 87 | 🐛 9 | 🌐 Rust | 📅 2024-08-16 - TUI-based space strategy game.
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 82 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 - Beautiful visualizations of common maze building and graph searching algorithms.
* [sharad-ratatui](https://github.com/ProHaller/sharad_ratatui) ⭐ 67 | 🐛 2 | 🌐 Rust | 📅 2025-07-06 - A text-based Shadowrun role-playing game.
* [crosstui](https://github.com/matrixfrog/crossword) ⭐ 58 | 🐛 12 | 🌐 Rust | 📅 2025-07-31 - Terminal-based crossword puzzle player.
* [tage](https://github.com/jacopograndi/tage) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2024-08-13 - Turn based strategy game with multiplayer, empires and warfare.
* [Snake](https://github.com/kriskw1999/ratatui-snake) ⭐ 44 | 🐛 1 | 🌐 Rust | 📅 2025-03-16 - Simple terminal based snake game.
* [sxtetris](https://github.com/shixinhuang99/sxtetris) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2025-08-26 - A terminal Tetris game.
* [cube timer](https://github.com/paarthmadan/cube) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2021-09-12 - A tui for cube timing, written in Rust.
* [wordl](https://github.com/palerdot/wordl-rs) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2024-03-16 - Terminal-based Wordle game. Web like experience with keyboard hints and guess reveal animations.
* [rust-sadari-cli](https://github.com/24seconds/rust-sadari-cli) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2020-05-11 - Rust sadari game based on terminal! (Ghost leg or Amidakuji in another words).
* [terminal.pong](https://github.com/IshmamR/terminal.pong) ⭐ 35 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 - Terminal based ping pong game.
* [modder-rs](https://github.com/JayanAXHF/modder-rs) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2025-09-20 - A practical TUI to manage and install mods for Minecraft.
* [chessterm](https://github.com/ronaldsuwandi/chessterm) ⭐ 28 | 🐛 0 | 🌐 Rust | 📅 2025-02-05 - A Rust-powered chess engine in a terminal.
* [termfarm](https://github.com/indium114/termfarm) ⭐ 28 | 🐛 1 | 🌐 Rust | 📅 2026-10-28 - A simple idle farming game.
* [tuiba](https://github.com/Huseynteymurzade28/tuiba) ⭐ 26 | 🐛 4 | 🌐 Rust | 📅 2026-10-27 - Game Boy Advance emulator with Kitty/Sixel/iTerm2 graphics and a half-block fallback.
* [oxycards](https://github.com/BrookJeynes/oxycards) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2024-08-01 - Quiz card application built within the terminal.
* [fishtanks](https://github.com/daniel-retamal/fishtanks) ⭐ 20 | 🐛 1 | 🌐 Rust | 📅 2026-10-23 - An ASCII aquarium for the terminal. Go fishing, dungeon crawling, or gamble away.
* [tic-tac-toe](https://github.com/thomas-mauran/tic-tac-toe) ⭐ 18 | 🐛 2 | 🌐 Rust | 📅 2024-10-29 - Terminal-based tic tac toe game.
* [WOPR TUI 2026](https://github.com/ankurCES/WOPR_TUI_2026) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-07-07 - A WarGames-inspired Cold War simulation TUI with AI-powered scenarios, DEFCON escalation, and multi-language intelligence intercepts.
* [flip7](https://github.com/ilyichv/flip7) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-04-13 - Terminal-based Flip7 game.
* [cgol-tui](https://github.com/jarjk/cgol-tui-rs) ⭐ 13 | 🐛 3 | 🌐 Rust | 📅 2026-09-02 - Conway's Game of Life viewer with a TUI in Rust.
* [game-of-life-rs](https://github.com/kachark/game-of-life-rs) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2021-04-08 - Conway's Game of Life implemented in Rust and visualized with tui-rs.
* [a-puzzle-a-day](https://github.com/mrbjarksen/a-puzzle-a-day) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2024-03-15 - Generate and browse all solutions to A-Puzzle-A-Day.
* [sued-rs](https://github.com/Danilo-Guedes/sued-rs) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-13 - A horror-themed recreation of SueD, the 2000s Brazilian prank oracle.
* [tetris-tui](https://github.com/Axyl1410/tetris-tui) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - Terminal Tetris following the Tetris Guideline.
* [Blackjack](https://github.com/skharchikov/blackjack) ⭐ 7 | 🐛 13 | 🌐 Rust | 📅 2026-09-30 - Multiplayer Blackjack with a WebSocket server and a terminal client.
* [bigbrainwordle](https://github.com/kloki/bigbrainwordle) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2026-02-28 - A tool to help you cheat with the daily wordle.
* [DEADLINE](https://github.com/pinkpixel-dev/deadline) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-10-04 - A haunted late-90s BBS text adventure for your terminal.
* [Connect-four](https://github.com/jesper-olsen/connect-four) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-10-29 - Connect-four; interactive game + perfect solver.
* [enimtui](https://codeberg.org/tranzystorekk/enimtui) - Terminal-based minesweeper knockoff.
* [Thardians](https://gitlab.com/thustle/thardians-rs) - Space Invaders for the terminal.

### 🔬 Science, Math, and Exploration

* [tgv](https://github.com/zeqianli/tgv) ⭐ 487 | 🐛 9 | 🌐 Rust | 📅 2026-10-27 - A terminal genome browser with Vim-style navigation.
* [tracker](https://github.com/ShenMian/tracker) ⭐ 330 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A terminal-based real-time satellite tracking and orbit prediction application.
* [numr](https://github.com/nasedkinpv/numr) ⭐ 307 | 🐛 6 | 🌐 Rust | 📅 2026-10-27 - A natural language calculator with unit/currency conversions and vim-style keybindings.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 178 | 🐛 0 | 🌐 Rust | 📅 2026-10-04 - A free, simple weather TUI that pulls data without the need for an API key, account, or subscription.
* [tenki](https://github.com/ckaznable/tenki) ⭐ 169 | 🐛 0 | 🌐 Rust | 📅 2026-07-23 - A tty-clock with weather effect.
* [sauva](https://github.com/lusingander/sauva) ⭐ 105 | 🐛 0 | 🌐 Rust | 📅 2026-10-24 - Terminal Unicode Explorer.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 92 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [fractouille](https://github.com/PottierLoic/Fractouille) ⭐ 88 | 🐛 2 | 🌐 Rust | 📅 2026-03-19 - A simple fractal explorer running in your terminal.
* [lpl](https://github.com/SOF3/lpl) ⭐ 55 | 🐛 10 | 🌐 Rust | 📅 2025-04-05 - Command-line plotting for real-time CSV and JSON streams.
* [SeqTUI](https://github.com/ranwez-search/SeqTUI) ⭐ 47 | 🐛 0 | 🌐 Rust | 📅 2026-03-10 - A terminal-based viewer and command-line toolkit for molecular sequences.
* [meteo-tui](https://github.com/16arpi/meteo-tui) ⭐ 42 | 🐛 2 | 🌐 Rust | 📅 2026-07-21 - French weather app in the command line.
* [jOtter](https://github.com/samox73/jotter) ⭐ 39 | 🐛 0 | 🌐 Rust | 📅 2026-10-28 - A fast Jupyter notebook TUI with vim keys, inline plots and rendered LaTeX.
* [seqsizzle](https://github.com/ChangqingW/SeqSizzle) ⭐ 27 | 🐛 1 | 🌐 Rust | 📅 2026-10-01 - A terminal pager for viewing and searching FASTA and FASTQ DNA sequence files.
* [rsfrac](https://github.com/SkwalExe/rsfrac) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-04-23 - Terminal based fractal explorer, including Mandelbrot, Burning Ship, and Julia.
* [termCA](https://github.com/fabiooo4/termCA) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-03-03 - Interactive TUI Cellular Automata simulator.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-29._
