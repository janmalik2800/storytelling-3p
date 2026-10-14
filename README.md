# storytelling-3p

A Claude skill that makes AI write short-form scripts with a real story in them instead of generic AI slop.

It turns one moment into a reel, carousel or caption in five steps: dig from the safe version of an idea to the raw one with three whys, give it a problem, pursuit, payoff arc, place that arc into a proven format, make the on-screen text carry the story, and time the turn of the story to the turn of the music. It ends with a checklist the script has to pass before it ships.

The method comes from my notes on Jun Yuh's free masterclass [How To Become a Master Storyteller](https://www.youtube.com/watch?v=XS-E6rnCr5U). I went through the full transcript, his slides and his example reels frame by frame, and wrote it down so an AI agent can follow it. These are unofficial notes, not affiliated with or endorsed by Jun Yuh or Creator College. Watch the original, it is worth it.

## What is inside

- `storytelling-3p/SKILL.md` is the method Claude follows.
- `storytelling-3p/references/masterclass-notes.md` has the longer notes with timestamps and every example from the masterclass.

## Install

**Claude Code**

```bash
git clone https://github.com/janmalik2800/storytelling-3p.git
cp -r storytelling-3p/storytelling-3p ~/.claude/skills/
```

On Windows copy the inner `storytelling-3p` folder to `C:\Users\<you>\.claude\skills\`.

**Claude.ai**

Zip the inner `storytelling-3p` folder and upload it in Settings, Capabilities, Skills.

## Use

Ask Claude for a reel script, a carousel or a caption, or paste a draft and say it feels flat. The skill triggers on its own. You can also call it by name: use storytelling-3p to rewrite this script.

## License

MIT for the skill files. The ideas belong to Jun Yuh; credit him when you use them.
