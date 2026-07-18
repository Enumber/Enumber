### Hi, I'm Enum 👋

I use Linux as my daily desktop, and every time something annoyed me I ended up writing a small
tool to fix it. These are those tools. They're written for one person's real desktop first, then
cleaned up and opened in case they're useful to you too.

我把 Linux 当日常桌面用，用着用着总有些地方别扭，就顺手写个小工具补上。
下面这些就是那些工具 —— 先是自己天天在用，然后整理干净开源出来，希望对你也有用。

---

### 🧰 Tools / 小工具

| | What it does | 做什么 |
|---|---|---|
| **[悄语 vokey](https://github.com/Enumber/vokey)** | Hold a hotkey and talk — offline Chinese voice typing for Linux/X11. Text lands in whatever window your cursor is in. No cloud, no account. | 按住热键就能说话打字，完全离线的中文语音输入，光标在哪就打到哪 |
| **[掠页 flipscan](https://github.com/Enumber/flipscan)** | Point a document camera at a book, flip pages, and it captures each one automatically — then cleans them into readable scans. | 高拍仪对着书翻页就自动拍，拍完自动做扫描增强 |
| **[落桌 dropdesk](https://github.com/Enumber/dropdesk)** | Put any installed app back on your GNOME desktop — the feature GNOME removed. Shortcuts come pre-trusted, no "Allow Launching?" nag. | 一键把应用放到桌面，补回 GNOME 删掉的功能，还免掉「是否允许启动」的弹窗 |
| **[BeeBEEP (fork)](https://github.com/Enumber/BeeBEEP)** | A reskinned build of the serverless LAN messenger — chat and send files across your local network with no server and no internet. GPL-3, same as upstream. | 无服务器局域网聊天工具的改版，界面重做，协议不变；沿用上游 GPL-3 |

---

### A few things they have in common / 它们的共同点

- **Installs without sudo** — `bash install.sh` builds a local virtualenv and drops a launcher on your desktop and in your app menu. Nothing touches the system unless you ask it to.
- **Bilingual** — README and UI in both English and Chinese.
- **Works offline** — no accounts, no telemetry, nothing phones home.

- **不用 sudo** —— `bash install.sh` 就装好，桌面和应用菜单里各留一个图标，不动系统目录。
- **中英双语** —— README 和界面都是。
- **离线可用** —— 不用注册，不上传，不联网。

---

I'm not a professional developer — these were built to solve my own problems, so expect rough
edges. If something breaks on your machine, an issue with what you ran and what happened is
genuinely helpful, and I'll do my best to fix it.

我不是专业程序员，这些都是为了解决自己的问题写的，难免有粗糙的地方。
如果在你机器上跑不起来，欢迎开 issue 告诉我你怎么运行的、出了什么错，我会尽力修。
