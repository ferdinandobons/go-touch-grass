# 🌾 go touch grass

> A meme micro-skill for [Claude Code](https://claude.com/claude-code). When you're deep in a fight with some over-engineered mess, it drops one line reminding you that the land is waiting.

`touch grass`, but with a vegetable patch. 🐓

---

## What it does

It stays silent while you work in peace. It wakes up **only** when the work turns hard and intense and you start cracking — the third *"it doesn't work"*, yet another merge conflict, tests red at 3am.

Then it does exactly **one thing**: prints a single meme line, written live from whatever you're stuck on, set against the calm of working the soil. No advice, no ASCII art, no "back to work". Just this:

```
—————-
Go Touch Grass

You've been fighting a merge conflict in auth.ts for an hour, but a row of vines has never quarreled with the one beside it. Drop the rebase: the grapes ripen anyway, and the sun rises tomorrow even if this branch never merges.
—————-
```

Every line is different and tailored to your actual task — to remind you that the complexity vanishes with your hands in the dirt, and the world won't end if the urgent ticket waits a little longer. The `Go Touch Grass` label stays in English; the line is written **in your language**.

## Install

A skill is just a folder with a `SKILL.md`. Drop it in an official skills location — no install command, no config.

```bash
# Personal — available in every project
git clone https://github.com/ferdinandobons/go-touch-grass.git ~/.claude/skills/go-touch-grass

# or Project — shareable with your team (run from the project root)
git clone https://github.com/ferdinandobons/go-touch-grass.git .claude/skills/go-touch-grass
```

Open a new session and run `/skills` — `go-touch-grass` should be in the list. That's it.

## License

[MIT](./LICENSE) — grow it, fork it, give it away. Like cuttings. 🌅
