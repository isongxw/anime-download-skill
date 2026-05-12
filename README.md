# anime-download-skill

Claude Code skill for searching and downloading anime torrents from miobt.com.

## Install

```bash
npx clawhub@latest install anime-download-skill
```

Or clone manually into `~/.claude/skills/`.

## Usage

Once loaded, ask Claude:

- "搜索 JOJO 的动漫资源"
- "帮我下载最新一集鬼灭之刃"
- "找找进击的巨人的种子"

The agent will auto-run:
```bash
uvx --from git+https://github.com/isongxw/anicatch.git anicatch --search "KEYWORD"
```

## Requirements

- [uv](https://docs.astral.sh/uv/) — auto-installs anicatch and all dependencies
- No Python/libtorrent pre-install needed

## Related

- [anicatch](https://github.com/isongxw/anicatch) — the underlying CLI tool
