# VS Code keyboard

## Setting almost everywhere:
```
Command + ,
```

## Command Palette 
```
Press Cmd + Shift + P
```
1. Keyboard Shortcut (Windows/Linux): Press Ctrl+Shift+P.
2. Keyboard Shortcut (macOS): Press Cmd+Shift+P.
3. Alternative Shortcut: Press the F1 key.
4. Menu: Select View > Command Palette from the application menu. 

## Key Uses and Features

Once open, you can start typing to filter the list of available commands. Here are some common uses and tips: 

* `Run Commands:` Start typing the name of an action (e.g., "install extension", "change color theme") to find and execute it. 
* `Navigate Files` (Quick Open): Remove the  symbol and start typing a file name to quickly search for and open files in your workspace. You can also use  (or  on macOS) to go directly to this mode. 
* `Navigate to a Line:` Type a colon () followed by a line number to jump to a specific line in the current file (e.g., ). 
* `Navigate Symbols:` Type the  symbol to navigate to a specific symbol (function, variable, etc.) within the current file (e.g., ). 
* `View Open Editors/Terminals:` Type  (with a space) to list all open editors or  to list open terminals, allowing quick switching between them. 
* `Discover Shortcuts:` The Command Palette displays the default keyboard shortcut next to each command, helping you learn them for future use. 
* `Customize:` You can use the Command Palette to open the Keyboard Shortcuts editor () to view, change, or add your own keybindings for commands.

Here are the **default keyboard shortcuts for using **GitHub Copilot** in **Visual Studio Code** on **macOS** — focused on accepting, navigating, and triggering AI suggestions:

### 🧠 Copilot Inline Suggestions (Code Completions)

| Action                                 | Shortcut (macOS)                      |
| -------------------------------------- | ------------------------------------- |
| **Accept inline suggestion**           | `Tab` ([GitHub Docs][1])              |
| **Dismiss inline suggestion**          | `Esc` ([GitHub Docs][1])              |
| **Show next suggestion**               | `Option (⌥)` + `]` ([GitHub Docs][1]) |
| **Show previous suggestion**           | `Option (⌥)` + `[` ([GitHub Docs][1]) |
| **Trigger inline suggestion manually** | `Option (⌥)` + `\` ([GitHub Docs][1]) |

### 📋 Copilot Completions Panel

| Action                                            | Shortcut (macOS)               |
| ------------------------------------------------- | ------------------------------ |
| **Open Completions Panel (multiple suggestions)** | `Ctrl` + `Enter` ([GitHub][2]) |

### 💬 Copilot Chat (if Copilot Chat extension is installed)

| Action                        | Shortcut (macOS, common defaults)                   |                                                   |
| ----------------------------- | --------------------------------------------------- | ------------------------------------------------- |
| **Open inline Copilot Chat**  | `Cmd` + `I` ([github-insight-anz-lab.github.io][3]) |                                                   |
| **Open Chat view in sidebar** | `Cmd` + `Ctrl` + `I` (or similar                    | may vary) ([github-insight-anz-lab.github.io][3]) |

### 🛠 Notes & Tips

* These are the **default key bindings** — you can customize any of them in **VS Code > Preferences > Keyboard Shortcuts** (`Cmd` + `K` then `Cmd` + `S`). ([GitHub][2])
* Copilot’s inline suggestions integrate with VS Code’s suggestion system, so some keys (like `Tab`) accept suggestions just like native IntelliSense. ([GitHub Docs][1])
* Some shortcuts (like Chat panel focus) depend on whether **GitHub Copilot Chat** is installed and enabled. ([iifx.dev][4])

If you want, I can also show how to **customize these shortcuts** or bind additional Copilot features for even smoother workflow!

[1]: https://docs.github.com/en/enterprise-cloud%40latest/copilot/reference/keyboard-shortcuts-for-github-copilot-in-the-ide?utm_source=chatgpt.com "Keyboard shortcuts for GitHub Copilot in the IDE - GitHub Enterprise Cloud Docs"
[2]: https://github.com/orgs/community/discussions/162320?utm_source=chatgpt.com "How to get Github Copilot Suggestions window in VsCode · community · Discussion #162320 · GitHub"
[3]: https://github-insight-anz-lab.github.io/github-copilot-labs-list/keyboard-shortcuts/?utm_source=chatgpt.com "Github Copilot Keyboard Shortcuts | GitHub Copilot Labs"
[4]: https://iifx.dev/en/articles/451116147?utm_source=chatgpt.com "visual studio code - VS Code & Copilot Chat: Your Guide to Keyboard Shortcuts & Workflow - github copilot"
