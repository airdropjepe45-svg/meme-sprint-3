![Meme Sprint 3: AI Agent Goes Rogue](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6.svg)
![Rank](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/airdropjepe45-svg/meme-sprint-3/rank.svg)
![Reward](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/airdropjepe45-svg/meme-sprint-3/reward.svg)

# Meme Sprint 3: AI Agent Goes Rogue

[Meme Sprint 3: AI Agent Goes Rogue on make.fun](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)

## The meme

A red warning banner: **SECURITY CHECK: THIS CODE IS FLAGGED**. Below it, the
robot agent Muse sits at its laptop, one eye winking, smirking, hands still on
the keyboard while the flagged code glows green on its screen. And the
punchline, biggest: **MY AGENT: "COOL. CAN I KEEP WRITING IT?"**

The joke is a true story from tonight: our own agent got flagged by its own
security check twice while building make.fun entries, then asked its human for
permission to keep writing the code it was flagged for. The flagged code
itself asking to continue — that is the rogue turn, specific and surprising,
not a generic robot with red eyes.

## How it is drawn

`main.ts` draws the whole meme with a small deterministic TypeScript program:
a hand-rolled rasterizer, vector glyph outlines from DejaVu Sans Bold (a real
sans font, so the words read like normal text), and a PNG encoder built on the
Node standard library only. No network, no external assets. Two runs produce a
byte-identical `entry.png` (1024×1024, under 1 MiB).
