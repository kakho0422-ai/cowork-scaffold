# How to Collaborate on This Project

This document is for any AI (or human) joining this project mid-stream.

## For AI assistants (ChatGPT, Claude, etc.)

### Getting context fast
1. Read `README.md` for the overview
2. Read `reasoning/` files newest-first to understand current decisions
3. Read this file to understand how to contribute

### How to suggest changes
- Describe your suggestion clearly in plain language
- Reference the specific file and section
- Explain *why* — not just *what*

### What not to do
- Don't make changes without explaining reasoning
- Don't ignore existing decisions in the reasoning logs
- Always add a reasoning entry when making significant changes

## For Ken (the human director)

### Your workflow
1. Ask Chloe (Claude in Cowork) to make changes
2. Review the files in Cowork2
3. Push to GitHub:
```bash
git add .
git commit -m "brief description of what changed"
git push
```

### When to add a reasoning entry
- Big decisions (changing tools, architecture)
- When you want ChatGPT or another AI to understand *why* something was done
- At the start of any new work session

## The collaboration protocol

| Role | Tool | Access |
|------|------|--------|
| Ken | Cowork + Terminal | Read + Write + Push |
| Chloe (Claude) | Cowork | Read + Write to Cowork2 |
| ChatGPT | GitHub (public repo) | Read only |
| Future AIs | GitHub (public repo) | Read only |
