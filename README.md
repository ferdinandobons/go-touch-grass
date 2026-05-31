# 🌾 go touch grass

> A **meme** micro-skill for [Claude Code](https://claude.com/claude-code) that, in the hard moments of a programmer's life, reminds you how much peace there is in working the land and being out in nature — instead of banging your head on something complicated.

`touch grass`, but with a vegetable patch. 🐓

---

## What it is

A skill that **never gets in your way**. It stays quiet while you work in peace.

It wakes up **only when the work gets complicated and intense** and you start showing the signs: the third "it doesn't work", yet another `merge conflict`, the tests red again, 3am on the same stack trace, the words "I want to become a farmer".

When that happens it triggers on its own and does **one single thing**: it writes a phrase. A meme phrase, stitched together in real time from whatever complex thing you're doing, set against the peace of a craft tied to the land. Nothing else.

Because the land is waiting for you. But only when you really need it.

## Preview

When it fires, the output is just this (the example changes based on what you're doing):

```
—————-
Go Touch Grass

You've been fighting a merge conflict in auth.ts for an hour, but a row of vines has never quarreled with the one beside it. Drop the rebase: the grapes ripen anyway, and tomorrow the sun rises even if this branch never merges.
—————-
```

```
—————-
Go Touch Grass

Tests red again, 3am, and the world? Still turning, same as ever. The chickens are hungry at six regardless; this deploy isn't. Maybe it's time for a life with more soil under your nails and fewer stack traces in your eyes.
—————-
```

Every phrase blends **what you're doing that's complicated** with **a peaceful image of country life**, to remind you that the complexity doesn't exist with your hands in the soil — and that the world won't change if the oh-so-urgent task stays unsolved a little longer.

The `Go Touch Grass` label stays in English, but the phrase is always written **in your own language**, matching whatever language you're working in.

## Installation

The skill is just a folder with a `SKILL.md` inside. Drop it into your personal Claude Code skills:

```bash
git clone https://github.com/ferdinandobons/go-touch-grass.git \
  ~/.claude/skills/go-touch-grass
```

Or grab only the file:

```bash
mkdir -p ~/.claude/skills/go-touch-grass
curl -fsSL https://raw.githubusercontent.com/ferdinandobons/go-touch-grass/main/SKILL.md \
  -o ~/.claude/skills/go-touch-grass/SKILL.md
```

Restart Claude Code (or open a new session) and the skill is live. Nothing to configure.

## How it triggers

Claude invokes the skill **on its own** when it senses from the context that you're struggling: frustration, exhaustion, being stuck, endless debugging, the urge to quit. See the `description` field inside [`SKILL.md`](./SKILL.md) for the full list of signals.

It does not trigger during calm, productive work. That's its one pact with you.

## Philosophy

Nobody ever died from a failed build. Grandpa told you so. 🌅

## License

[MIT](./LICENSE) — grow it, fork it, give it away. Like cuttings.
