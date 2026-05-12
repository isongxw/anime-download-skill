# anime-download-skill

Claude Code skill for searching and downloading anime torrents from miobt.com.

## Install

```bash
clawhub install anime-download-skill --dir ~/.claude/skills
```

Or clone manually:

```bash
git clone https://github.com/isongxw/anime-download-skill.git ~/.claude/skills/anime-download-skill
```

Then `/reload-plugins` in Claude Code.

## Usage

Once loaded, ask Claude:

- "搜索 JOJO 的动漫资源"
- "帮我下载最新一集鬼灭之刃"
- "看看这个季度有哪些新番"

The agent will auto-run the matching command from the skill.

## Requirements

- [uv](https://docs.astral.sh/uv/) — for `uvx` zero-install execution
- Or `pipx install anicatch` as fallback

## Related

- [anicatch](https://github.com/isongxw/anicatch) — the underlying CLI tool
- [anicatch on PyPI](https://pypi.org/project/anicatch/)
