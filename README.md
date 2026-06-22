# joye-skills

Agent skills by **Joye Huang** — [joyehuang.me](https://joyehuang.me) · [@joyehuang](https://github.com/joyehuang)

A small collection of [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) I use in my own work and decided to share. Same taste as my site: dark, calm, terminal-flavored.

---

## Skills

### `terminal-slide-deck`

Build a self-contained, single-file HTML slide deck in a distinctive **cyan-on-near-black terminal aesthetic** — monospace eyebrows, a blinking cursor, hairline borders, and bespoke HTML/SVG data-viz components (timelines, concentric rings, bar charts, hub-and-spoke and loop diagrams, streaming chat cards, comparison paths, pipelines). Keyboard/touch navigation, fullscreen, reduced-motion fallback. CJK fonts bundled.

The output is always **one HTML file** — no build step, opens in any browser. You bring the content; the skill brings the look. It's the same visual language as [joyehuang.me](https://joyehuang.me).

→ [`skills/terminal-slide-deck`](skills/terminal-slide-deck)

---

## Install

These skills install with the [`skill`](https://www.npmjs.com/package/skill) CLI. Point it at this repo via `SKILL_BASE_URL`:

```bash
SKILL_BASE_URL=https://github.com/joyehuang/joye-skills/tree/main \
  npx skill skills/terminal-slide-deck
```

That downloads the skill into `.codebuddy/skills/terminal-slide-deck`.

### Using with Claude Code

To use as a [Claude Code skill](https://docs.claude.com/en/docs/claude-code/skills), drop the folder into your skills directory instead:

```bash
# project-level
git clone https://github.com/joyehuang/joye-skills /tmp/joye-skills
cp -R /tmp/joye-skills/skills/terminal-slide-deck .claude/skills/

# or user-level (available in every project)
cp -R /tmp/joye-skills/skills/terminal-slide-deck ~/.claude/skills/
```

Then ask Claude for "slides in the terminal style" and the skill triggers.

---

## License

MIT — free to use and adapt. A link back to [joyehuang.me](https://joyehuang.me) is appreciated but not required.

Made by [Joye Huang](https://joyehuang.me) · AI Agent & Full-Stack Developer, Melbourne 🇦🇺
