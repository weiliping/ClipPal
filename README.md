# ClipPal

**ClipPal** is a lightweight, privacy-focused clipboard history manager for macOS. It helps you keep track of your recent copied items (like text, code snippets) without getting in your way.

**ClipPal** 是一款轻量、注重隐私的 macOS 剪贴板历史管理工具。它能帮你记录最近复制的文本、代码片段等内容，且不占用系统资源。

---

## ✨ Features / 功能特性

- **LRU History**: Keeps up to your configured limit (default: 35 items). Recently used items are moved to the top.
  最近使用优先（LRU）：默认保留 35 条历史，粘贴后自动置顶，超出限制自动淘汰最旧记录。
- **Global Hotkey**: Press `⌘ + ⇧ + V` anywhere to open the history panel.
  全局快捷键：在任何应用内按 `⌘ + ⇧ + V` 呼出历史面板。
- **Auto Paste**: Select an item and press `Enter` to paste it directly into your active app.
  自动粘贴：选中记录后按回车，自动模拟 `⌘V` 粘贴到当前应用。
- **Menu Bar App**: No Dock icon. It sits quietly in your menu bar.
  菜单栏常驻：无 Dock 图标，安静地待在顶部菜单栏。
- **Clean UI**: A modern, frosted-glass panel.
  清爽界面：现代化的毛玻璃半透明面板。

---

## 📦 Installation / 安装说明

⚠️ **Important:** Because ClipPal is not notarized by Apple yet, macOS will block it on first launch. You need to follow a few extra steps to install and grant permissions.

⚠️ **重要提示：** 由于 ClipPal 目前尚未通过 Apple 公证，macOS 会在首次启动时拦截。你需要按照几个额外步骤来完成安装和权限授权。

👉 **Please read the detailed installation guide here: [INSTALL.md](./INSTALL.md)**  
👉 **请点击此处阅读详细的安装指南：[INSTALL.md](./INSTALL.md)**

*(If you put the install file in a different path, replace `./INSTALL.md` with your actual file name or path.)*

---

## 🚀 Usage / 使用方式

| Action / 操作 | Result / 结果 |
| :--- | :--- |
| Copy any text / 复制任意文本 | Automatically saved to history (LRU). / 自动保存至历史记录（LRU）。 |
| Press `⌘ + ⇧ + V` | Show the history panel. / 弹出历史列表面板。 |
| Press `↑` / `↓` | Navigate the list. / 上下选择记录。 |
| Press `Enter` or Double-click | Paste the selected item and move it to the top. / 粘贴选中内容，并将其置顶。 |
| Press `Esc` or Click outside | Hide the panel. / 关闭面板。 |
| Right-click the menu bar icon | Clear history or change max items. / 右键菜单栏图标：清空历史或修改最大条数。 |

---

## 🛠️ Built With / 技术栈

- Swift & AppKit
- Pure native macOS, no external dependencies. / 纯原生 macOS 开发，无第三方依赖。

## 📄 License / 开源协议

MIT License
