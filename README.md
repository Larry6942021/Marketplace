<p align='center'>
  <img src="https://github.com/SkEditorTeam/SkEditor/blob/main/SkEditor.png?raw=true" width="300">
</p>

<div align='center'>

# SkEditor: Marketplace
<a href='https://github.com/SkEditorTeam/SkEditor/releases'><img src='https://img.shields.io/github/v/release/SkEditorTeam/SkEditor?color=%237a34eb&label=version&style=flat-square'></a>
<a href='https://github.com//SkEditorPlus/SkEditor/blob/main/LICENSE'><img src='https://img.shields.io/github/license/SkEditorTeam/SkEditor?color=%230fa685&label=license&style=flat-square'></a>
<a href='https://github.com//SkEditorPlus/SkEditor/releases/latest'><img src='https://img.shields.io/github/downloads/SkEditorTeam/SkEditor/total?color=%230fa621&style=flat-square'></a>

**The ultimate IDE for Skript.** Fast. Modern. Extensible.

The SkEditor Marketplace is a community-driven repository that powers the in-app discovery and installation of SkEditor enhancements. By submitting your work here, you make it instantly available to thousands of Skript developers looking to customize their IDE experience.

> | Category | Content | Deployment |
> |------|-----|-------|
> | **Addons** | Custom .dll logic and API extensions | In-app Addons folder |
> | **Themes** | Visual XAML skins and color palettes | Settings > Themes |
> | **Syntax** | Language definition files for Skript & more | Syntax Highlighting menu |
> | **Packs** | Bundled themes and syntax definitions | One-click install |


```bash
# How to submit your own extension
# 1. Fork the SkEditorTeam/Marketplace repository
# 2. Add your extension files to the correct category folder
# 3. Open a Pull Request to the main branch
```

[!NOTE]
> **Submissions are manual.** To maintain quality and security, every marketplace entry must be submitted via a Pull Request to this repository. Once merged, your addon or theme will appear in the official SkEditor Marketplace tab automatically.

---

## 📂 Repository Structure

The Marketplace is organized by content type to ensure the [SkEditor](https://github.com) client can index them correctly:


| Folder | Purpose |
|----------|-------------|
| '/Addons' | Advanced extensions utilizing the SkEditor API |
| '/Themes' | Custom UI skins and color schemes |
| '/Syntax Highlighting' | Custom language definitions |
| '/Analyzer' | Mock Skript Built-in Executer  |

---

## 🚀 Featured Extensions


| | Name | Description |
|---|---------|---------------|
| 🔍 | **SkAnalyzer** | The official addon for offline script analysis and optimization |
| 🎨 | **VSC-Skript** | Visual Studio Code syntax highlights for Skript ([Larry6942021](https://larry6942021.github.io/portfolio)) |
| 📝 | **VSC-YAML** | Syntax highlighting for YAML files based off Visual Studio Code |

---

## 🔬 How to Contribute

We value all community contributions! Follow these steps to list your project:

1. **Prepare your files:** Ensure your addon '.dll' or theme '.xaml' is tested against the latest [SkEditor Release](https://github.com/releases).
2. **Include Metadata:** Every submission should include a 'manifest.json' (or equivalent) with your name, version, and a short description.
3. **Open a PR:** Follow the [Contribution Guidelines](https://github.com/blob/master/CONTRIBUTING.md) to submit your work for review.

**Ready to showcase your work?**
Submit your project to the [Marketplace Repo](https://github.com) or join our [Discord Community](https://discord.gg/cZJx64Mg6F) for help.
Use code with caution.


## 📖 Documentation


| Document | Description |
|----------|-------------|
| [Getting Started](https://skeditor.com) | Installation, initial configuration, and first script setup |
| [Plugin API](https://skeditor.com) | Documentation for creating custom SkEditor extensions in C# |
| [Theme Guide](https://skeditor.com) | How to create and share custom UI skins |
| [Keybindings](https://skeditor.com) | Master the editor with professional keyboard shortcuts |

---

<img src="https://camo.githubusercontent.com/8648be7df33245e7c5c1b977c7dad271acc60920f9febf83069ec06a62c0d4bc/68747470733a2f2f6e6f74726f2e6d652f7265736f75726365732f736b656469746f722f77696e646f77322e706e67" alt="SkEditor Interface Preview" width="800">
<br>
<em>Modern UI with advanced Skript syntax highlighting and file explorer</em>

## 🚀 Key Features

### The Editor

Code with precision using tools built specifically for the Skript language.


| | Feature | What It Means |
|---|---------|---------------|
| ⚡ | **Live Completion** | Real-time suggestions for effects, expressions, and local variables |
| 📂 | **File Explorer** | Manage your entire 'scripts/' folder with a native, high-speed sidebar |
| 🎨 | **Advanced Highlighting** | Distinct colors for variables, options, and functions |
| 🛠️ | **Code Snippets** | Save and trigger common code patterns (loops, GUIs) with a few keystrokes |

### Connectivity & Cloud

Stay synced with your server without ever leaving the editor.


| | Feature | What It Means |
|---|---------|---------------|
| ☁️ | **SFTP / FTP** | Edit scripts directly on your VPS or shared host with auto-save upload |
| 📤 | **Pastebin Support** | Share code snippets instantly via integrated paste services |
| 🛡️ | **Session Restore** | SkEditor restores all tabs and cursor positions on restart |

---

## 🔬 How It Works

SkEditor bridges the gap between a simple text editor and a heavy IDE by focusing specifically on the AST (Abstract Syntax Tree) of Skript:

```text
User Input → Tokenizer (Custom Regex) → Contextual Highlighting
    ↓
Language Server → Analyzes Addons/Documentation → IntelliSense Suggestions
    ↓
SFTP Link → Encrypted SSH Tunnel → Remote File System
    ↓
UI Layer → Avalonia Framework → Modern, fast rendering
```

**Ready to upgrade your Skripting experience?** 
Download the latest version from the [Spigot Page](https://www.spigotmc.org/resources/skeditor.108251/) or [GitHub Releases](https://github.com).
