# ChalkMD-ish

A lightweight, web-based Markdown notes viewer and editor.

I like taking my notes in Obsidian, but running Obsidian on a Chromebook can be a hassle—whether dealing with the Linux container or the Android app. 
Designed as a simple PWA alternative for browsing and lightly editing an Obsidian-style vault from any browser.

### Why "Chalk"?

Obsidian is dense, sharp, and permanent. 
Chalk is basic, imperfect, a bit brittle… but still gets the job done when you want to write something down quickly.

### Usage

You can use the live PWA directly from your browser:
[ChalkMD-ish](https://saturnsgithubsaga.github.io/ChalkMD-ish/chalkmdish.html)

Click "Open Vault Folder" and grant access to a local folder — that folder (and its subfolders) becomes your vault. ChalkMD-ish remembers the last folder you opened and reopens it automatically next time.

### Features

- Syntax-highlighted Markdown editing (CodeMirror), not a rendered HTML preview
- Installable as a Progressive Web App (PWA)
- No accounts, no built-in sync, no bloat—just open a local folder
- Automatically reopens your last folder upon restart
- Dotfiles and dot-folders (`.git`, `.obsidian`, etc.) stay hidden from the sidebar
- Create and delete notes and folders directly from the sidebar, targeted at whichever folder you last clicked (the vault root itself can be selected too)
- Autosaves as you type, with a save status indicator and a manual Save button
- The file list never refreshes on its own (so an editor change can't get overwritten out from under you) — use the Refresh button to save and pick up files added outside the app

### Status

Early personal tool.

### Planned Features

- Offline functionality — the app currently loads CodeMirror from a CDN, so it needs a network connection even when installed as a PWA. Running fully offline after install is the next step.

---

Open-source under the GPL-3.0 license. Feel free to fork or adapt.
