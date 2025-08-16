# 💻 VS Code Config

My personal **Visual Studio Code** setup — focused on aesthetics, productivity, and a smooth coding experience.  
Using the **Vesper theme**, **Symbols icons**, and some tweaks for cursor + sidebar.  

---

## 📂 Files
- [`settings.json`](./settings.json) → contains my VS Code configuration  

---

## 🚀 Usage

1. Install [Visual Studio Code](https://code.visualstudio.com/)  
2. Copy [`settings.json`](./settings.json) to your VS Code config directory:  
   - **macOS** → `~/Library/Application Support/Code/User/settings.json`  
   - **Linux** → `~/.config/Code/User/settings.json`  
   - **Windows** → `%APPDATA%\Code\User/settings.json`  
3. Restart VS Code and enjoy 🎉

---

## ⚙️ Configuration Preview

```json
{
    "workbench.iconTheme": "symbols",
    "editor.cursorBlinking": "phase",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "editor.formatOnSave": true,
    "workbench.sideBar.location": "right",
    "editor.fontSize": 14,
    "workbench.colorTheme": "Vesper",
    "symbols.hidesExplorerArrows": false,
    "editor.minimap.enabled": true
}