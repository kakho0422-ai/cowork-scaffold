# cowork-scaffold

A collaborative AI workflow — where code, design, and reasoning are all versioned together.

## The Idea

This repo is both the **sample project** and the **workflow itself**. The act of setting it up is what we're building.

The players:
- **Ken** — the director, decides what gets built and when
- **Chloe (Claude)** — builds files, writes reasoning, edits in Cowork2
- **ChatGPT** — reads the repo, picks up context from reasoning logs

## Folder Structure

```
cowork-scaffold/
├── README.md              ← you are here
├── reasoning/             ← decision logs (the "why" behind every change)
│   └── 2026-02-23.md     ← first entry: why we built this
├── states/                ← living snapshots of each player
│   ├── ken.md            ← Ken's current knowledge, preferences, tools
│   └── chloe.md          ← Chloe's capabilities, limitations, gaps
├── figma/                 ← links and notes to Figma designs
│   └── links.md
├── docs/                  ← guides for using this workflow
│   └── how-to-collaborate.md
└── .gitignore
```

## How It Works

1. Ken asks Chloe to make changes
2. Chloe edits files directly in Cowork2
3. Ken runs `git add . && git commit -m "message" && git push` from Terminal
4. GitHub is updated — visible to ChatGPT or any other AI

## For ChatGPT (or any external AI)

To get full context on this project, read these files in order:
1. `README.md` — this file
2. `states/` — who the players are, what they know, what they can do
3. `reasoning/` — all decision logs, newest first
4. `docs/how-to-collaborate.md` — how to contribute

---
*Built with Claude (Chloe) via Cowork on 2026-02-23*
