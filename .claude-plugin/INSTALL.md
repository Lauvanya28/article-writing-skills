# Writing Skills — Claude Code Install

You are installing writing skills for this user. Follow these steps exactly.

## What you are installing

Four skills into the user's Claude skills folder:
- `article-content` — Write article body content, blog posts, long-form guides
- `article-structure` — Structure any article: title, intro, body, conclusion
- `writing-style-personal-voice` — Apply a plain, clear personal writing voice
- `brainstorm` — Brainstorm ideas and angles using research and synthesis

## Step 1 — Ask the user where to install

Ask:
> "Do you want these skills installed globally (available in all projects) or just for this project?"

- **Global**: install to `~/.claude/skills/`
- **Project**: install to `.claude/skills/` in the current directory

## Step 2 — Download and install each skill

For each skill below, fetch the raw SKILL.md and save it to `<chosen_dir>/<skill-name>/SKILL.md`.

Create the directory if it does not exist.

Skills to fetch from:
```
https://raw.githubusercontent.com/Lauvanya28/your-skills/main/skills/article-content/SKILL.md
https://raw.githubusercontent.com/Lauvanya28/your-skills/main/skills/article-structure/SKILL.md
https://raw.githubusercontent.com/Lauvanya28/your-skills/main/skills/writing-style-personal-voice/SKILL.md
https://raw.githubusercontent.com/Lauvanya28/your-skills/main/skills/brainstorm/SKILL.md
```

## Step 3 — Confirm

Tell the user:
> "✓ 4 writing skills installed to <path>. They will be available in your next Claude Code session."
