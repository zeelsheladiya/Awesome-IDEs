# Awesome-IDEs

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Welcome to **Awesome-IDEs**, a curated list of Integrated Development Environments (IDEs) and intelligent code editors. This list aims to help you discover the perfect environment for your workflow, whether you need a lightweight editor, a robust integrated environment, or a next-generation AI-powered assistant.

## Table of Contents

- [Introduction](#introduction)
- [AI-Powered & Next-Gen IDEs](#ai-powered--next-gen-ides)
- [General Purpose IDEs](#general-purpose-ides)
- [Language-Specific IDEs](#language-specific-ides)
    - [Python](#python)
    - [Java](#java)
    - [C/C++](#cc)
    - [PHP](#php)
    - [Go](#go)
    - [Rust](#rust)
    - [Ruby](#ruby)
- [Web Development](#web-development)
- [Mobile Development](#mobile-development)
- [Data Science](#data-science)
- [Game Development](#game-development)
- [Embedded Systems](#embedded-systems)
- [Version Control & Tools](#version-control--tools)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Choosing the right IDE can significantly impact your productivity. The landscape is evolving rapidly, with a new wave of **AI-First IDEs** changing how we write code. This list categorizes structured environments by their primary focus, while using **Tags** to highlight cross-capabilities (like Web support in a Java IDE or AI integration).

**Key to Tags:**
- `AI-Native`: Built from the ground up for AI.
- `AI-Ready`: Has strong, official AI plugins or integrations.
- `Lightweight`: Fast startup, low resource usage.
- `Polyglot`: Excellent support for many languages.

## AI-Powered & Next-Gen IDEs

These IDEs are built with Artificial Intelligence at their core or represent the next generation of high-performance editors.

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/cursor.png" alt="icon" width=15 height=15> **Cursor** | An AI-first code editor built on top of VS Code. It understands your entire codebase and allows for natural language coding and diff revisions. | [Website](https://cursor.com/) | `Mac` `Windows` `Linux` | Freemium, Proprietary | `AI-Native` `Fork-of-VSCode` |
| <img src="Resources/Icons/windsurf.png" alt="icon" width=15 height=15> **Windsurf** | The first "agentic" IDE by Codeium. It features "Flow" to keep context of your work and can act autonomously to refactor or generate code. | [Website](https://codeium.com/windsurf) | `Mac` `Windows` `Linux` | Freemium, Proprietary | `AI-Native` `Agentic` |
| <img src="Resources/Icons/zed.png" alt="icon" width=15 height=15> **Zed** | A high-performance, multiplayer code editor written in Rust. Designed for speed and collaboration with built-in AI chat. | [Website](https://zed.dev/) <br> [Github](https://github.com/zed-industries/zed) | `Mac` `Linux` `Windows (Preview)` | Free, Open-Source | `High-Performance` `Rust` `AI-Integrated` |
| <img src="Resources/Icons/trae.png" alt="icon" width=15 height=15> **Trae** | An adaptive AI IDE that offers a "Builder Mode" to automate end-to-end development tasks. | [Website](https://trae.ai/) | `Mac` `Windows` | Free, Proprietary | `AI-Native` |
| <img src="Resources/Icons/theia-ide.png" alt="icon" width=15 height=15> **Theia IDE** | An extensible, adaptable platform compatible with VS Code extensions, featuring transparent AI coding. | [Website](https://theia-ide.org/) <br> [Github](https://github.com/eclipse-theia/theia) | `Mac` `Windows` `Linux` `Online` | Free, Open-Source | `Cloud-Ready` `Extensible` |
| <img src="Resources/Icons/google_antigravity.png" alt="icon" width=15 height=15> **Google Antigravity** | Agent-first IDE by Google. Autonomous agents collaborating as developers. | [Website](https://antigravity.google) | `Web` `All Platforms` | Free (Preview) | `Agent-First` `Google` |
| <img src="Resources/Icons/void.png" alt="icon" width=15 height=15> **Void** | Open-source, AI-powered fork of VS Code. Privacy-focused alternative to Cursor. | [Website](https://voideditor.com) <br> [Github](https://github.com/voideditor/void) | `Mac` `Windows` `Linux` | Free, Open-Source | `Fork-of-VSCode` `Privacy` |
| <img src="Resources/Icons/kiro.svg" alt="icon" width=15 height=15> **Kiro** | Agentic IDE by AWS. Spec-driven development with autonomous capabilities. | [Website](https://kiro.dev) | `Mac` `Windows` `Linux` | Free (Preview) | `AWS` `Agentic` |
| <img src="Resources/Icons/qoder.png" alt="icon" width=15 height=15> **Qoder** | Agentic AI IDE by Alibaba. "Programming through conversation". | [Website](https://qoder.com) | `Mac` `Windows` | Free (Preview) | `Alibaba` `Agentic` |
| <img src="Resources/Icons/cline.png" alt="icon" width=15 height=15> **Cline** | Autonomous coding agent extension for VS Code. | [Github](https://github.com/cline/cline) | `VS Code` | Free, Open-Source | `Extension` `Agent` |
| <img src="Resources/Icons/opencode.png" alt="icon" width=15 height=15> **OpenCode** | AI coding agent that integrates with terminals and IDEs. | [Website](https://opencode.ai) <br> [Github](https://github.com/sst/opencode) | `Terminal` `VS Code` | Free, Open-Source | `Agent` `Terminal-UI` |
| <img src="Resources/Icons/coder.png" alt="icon" width=15 height=15> **Coder** | Coding Agent Multiplexer. Manage multiple AI agents in parallel. | [Website](https://coder.com) <br> [Github](https://github.com/coder/code-server) | `Mac` `Windows` `Linux` | Paid | `Agent-Manager` |
| <img src="Resources/Icons/v0.png" alt="icon" width=15 height=15> **v0** | Generative UI system by Vercel. React + Tailwind CSS generation. | [Website](https://v0.dev) | `Web` | Freemium | `UI-Gen` `React` |
| <img src="Resources/Icons/jetbrains-fleet.svg" alt="icon" width=15 height=15> **JetBrains Fleet** | A distributed, polyglot IDE built from scratch by JetBrains. Uses the IntelliJ engine but with a lightweight UI. | [Website](https://www.jetbrains.com/fleet) | `Mac` `Windows` `Linux` | Freemium, Proprietary | `Distributed` `Polyglot` |

## General Purpose IDEs

Versatile editors and IDEs that support a wide array of languages and workflows via plugins.

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/vscode.png" alt="icon" width=15 height=15> **Visual Studio Code** | The most popular code editor, highly customizable with a massive extension marketplace. | [Website](https://code.visualstudio.com/) <br> [Github](https://github.com/microsoft/vscode) | `Mac` `Windows` `Linux` `Web` | Free, Open-Source | `Polyglot` `Extensible` `AI-Ready` |
| <img src="Resources/Icons/visual_studio.png" alt="icon" width=20 height=20> **Visual Studio** | A comprehensive IDE for .NET and C++ development, widely used in enterprise environments. | [Website](https://visualstudio.microsoft.com/) | `Windows` `Mac` | Freemium, Proprietary | `Enterprise` `.NET` `C++` |
| <img src="Resources/Icons/vim.png" alt="icon" width=15 height=15> **Vim** | A highly configurable text editor for efficient text editing. Often used as an IDE by power users. | [Website](https://www.vim.org/) | `All Platforms` | Free, Open-Source | `CLI` `Lightweight` |
| <img src="Resources/Icons/Emacs.png" alt="icon" width=15 height=15> **Emacs** | An extensible, customizable, self-documenting display editor. "An OS inside an editor". | [Website](https://www.gnu.org/software/emacs/) | `All Platforms` | Free, Open-Source | `CLI` `Lisp` `Extensible` |
| <img src="Resources/Icons/UltraEdit.png" alt="icon" width=15 height=15> **UltraEdit** | A powerful commercial text editor for handling large files and complex editing tasks. | [Website](https://www.ultraedit.com/) | `Mac` `Windows` `Linux` | Paid | `Text-Processing` `Hex` |
| <img src="Resources/Icons/Lapce.png" alt="icon" width=15 height=15> **Lapce** | A lightning-fast, open-source code editor written in Rust. | [Website](https://lap.dev/lapce/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Rust` `Fast` |
| <img src="Resources/Icons/sublime.png" alt="icon" width=15 height=15> **Sublime Text** | Sophisticated text editor for code, markup, and prose. Known for speed. | [Website](https://www.sublimetext.com/) | `Mac` `Windows` `Linux` | Paid (Trial) | `Fast` `Extensible` |
| <img src="Resources/Icons/Notepad++.png" alt="icon" width=15 height=15> **Notepad++** | Free source code editor and Notepad replacement that supports several languages. | [Website](https://notepad-plus-plus.org/) | `Windows` | Free, Open-Source | `Lightweight` `Classic` |
| <img src="Resources/Icons/neovim.png" alt="icon" width=15 height=15> **Neovim** | Hyperextensible Vim-based text editor. | [Website](https://neovim.io) <br> [Github](https://github.com/neovim/neovim) | `Mac` `Windows` `Linux` `BSD` | Free, Open-Source | `CLI` `Modal` `Lua` |
| <img src="Resources/Icons/helix.png" alt="icon" width=15 height=15> **Helix** | A post-modern modal text editor built in Rust. | [Website](https://helix-editor.com) <br> [Github](https://github.com/helix-editor/helix) | `Mac` `Windows` `Linux` | Free, Open-Source | `Rust` `Modal` `CLI` |
| <img src="Resources/Icons/micro.png" alt="icon" width=15 height=15> **Micro** | A modern, intuitive terminal-based text editor. | [Website](https://micro-editor.github.io/) <br> [Github](https://github.com/zyedidia/micro) | `Mac` `Windows` `Linux` | Free, Open-Source | `CLI` `Mouse-Support` |
| <img src="Resources/Icons/vscodium.png" alt="icon" width=15 height=15> **VSCodium** | Binary releases of VS Code without Microsoft telemetry/branding. | [Website](https://vscodium.com/) <br> [Github](https://github.com/VSCodium/vscodium) | `Mac` `Windows` `Linux` | Free, Open-Source | `Privacy` `VSCode` |
| <img src="Resources/Icons/geany.png" alt="icon" width=15 height=15> **Geany** | Powerful, stable, and lightweight programmer's text editor. | [Website](https://geany.org) <br> [Github](https://github.com/geany/geany) | `Mac` `Windows` `Linux` | Free, Open-Source | `Lightweight` `Fast` |
| <img src="Resources/Icons/kate.png" alt="icon" width=15 height=15> **Kate** | Advanced text editor by KDE. | [Website](https://kate-editor.org/) <br> [GitLab](https://invent.kde.org/utilities/kate) | `Mac` `Windows` `Linux` | Free, Open-Source | `KDE` `Lightweight` |
| <img src="Resources/Icons/gedit.png" alt="icon" width=15 height=15> **gedit** | The official text editor of the GNOME desktop environment. | [Website](https://wiki.gnome.org/Apps/Gedit) <br> [GitLab](https://gitlab.gnome.org/GNOME/gedit) | `Linux` `Mac` `Windows` | Free, Open-Source | `GNOME` `Simple` |
| <img src="Resources/Icons/bbedit.png" alt="icon" width=15 height=15> **BBEdit** | Leading professional HTML and text editor for macOS. | [Website](https://www.barebones.com/products/bbedit/) | `Mac` | Freemium, Proprietary | `Mac-Native` `Powerful` |
| <img src="Resources/Icons/Textmate.png" alt="icon" width=15 height=15> **TextMate** | Powerful and customizable text editor for macOS. | [Website](https://macromates.com/) <br> [Github](https://github.com/textmate/textmate) | `Mac` | Free, Open-Source | `Mac-Native` `Classic` |
| <img src="Resources/Icons/cotedit.png" alt="icon" width=15 height=15> **CotEditor** | Lightweight plain-text editor for macOS. | [Website](https://coteditor.com/) <br> [Github](https://github.com/coteditor/CotEditor) | `Mac` | Free, Open-Source | `Mac-Native` `Lightweight` |
| <img src="Resources/Icons/spacemacs.svg" alt="icon" width=15 height=15> **Spacemacs** | Community-driven Emacs distribution. "The best of both Emacs and Vim". | [Website](https://www.spacemacs.org/) <br> [Github](https://github.com/syl20bnr/spacemacs) | `Mac` `Windows` `Linux` `BSD` | Free, Open-Source | `Emacs` `Vim` |
| <img src="Resources/Icons/litexl.png" alt="icon" width=15 height=15> **Lite XL** | A lightweight text editor written in Lua. | [Website](https://lite-xl.com) <br> [Github](https://github.com/lite-xl/lite-xl) | `Mac` `Windows` `Linux` | Free, Open-Source | `Lua` `Lightweight` |
| <img src="Resources/Icons/cudatext.png" alt="icon" width=15 height=15> **CudaText** | Cross-platform text editor with Python API. | [Website](https://cudatext.github.io/) <br> [Github](https://github.com/Alexey-T/CudaText) | `Mac` `Windows` `Linux` | Free, Open-Source | `Pascal` `Native` |
| <img src="Resources/Icons/athas.png" alt="icon" width=15 height=15> **Athas** | High-performance, Vim-based editor built with Tauri and React. | [Website](https://athas.dev) <br> [Github](https://github.com/athasdev/athas) | `Mac` `Windows` `Linux` | Free, Open-Source | `Vim` `Web-Tech` |
| <img src="Resources/Icons/fresh_text_editor.jpg" alt="icon" width=15 height=15> **Fresh Editor** | Modern terminal-based text editor and IDE. | [Website](https://sinelaw.github.io/fresh/) <br> [Github](https://github.com/sinelaw/fresh) | `Mac` `Linux` | Free, Open-Source | `Terminal` `IDE-Like` |
| <img src="Resources/Icons/graviton.png" alt="icon" width=15 height=15> **Graviton** | Minimalistic, cross-platform code editor. | [Website](https://graviton.netlify.app/) <br> [Github](https://github.com/Graviton-Code-Editor/Graviton-App) | `Mac` `Windows` `Linux` | Free, Open-Source | `Minimal` |
| <img src="Resources/Icons/pspad.png" alt="icon" width=15 height=15> **PSPad** | Freeware text and source editor for Windows. | [Website](http://www.pspad.com/) | `Windows` | Free | `Classic` |
| <img src="Resources/Icons/emeditor.png" alt="icon" width=15 height=15> **EmEditor** | Fast, lightweight, yet extensible text editor for Windows. Great for large files. | [Website](https://www.emeditor.com/) | `Windows` | Paid | `Large-Files` |
| <img src="Resources/Icons/SciTE.png" alt="icon" width=15 height=15> **SciTE** | CheckOut Scintilla Text Editor. | [Website](https://www.scintilla.org/SciTE.html) <br> [Github](https://github.com/ScintillaOrg/lexilla) | `Windows` `Linux` | Free, Open-Source | `Minimal` |
| <img src="Resources/Icons/Bluefish.png" alt="icon" width=15 height=15> **Bluefish** | Powerful editor targeted towards programmers and web developers. | [Website](http://bluefish.openoffice.nl/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Fast` |
| <img src="Resources/Icons/textadept.png" alt="icon" width=15 height=15> **Textadept** | Fast, minimalist, and extensible cross-platform text editor. | [Website](https://orbitalquark.github.io/textadept/) <br> [Github](https://github.com/orbitalquark/textadept) | `Mac` `Windows` `Linux` | Free, Open-Source | `Lua` `Minimal` |
| <img src="Resources/Icons/lighttable.png" alt="icon" width=15 height=15> **Light Table** | Next generation code editor. (Legacy). | [Website](http://lighttable.com/) <br> [Github](https://github.com/LightTable/LightTable) | `Mac` `Windows` `Linux` | Free, Open-Source | `ClojureScript` `Legacy` |
| <img src="Resources/Icons/Leafpad.png" alt="icon" width=15 height=15> **Leafpad** | Simple GTK+ text editor. | [Website](http://tarot.freeshell.org/leafpad/) | `Linux` | Free, Open-Source | `Simple` |
| <img src="Resources/Icons/bbedit.png" alt="icon" width=15 height=15> **BBEdit** | (Discontinued) Replaced by BBEdit. | [Website](https://www.barebones.com/products/textwrangler/) | `Mac` | Free | `Legacy` |

## Language-Specific IDEs

While many general IDEs support these languages, the following are specialized or "Best-in-Class" for specific ecosystems.

### PHP

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/PhpStorm.png" alt="icon" width=15 height=15> **PhpStorm** | Lightning-smart PHP IDE by JetBrains. | [Website](https://www.jetbrains.com/phpstorm/) | `Mac` `Windows` `Linux` | Paid | `PHP` `Web` |

### Go

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/GoLand.png" alt="icon" width=15 height=15> **GoLand** | Capable and ergonomic Go IDE by JetBrains. | [Website](https://www.jetbrains.com/go/) | `Mac` `Windows` `Linux` | Paid | `Go` `Microservices` |

### Rust

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/rustrover.png" alt="icon" width=15 height=15> **RustRover** | Dedicated Rust IDE by JetBrains. | [Website](https://www.jetbrains.com/rust/) | `Mac` `Windows` `Linux` | Paid | `Rust` `Native` |

### Python

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/PyCharm.png" alt="icon" width=15 height=15> **PyCharm** | The premier Python IDE with code analysis, graphical debugger, and Django support. | [Website](https://www.jetbrains.com/pycharm/) | `Mac` `Windows` `Linux` | Freemium, Proprietary | `Intelligent` `Web` `Data-Science` |
| <img src="Resources/Icons/Spyder.png" alt="icon" width=40 height=20> **Spyder** | A scientific environment written in Python, for Python. Great for data analysts. | [Website](https://www.spyder-ide.org/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Scientific` `Data-Analysis` |
| <img src="Resources/Icons/Thonny.png" alt="icon" width=15 height=15> **Thonny** | Python IDE for beginners. | [Website](https://thonny.org/) <br> [Github](https://github.com/thonny/thonny) | `Mac` `Windows` `Linux` | Free, Open-Source | `Education` `Beginner` |
| <img src="Resources/Icons/wingpythonide.png" alt="icon" width=15 height=15> **Wing IDE** | Powerful Python IDE with powerful debugger and intelligent editor. | [Website](https://wingware.com/) | `Mac` `Windows` `Linux` | Paid, Freemium | `Python` |
| <img src="Resources/Icons/pydev.jpg" alt="icon" width=15 height=15> **PyDev** | Python IDE for Eclipse. | [Website](https://www.pydev.org/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Eclipse` `Plugin` |
| <img src="Resources/Icons/eric.png" alt="icon" width=15 height=15> **Eric** | Full featured Python editor and IDE, written in Python. | [Website](https://eric-ide.python-projects.org/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Python` `Qt` |
| <img src="Resources/Icons/PyScripter.png" alt="icon" width=15 height=15> **PyScripter** | Lightweight, open-source Python IDE for Windows. | [Github](https://github.com/pyscripter/pyscripter) | `Windows` | Free, Open-Source | `Lightweight` |
| <img src="Resources/Icons/pyzo.png" alt="icon" width=15 height=15> **IEP (Pyzo)** | Cross-platform Python IDE focused on interactivity and introspection. | [Website](https://pyzo.org/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Science` |

### Java

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/IntelliJ_IDEA.png" alt="icon" width=15 height=15> **IntelliJ IDEA** | Capable and ergonomic IDE for JVM languages. deeply intelligent coding assistance. | [Website](https://www.jetbrains.com/idea/) | `Mac` `Windows` `Linux` | Freemium, Proprietary | `Java` `Kotlin` `Enterprise` |
| <img src="Resources/Icons/Eclipse.png" alt="icon" width=15 height=15> **Eclipse** | Famous open-source IDE, widely used for Java and legacy enterprise applications. | [Website](https://www.eclipse.org/) | `Mac` `Windows` `Linux` | Free, Open-Source | `Java` `Plugin-Ecosystem` |
| <img src="Resources/Icons/NetBeans.png" alt="icon" width=15 height=15> **NetBeans** | Official IDE for Java 8. Good support to modular applications. | [Website](https://netbeans.apache.org/) <br> [Github](https://github.com/apache/netbeans) | `Mac` `Windows` `Linux` | Free, Open-Source | `Java` `Swing` |

### C/C++

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/clion.png" alt="icon" width=15 height=15> **CLion** | Cross-platform C/C++ IDE by JetBrains. Uses CMake natively. | [Website](https://www.jetbrains.com/clion/) | `Mac` `Windows` `Linux` | Paid | `CMake` `Embedded` |
| <img src="Resources/Icons/qt.png" alt="icon" width=15 height=15> **Qt Creator** | Designed for developing applications with the Qt framework. | [Website](https://www.qt.io/) | `Mac` `Windows` `Linux` | Freemium | `Qt` `GUI` |
| <img src="Resources/Icons/codeblocks.png" alt="icon" width=20 height=20> **Code::Blocks** | Open-source C/C++ IDE built to meet the most demanding needs of its users. | [Website](http://www.codeblocks.org/) | `Windows` `Linux` | Free, Open-Source | `Lightweight` |
| <img src="Resources/Icons/kdevelop.png" alt="icon" width=20 height=20> **KDevelop** | Cross-platform IDE for C, C++, Python, QML/JavaScript and PHP. | [Website](https://apps.kde.org/kdevelop/) | `Windows` `Linux` | Free, Open-Source | `KDE` |
| <img src="Resources/Icons/CodeLite.png" alt="icon" width=15 height=15> **CodeLite** | Lightweight open-source IDE for C/C++/PHP and Node.js. | [Website](https://codelite.org) | `Mac` `Windows` `Linux` | Free, Open-Source | `Lightweight` |
| <img src="Resources/Icons/rad_studio.png" alt="icon" width=15 height=15> **RAD Studio** | Powerful rapid application development suite for GUI-centric apps. | [Website](https://www.embarcadero.com/products/rad-studio) | `Windows` | Paid | `GUI` `Delphi` `C++` |
| <img src="Resources/Icons/devc++.png" alt="icon" width=15 height=15> **Dev-C++** | Legacy full-featured IDE for C/C++. | [Website](http://www.bloodshed.net) | `Windows` | Free, Open-Source | `Legacy` `Lightweight` |
| <img src="Resources/Icons/Ultimate++.png" alt="icon" width=15 height=15> **Ultimate++** | C++ cross-platform rapid application development framework. | [Website](https://www.ultimatepp.org) | `Windows` `Linux` | Free, Open-Source | `RAD` |
| <img src="Resources/Icons/Anjuta.png" alt="icon" width=15 height=15> **Anjuta** | Versatile IDE for C/C++ on GNU/Linux. | [Website](https://wiki.gnome.org/Apps/Anjuta) | `Linux` | Free, Open-Source | `GNOME` |
| <img src="Resources/Icons/cevelop.png" alt="icon" width=15 height=15> **Cevelop** | The C++ IDE for professional developers. | [Website](https://www.cevelop.com) | `Mac` `Windows` `Linux` | Free, Paid | `Professional` |
| <img src="Resources/Icons/Zinjai.png" alt="icon" width=15 height=15> **Zinjai** | Designed for use by students of programming. | [Website](https://zinjai.sourceforge.net) | `Mac` `Windows` `Linux` | Free, Open-Source | `Education` |
| <img src="Resources/Icons/JCppEdit.png" alt="icon" width=15 height=15> **JCppEdit** | Multi-language environment starting from C/C++ to Java/Web. | [Website](https://www.jcppedit.com) | `Windows` `Linux` | Free, Paid | `Multi-Language` |

### Ruby

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/RubyMine.png" alt="icon" width=15 height=15> **RubyMine** | A dedicated Ruby and Rails IDE with smart assistance. | [Website](https://www.jetbrains.com/ruby/) | `Mac` `Windows` `Linux` | Paid | `Ruby` `Rails` |

## Web Development

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/WebStorm.png" alt="icon" width=15 height=15> **WebStorm** | The smartest JavaScript IDE. Fully equipped for advanced web development. | [Website](https://www.jetbrains.com/webstorm/) | `Mac` `Windows` `Linux` | Paid | `JavaScript` `TypeScript` `Frontend` |
| <img src="Resources/Icons/aptana_studio.jpeg" alt="icon" width=15 height=15> **Aptana Studio** | Professional, open-source development tool for the open web. | [Github](https://github.com/aptana/studio3) | `Mac` `Windows` `Linux` | Free, Open-Source | `Web` `Eclipse` |
| <img src="Resources/Icons/webuilder.png" alt="icon" width=15 height=15> **WeBuilder** | All-in-one web code editor for HTML, CSS, JavaScript, PHP, Ruby, Python, etc. | [Website](https://www.blumentals.net/webuilder/) | `Windows` | Paid | `All-in-One` |
| <img src="Resources/Icons/Komodo_IDE.png" alt="icon" width=15 height=15> **Komodo IDE** | One IDE for all your languages (Python, PHP, Go, Perl, Tcl, Ruby, etc). | [Website](https://www.activestate.com/products/komodo-ide/) <br> [Github](https://github.com/ActiveState/OpenKomodoIDE) | `Mac` `Windows` `Linux` | Free (ActiveState) | `Polyglot` `Legacy` |
| <img src="Resources/Icons/firebase_studio.png" alt="icon" width=15 height=15> **Firebase Studio** | Web-based toolset for Firebase development. | [Website](https://firebase.studio/) | `Web` | Free | `Firebase` |

## Mobile Development

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/Android_Studio.png" alt="icon" width=15 height=15> **Android Studio** | Official IDE for Android development. Based on IntelliJ IDEA. | [Website](https://developer.android.com/studio) | `Mac` `Windows` `Linux` | Free, Open-Source | `Android` `Kotlin` |
| <img src="Resources/Icons/Xcode.png" alt="icon" width=15 height=15> **Xcode** | The only IDE for developing fully functional iOS/macOS apps. | [Website](https://developer.apple.com/xcode/) | `Mac` | Free, Proprietary | `iOS` `Swift` `macOS` |
| <img src="Resources/Icons/Squircle_IDE.png" alt="icon" width=15 height=15> **Squircle IDE** | A fast multi-language code editor for Android devices. | [Github](https://github.com/massivemadness/Squircle-CE) | `Android` | Free, Open-Source | `Mobile-on-Mobile` |
| <img src="Resources/Icons/cppdroid.png" alt="icon" width=15 height=15> **CppDroid** | simple C/C++ IDE focused on learning. | [PlayStore](https://play.google.com/store/apps/details?id=name.antonsmirnov.android.cppdroid) | `Android` | Freemium | `Mobile-on-Mobile` |
| <img src="Resources/Icons/pydroid3.png" alt="icon" width=15 height=15> **Pydroid 3** | Easy to use educational Python 3 IDE for Android. | [PlayStore](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3) | `Android` | Freemium | `Python` `Mobile` |
| <img src="Resources/Icons/cosmic_ide.png" alt="icon" width=15 height=15> **Cosmic IDE** | JVM (Java/Kotlin) IDE for Android. | [Github](https://github.com/Cosmic-IDE/Cosmic-IDE) | `Android` | Free, Open-Source | `Java` `Kotlin` |

## Data Science

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/Jupyter.png" alt="icon" width=15 height=15> **Jupyter** | Open-source web application for interactive computing and notebooks. | [Website](https://jupyter.org/) | `Web` `All Platforms` | Free, Open-Source | `Notebooks` `Python` `R` |
| <img src="Resources/Icons/RStudio.png" alt="icon" width=50 height=15> **RStudio** | The premier IDE for R. Integrated tools for plotting, history, and workspace. | [Website](https://rstudio.com/) | `Mac` `Windows` `Linux` | Free, Open-Source | `R` `Statistics` |
| <img src="Resources/Icons/dataspell.png" alt="icon" width=15 height=15> **DataSpell** | The IDE for Data Science by JetBrains. | [Website](https://www.jetbrains.com/dataspell/) | `Mac` `Windows` `Linux` | Paid | `Jupyter` `Python` |
| <img src="Resources/Icons/zasper.svg" alt="icon" width=15 height=15> **Zasper** | AI-native IDE for Data Science. "Cursor for Data Science". | [Website](https://zasper.io) <br> [Github](https://github.com/zasper-io/zasper) | `Web` | Free (Preview) | `AI` `Notebooks` |

## Game Development

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/unity.png" alt="icon" width=15 height=15> **Unity** | Real-time 3D development platform for building games and AR/VR experiences. | [Website](https://unity.com/) | `Mac` `Windows` `Linux` | Freemium | `3D` `C#` |
| <img src="Resources/Icons/unreal.png" alt="icon" width=15 height=15> **Unreal Engine** | High-fidelity game engine used for AAA games and cinema. | [Website](https://www.unrealengine.com/) | `Mac` `Windows` `Linux` | Freemium | `AAA` `C++` `Visual-Scripting` |
| <img src="Resources/Icons/godot.png" alt="icon" width=15 height=15> **Godot** | Feature-packed, cross-platform, open-source game engine. | [Website](https://godotengine.org/) <br> [Github](https://github.com/godotengine/godot) | `Mac` `Windows` `Linux` | Free, Open-Source | `Lightweight` `2D/3D` |
| <img src="Resources/Icons/cryengine.png" alt="icon" width=15 height=15> **CryEngine** | A game engine known for its impressive visual fidelity and real-time physics. | [Website](https://www.cryengine.com/) | `Windows` | Free, Proprietary | `AAA` `Visuals` |
| <img src="Resources/Icons/game_maker.png" alt="icon" width=25 height=15> **GameMaker** | The ultimate 2D game development environment. | [Website](https://www.yoyogames.com/gamemaker) | `Windows` `Mac` | Paid | `2D` `Beginner-Friendly` |
| <img src="Resources/Icons/construct.png" alt="icon" width=15 height=15> **Construct** | Visual game engine for creating 2D games without coding. | [Website](https://www.construct.net/) | `Web` `Windows` | Paid | `No-Code` `2D` |
| <img src="Resources/Icons/defold.png" alt="icon" width=15 height=15> **Defold** | focused on 2D game development and ease of use. | [Website](https://defold.com/) <br> [Github](https://github.com/defold/defold) | `Mac` `Windows` `Linux` | Free, Open-Source | `2D` `Lightweight` |
| <img src="Resources/Icons/stride.png" alt="icon" width=15 height=15> **Stride** | Open-source 3D game engine (formerly Xenko). | [Website](https://stride3d.net/) <br> [Github](https://github.com/stride3d/stride) | `Windows` | Free, Open-Source | `.NET` `C#` |
| <img src="Resources/Icons/hazel.png" alt="icon" width=15 height=15> **Hazel** | Early-stage interactive application and rendering engine. | [Github](https://github.com/TheCherno/Hazel) | `Windows` | Free, Open-Source | `Learning` `Rendering` |
| <img src="Resources/Icons/open-3d-engine.png" alt="icon" width=15 height=15> **Open 3D Engine** | AAA-capable, open-source 3D engine. | [Website](https://o3de.org) <br> [Github](https://github.com/o3de/o3de) | `Windows` `Linux` | Free, Open-Source | `AAA` `3D` |
| <img src="Resources/Icons/redot_engine.png" alt="icon" width=15 height=15> **Redot Engine** | Community-driven fork of Godot Engine. | [Website](https://redotengine.org) <br> [Github](https://github.com/Redot-Engine/redot-engine) | `Mac` `Windows` `Linux` `Android` | Free, Open-Source | `Godot-Fork` `2D/3D` |
| <img src="Resources/Icons/microstudio.png" alt="icon" width=15 height=15> **MicroStudio** | Online game engine for learning and prototyping. | [Website](https://microstudio.dev) <br> [Github](https://github.com/pmgl/microstudio) | `Web` `Mac` `Windows` `Linux` | Free, Open-Source | `Web` `Learning` |
| <img src="Resources/Icons/bevy.svg" alt="icon" width=15 height=15> **Bevy** | A data-driven game engine built in Rust. | [Website](https://bevyengine.org) <br> [Github](https://github.com/bevyengine/bevy) | `Mac` `Windows` `Linux` `Web` | Free, Open-Source | `Rust` `ECS` |
| <img src="Resources/Icons/Verge3D.png" alt="icon" width=15 height=15> **Verge3D** | Toolkit for creating immersive web-based 3D experiences (Blender/Max/Maya). | [Website](https://www.soft8soft.com/verge3d/) | `Web` `Blender` | Paid | `Web` `No-Code` |
| <img src="Resources/Icons/playcanvas.png" alt="icon" width=15 height=15> **PlayCanvas** | Cloud-first web game engine. Collaborative 3D development. | [Website](https://playcanvas.com) <br> [Github](https://github.com/playcanvas/engine) | `Web` | Freemium | `Cloud` `Web` |
| <img src="Resources/Icons/torque3d.png" alt="icon" width=15 height=15> **Torque 3D** | Open-source C++ engine with a long history. | [Website](https://torque3d.org) <br> [Github](https://github.com/TorqueGameEngines/Torque3D) | `Windows` `Mac` `Linux` | Free, Open-Source | `C++` `Legacy` |
| <img src="Resources/Icons/xogot.png" alt="icon" width=15 height=15> **XoGot** | Godot engine adapted for iPadOS development. | [Website](https://xogot.com) | `iOS` | Freemium | `iPad` `Mobile` |
| <img src="Resources/Icons/flax_engine.png" alt="icon" width=15 height=15> **Flax Engine** | High-quality 3D engine with C++ and C# scripting. | [Website](https://flaxengine.com) <br> [Github](https://github.com/FlaxEngine/FlaxEngine) | `Windows` `Mac` `Linux` | Free (Royalties) | `C++` `C#` |
| <img src="Resources/Icons/source_sdk.png" alt="icon" width=15 height=15> **Source SDK** | Tools for creating mods and games for Valve's Source Engine. | [Website](https://developer.valvesoftware.com/wiki/Source_SDK) | `Windows` `Linux` | Free | `Modding` `Valve` |
| <img src="Resources/Icons/wicked_engine.png" alt="icon" width=15 height=15> **Wicked Engine** | Modern C++ engine focusing on rendering performance. | [Website](https://wickedengine.net) <br> [Github](https://github.com/turanszkij/WickedEngine) | `Windows` `Linux` | Free, Open-Source | `C++` `Rendering` |
| <img src="Resources/Icons/Roblox_Studio.png" alt="icon" width=15 height=15> **Roblox Studio** | The tool for creating games on the Roblox platform. | [Website](https://www.roblox.com/create) | `Windows` `Mac` | Free (Rev Share) | `Lua` `Platform` |
| <img src="Resources/Icons/ezengine.png" alt="icon" width=15 height=15> **EzEngine** | Modular C++ game engine. | [Website](https://ezengine.net) <br> [Github](https://github.com/ezEngine/ezEngine) | `Windows` `Linux` | Free, Open-Source | `C++` `Modular` |
| <img src="Resources/Icons/harfang3d.png" alt="icon" width=15 height=15> **Harfang 3D** | Multi-language 3D engine (Python, Lua, C++). | [Website](https://www.harfang3d.com) | `Windows` `Linux` | Freemium | `Python` `Lua` |
| <img src="Resources/Icons/enigma.png" alt="icon" width=15 height=15> **Enigma** | Open-source game development environment compatible with Game Maker. | [Website](https://enigma-dev.org) <br> [Github](https://github.com/enigma-dev/enigma-dev) | `Windows` `Mac` `Linux` | Free, Open-Source | `GameMaker` |
| <img src="Resources/Icons/hology.jpg" alt="icon" width=15 height=15> **Hology** | Web-first game engine for browser games. | [Website](https://hology.app) | `Web` | Free | `Web` `Browser` |
| <img src="Resources/Icons/evergine.png" alt="icon" width=15 height=15> **Evergine (Wave)** | Industrial-grade component-based engine (formerly Wave Engine). | [Website](https://evergine.com) | `Windows` | Free | `.NET` `C#` |
| <img src="Resources/Icons/fyrox.png" alt="icon" width=15 height=15> **Fyrox** | Feature-rich game engine written in Rust. | [Website](https://fyrox.rs) <br> [Github](https://github.com/FyroxEngine/Fyrox) | `Windows` `Mac` `Linux` | Free, Open-Source | `Rust` |
| <img src="Resources/Icons/neoaxis.jpg" alt="icon" width=15 height=15> **NeoAxis** | Versatile 3D/2D engine with C# scripting. | [Website](https://www.neoaxis.com) | `Windows` | Free (Royalties) | `C#` |
| <img src="Resources/Icons/RogueEngine.svg" alt="icon" width=15 height=15> **Rogue Engine** | Unity-like environment for Three.js (Web). | [Website](https://rogueengine.io) | `Web` | Free, Open-Source | `Three.js` `Web` |
| <img src="Resources/Icons/amethyst.png" alt="icon" width=15 height=15> **Amethyst** | Data-driven game engine written in Rust (Maintenance Mode). | [Github](https://github.com/amethyst/amethyst) | `Windows` `Mac` `Linux` | Free, Open-Source | `Rust` `Legacy` |
| <img src="Resources/Icons/leadwerks.png" alt="icon" width=15 height=15> **Leadwerks** | Easy-to-learn game engine for C++ and Lua. | [Website](https://www.leadwerks.com) | `Windows` `Linux` | Paid | `C++` `Lua` |
| <img src="Resources/Icons/range_engine.png" alt="icon" width=15 height=15> **Range Engine** | Game engine based on Blender. | [Website](https://rangeengine.tech) | `Windows` `Linux` | Free, Open-Source | `Blender` |
| <img src="Resources/Icons/wonderlandengine.png" alt="icon" width=15 height=15> **Wonderland Engine** | Development platform for WebXR and 3D web. | [Website](https://wonderlandengine.com) | `Web` | Freemium | `WebXR` `Web` |
| <img src="Resources/Icons/verus_engine.png" alt="icon" width=15 height=15> **Verus Engine** | High-performance C++ game engine. | [Website](https://en.verushub.com/) <br> [Github](https://github.com/dmaluev/verus) | `Windows` | Free, Open-Source | `C++` |
| <img src="Resources/Icons/nau_engine.jpeg" alt="icon" width=15 height=15> **Nau Engine** | Open-source engine for creating games on all platforms. | [Website](https://nauengine.org) <br> [Github](https://github.com/NauEngine) | `Windows` `Mac` `Linux` | Free, Open-Source | `C++` |
| <img src="Resources/Icons/cave_engine.png" alt="icon" width=15 height=15> **Cave Engine** | Python-powered 3D game engine. | [Website](https://uniday.studio/cave/) | `Windows` | Free | `Python` |

## Embedded Systems

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/PlatformIO.png" alt="icon" width=15 height=15> **PlatformIO** | Professional collaborative platform for embedded development. | [Website](https://platformio.org/) | `Plugin (VSCode, etc)` | Free, Open-Source | `IoT` `Embedded` |
| <img src="Resources/Icons/avalonstudio.png" alt="icon" width=15 height=15> **AvalonStudio** | Cross platform IDE for Embedded C/C++ and .NET Core. | [Github](https://github.com/VitalElement/AvalonStudio) | `Mac` `Windows` `Linux` | Free, Open-Source | `.NET` `Embedded` |
| <img src="Resources/Icons/ElectronIDE.png" alt="icon" width=15 height=15> **ElectronIDE** | Web based Arduino IDE. | [Github](https://github.com/joshmarinacci/ElectronIDE) | `Mac` `Windows` `Linux` `Web` | Free, Open-Source | `Arduino` |

## Version Control & Tools

| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/Git.png" alt="icon" width=15 height=15> **Git** | Distributed version control system. | [Website](https://git-scm.com/) | `Mac` `Windows` `Linux` `BSD` | Free, Open-Source | `VCS` |
| <img src="Resources/Icons/github.png" alt="icon" width=15 height=15> **GitHub** | Hosting service for software development and version control using Git. | [Website](https://github.com/) | `Web` | Freemium | `Hosting` `Collaboration` |
| <img src="Resources/Icons/judge0.png" alt="icon" width=15 height=15> **Judge0** | Robust, scalable, and open-source online code execution system. | [Website](https://judge0.com/) <br> [Github](https://github.com/judge0/judge0) | `Web` `API` | Free, Open-Source | `Compiler-API` |

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

Licensed under the [Creative Commons Attribution 4.0 International License](LICENSE).

---
*Disclaimer: Usage of icons is for identification purposes only.*
