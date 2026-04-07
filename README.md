# Writing Skills

Four writing and content skills for Claude Code, Cursor, Codex, and OpenCode.

| Skill | What it does |
|-------|-------------|
| `article-content` | Write article body content, blog posts, long-form guides |
| `article-structure` | Structure any article: title, intro, body, conclusion |
| `writing-style-personal-voice` | Apply a plain, clear personal writing voice |
| `brainstorm` | Brainstorm ideas and angles using research and synthesis |

---

## Install

### Claude Code

```
Fetch and follow instructions from https://raw.githubusercontent.com/Lauvanya28/ArticleClaudeSkills/master/.claude-plugin/INSTALL.md
```

### Codex

```
Fetch and follow instructions from https://raw.githubusercontent.com/Lauvanya28/ArticleClaudeSkills/master/.codex/INSTALL.md
```

### OpenCode

```
Fetch and follow instructions from https://raw.githubusercontent.com/Lauvanya28/ArticleClaudeSkills/master/.opencode/INSTALL.md
```

### Cursor

Copy the files from `.cursor/rules/` into your project's `.cursor/rules/` folder,
or into `~/.cursor/rules/` for global use.

```bash
# Mac/Linux — global
cp -r .cursor/rules/* ~/.cursor/rules/

# Windows PowerShell — global
Copy-Item .cursor\rules\* "$env:USERPROFILE\.cursor\rules\" -Force
```

---

## Update

Re-run the same install command. It will overwrite the existing files with the latest versions.
