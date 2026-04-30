# coScene Skills

Agent Skills for [coScene](https://coscene.io/) — robotics data platform automation via Claude Code, Cursor, and other [Agent Skills](https://github.com/anthropics/skills)–compatible runtimes.

## Install

Copy-paste this prompt into Claude Code:

```
Clone https://github.com/coscene-io/skills to ~/coscene-skills (skip if already exists), then symlink each skill directory under skills/ into ~/.claude/skills/ so they're available as slash commands. Verify by listing ~/.claude/skills/cos and ~/.claude/skills/coscene-docs.
```

Or manually:

```bash
git clone https://github.com/coscene-io/skills.git ~/coscene-skills
mkdir -p ~/.claude/skills
ln -sf ~/coscene-skills/skills/cos ~/.claude/skills/cos
ln -sf ~/coscene-skills/skills/coscene-docs ~/.claude/skills/coscene-docs
```

## Skills

- **`cos`** — CLI interface to the coScene platform via [`cocli`](https://github.com/coscene-io/coCLI). Upload, query, process, move.
- **`coscene-docs`** — Platform concepts, automation model, and troubleshooting grounded in official docs.

## License

Apache 2.0 — see [`LICENSE`](./LICENSE).
