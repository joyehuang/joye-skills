# joye-skills

Agent skills by **Joye Huang** — [joyehuang.me](https://joyehuang.me) · [@joyehuang](https://github.com/joyehuang)

A small collection of [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) I use in my own work and decided to share. Same taste as my site: dark, calm, terminal-flavored.

---

## Skills

### `terminal-slide-deck`

Build a self-contained, single-file HTML slide deck in a distinctive **cyan-on-near-black terminal aesthetic** — monospace eyebrows, a blinking cursor, hairline borders, and bespoke HTML/SVG data-viz components (timelines, concentric rings, bar charts, hub-and-spoke and loop diagrams, streaming chat cards, comparison paths, pipelines). Keyboard/touch navigation, fullscreen, reduced-motion fallback. CJK fonts bundled.

The output is always **one HTML file** — no build step, opens in any browser. You bring the content; the skill brings the look. It's the same visual language as [joyehuang.me](https://joyehuang.me).

→ [View rendered demo](https://joyehuang.github.io/joye-skills/skills/terminal-slide-deck/references/demo-reference.html) · [`skills/terminal-slide-deck`](skills/terminal-slide-deck) · [demo source](skills/terminal-slide-deck/references/demo-reference.html)

---

## Install

Install with the [`skills`](https://skills.sh) CLI ([skills.sh](https://skills.sh)) — it auto-detects your agent (Claude Code, Cursor, Codex, …) and copies the skill in:

```bash
# install all skills in this repo
npx skills add joyehuang/joye-skills

# or just one, into Claude Code
npx skills add joyehuang/joye-skills --skill terminal-slide-deck -a claude-code
```

Handy variants:

```bash
npx skills add joyehuang/joye-skills --list      # see what's in the repo
npx skills add joyehuang/joye-skills -g          # install globally (every project)
npx skills use joyehuang/joye-skills@terminal-slide-deck | claude   # use once, no install
```

The skill lands in `.claude/skills/terminal-slide-deck` (or `~/.claude/skills/` with `-g`). Then ask your agent for "slides in the terminal style" and it triggers.

> Installing via the `skills` CLI is also how this repo gets ranked on [skills.sh](https://skills.sh) — so `npx skills add` is the preferred path. ⭐ the repo if it's useful.

---

## License

MIT — free to use and adapt. A link back to [joyehuang.me](https://joyehuang.me) is appreciated but not required.

Made by [Joye Huang](https://joyehuang.me) · AI Agent & Full-Stack Developer, Melbourne 🇦🇺
