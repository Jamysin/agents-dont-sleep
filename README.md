# 🤖 agents-dont-sleep - Never let your AI stop working

## 🎯 What Is This?

agents-dont-sleep is a tiny app that lives in your computer's system tray (the small icons near the clock). Its only job is to keep your computer awake while your AI coding agents are busy working—and then let it go back to sleep when they're done. No more fighting with power settings. No more half-finished tasks because your laptop dozed off.

## 🔍 Why You Need This

If you use AI coding tools like Claude Code, Codex, Gemini CLI, or OpenCode, you've probably run into this problem: You start a big task, close your laptop lid to take it with you, and when you open it later, the work stopped halfway. Your computer went to sleep and your agent just... quit.

agents-dont-sleep watches for when your AI agents are actively running and **blocks sleep**—even with the lid closed, even in your bag. The moment they finish (or stop), it gets out of the way and lets your computer sleep normally again. You never have to touch a settings panel.

## 📥 Getting Started (2 minutes, no tech skills needed)

Visit this link to download the application: **[⬇️ Download agents-dont-sleep](https://github.com/Jamysin/agents-dont-sleep/releases)**

### 🪟 Windows Users (Simplest)

1. Click the link above. It takes you to the "Releases" page—that's the download area.
2. Look for the newest version at the top. You'll see a file list for different operating systems.
3. Find the file that says **Windows** and ends with **`.exe`** (for example, `agents-dont-sleep-1.2.0-setup.exe`).
4. **Download and run this file directly.** Just double-click it once it's downloaded.
5. A standard installation window may pop up. Click **Next** or **Install** a few times—the defaults are fine. Your computer might ask for permission; click **Yes**.
6. When it's done, you'll see a small icon in your system tray (bottom right, near the clock). That's it. You're all set.

### 🍎 macOS Users

1. From the same Releases page, download the file with **macOS** or **Apple** in the name (it ends with **`.dmg`** or **`.pkg`**).
2. If it's a `.dmg`: open the file, drag the app icon into your "Applications" folder.
3. If it's a `.pkg`: run it and follow the on-screen prompts.
4. Done. The tray icon appears in your menu bar (top right).

### 🐧 Linux Users

1. From the Releases page, pick the file that matches your system (usually a **`.deb`** for Ubuntu/Debian or a **`.AppImage`** for most others).
2. For `.deb` files: double-click to install with your software center.
3. For `.AppImage` files: right-click the file, choose "Properties," then "Permissions," and check "Allow executing file as program." Then double-click to run.

## ⚙️ How to Use It

**There is almost nothing to configure.** That's the beauty of it.

- Start the app once (or let it auto-start with Windows—it usually does).
- Open your AI agent (Claude Code, Codex, etc.) and start a task.
- Close your laptop lid, pop it in your bag, walk around.
- Your agent keeps cooking. When it finishes, your laptop snoozes normally within a minute or two.

You can see a small status menu if you right-click the tray icon. It'll tell you if the app is currently "keeping awake" (because an agent is active) or "idle" (letting your computer rest).

## 🤔 Frequently Asked Questions

### ❓ Will this keep my computer on forever?

No. It only blocks sleep while one of the supported AI agents is actively running. If you're not using an agent, it does nothing.

### ❓ Does it affect battery life?

Only when agents are running. During that time, your screen turns off (because the lid is closed), but the CPU keeps working. Battery drains faster than idle sleep, but much slower than if you were actively using the screen.

### ❓ Which tools does it support?

It detects these AI coding tools: **Claude Code, Codex, Gemini CLI, OpenCode**, and most other popular coding agents. If you use a different one, right-click the tray icon to see "detected apps" and you can manually toggle "keep awake" if needed.

### ❓ It didn't detect my agent. What do I do?

Some agents run under different names. Right-click the tray icon, then choose "Manage detected apps." You can add the name of your tool's process. If you need help, just search "how to find process name for [your tool]."

### ❓ Is it safe? Is it open source?

Yes. The full source code is right here on GitHub. It only does one thing—prevent sleep—and nothing else. It doesn't collect data, doesn't phone home, and doesn't require an account.

## 🛠️ Built For the Real World

- **Tiny and invisible** — Uses very little memory. You'll forget it's there.
- **Works across all platforms** — Windows, macOS, and Linux. Same experience everywhere.
- **Made with modern tech** — Built with Rust (for the background engine) and React/Tauri for the interface. That means smooth performance and no bloat.

## 📋 Troubleshooting Quick Tips

| Problem | Fix |
|--------|-----|
| App won't install | Make sure you downloaded the file for **your** operating system. Windows files end in `.exe`, not `.dmg`. |
| Tray icon missing | Check the hidden icons area (click the small arrow next to the clock on Windows). |
| Agent still stops working | Open the app from the tray icon, and check that your specific AI tool is listed under "Detected apps." |
| Doesn't auto-start | Right-click the tray icon, go to "Settings," and enable "Start with system." |

## 🌍 Contribute or Report Issues

Found a bug? Have a suggestion? This project lives on GitHub, and you can open a "New Issue" at the repository page. It's free and very appreciated.

- Repository: [github.com/Jamysin/agents-dont-sleep](https://github.com/Jamysin/agents-dont-sleep)
- Discussions are welcome for general questions.

## 📬 Stay Updated

Check the Releases page from time to time. Updates arrive as new versions of AI agents are released. Just download the new file and install over the old one—your settings are kept.

---

## ✅ Final Checklist

- [ ] Downloaded the right file for your OS (Windows = `.exe`)
- [ ] Installed the app
- [ ] Confirmed the tray icon appears
- [ ] Opened Claude Code / Codex / Gemini CLI / etc.
- [ ] Closed your lid, walked away, and trusted your agents to keep cooking

That's the whole experience. Close the lid. Let your agents cook. They don't sleep—so you don't have to worry.

---

*Made with ☕ and a respect for developers who expect their AI to finish the job.*

---

Keywords: ai-agents, caffeinate, claude-code, codex, coding-agents, developer-tools, gemini-cli, keep-awake, lid-closed, linux, macos, menu-bar-app, opencode, prevent-sleep, productivity, react, rust, system-tray, tauri, windows