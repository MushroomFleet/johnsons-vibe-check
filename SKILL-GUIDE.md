# Johnson's Vibe-Check — Skill Guide

A short, practical guide to what this skill does, when to reach for it, and how to get the most out of it. (For the underlying theory, see `references/Johnsons-Vibe-Check-grounding.md`. For the operating instructions Claude itself follows, see `SKILL.md`.)

---

## What it is, in one breath

Johnson's Vibe-Check reads the **audience a piece of work was secretly built for** — not the audience its makers *say* it's for — and tells you where that hidden audience-model is solid, where it cracks, and whether the work is likely to land, get rejected-then-loved, or quietly age out.

It works on finished media (a film, a show, a franchise) and on work you're still making (a lorebook, a chapter, a character concept). You can also just point it at something you're already discussing.

---

## The core idea (why it works)

Every story encodes a picture of its ideal reader — in what it bothers to explain, what it assumes you already know, what it tries to sell you, how fast it cuts, how brightly it signposts the good guys. Creators rarely state this picture out loud; often they aren't fully aware of it. But it's **baked into the choices**, and you can read it back out.

The skill calls this *reading the shadow instead of the glare*: the marketing and the interviews are bright light that hides the real shape; the choices in the work are the shadow that reveals it. It then runs a simple three-part sweep:

1. **Who were they speaking to?** (the reader the text talks to right now)
2. **Who do they think we are?** (the audience the work *assumes* is there)
3. **Who did they think we'd become?** (the bet it places on how readers will change)

**The interesting findings live in the gaps between those three answers.** A work that speaks to insiders but is built for a mass crowd, or one that bets readers will keep moving in a direction they've already turned away from, tells you exactly where and why it will struggle.

---

## Why you might want it

- **You're workshopping a lorebook or character and something feels off.** The skill tells you *who* the material is actually aimed at, and whether that reader exists — often the real problem isn't the writing, it's that it's cut for nobody, or for two incompatible people at once.
- **You're deciding how to target a project.** It distinguishes the two ways to aim — *engineering* an audience from trends (precise but prone to chasing a crowd that isn't there) versus *reflecting* your own cohort authentically (riskier-feeling, but the only path to something genuinely new). Knowing which bet you're making is half the battle.
- **You want to know if something will last.** It separates work built on durable, trans-historical foundations from work riding a moment that will expire with its cohort — and flags the early-warning signs of "aging out."
- **You're curious why a film flopped or got rehabilitated.** It gives you a structural answer ("the audience it forecast hadn't arrived yet" / "it aimed precisely at a crowd that didn't exist") instead of a vibe.
- **You're studying reception, fandom, or franchise strategy.** It's a repeatable, falsifiable lens you can apply case after case and refine.

---

## How to use it

**Invoke it** by saying any of:

- "Use johnsons-vibe-check on this lorebook."
- "Vibe-check chapter 7."
- "Who is this character actually for?"
- "Will this premise age well?"
- "Assess who they think the audience is for [film/show]."

You don't have to name the skill — phrasings about *who something is for*, *whether it'll land or endure*, or *why it was rejected* will reach for it too.

**Give it a subject** in any of three forms:

- **Upload a file** — a lorebook, chapter, script, or character bible. It reads the whole thing first.
- **Discuss something in chat** — name a film, show, or character, or paste an excerpt.
- **Point at the conversation** — if you've been talking about a subject, just say "vibe-check that."

If it's unclear *which* thing you mean, it'll ask one quick question; otherwise it dives in.

**What you get back:** a detailed report written to its own **semantically named markdown file** (e.g. `Eldoria-lorebook-vibe-check.md`), so you can keep it, share it, or drop it into your project. The report runs:

- an **intent gate** (what this was built to do; engineered-appeal vs. authentic-reflection),
- the **three-question sweep**,
- a reading of **where the model holds or breaks**,
- a **lock analysis** (is the intended audience real or imaginary; a growing edge or a dead end),
- any relevant **structural notes** (durability, aging-out, archetype vs. trend, and so on),
- a **falsifiable prediction** with stated confidence,
- an **honesty pass** on how much to trust the read, and
- for work-in-progress, **concrete recommendations** to tighten who it's aimed at.

---

## What makes a good run

- **Give it enough to read.** A full chapter or a fleshed-out lorebook yields a far sharper read than a one-line premise. The skill reads *choices*, so it needs choices to read.
- **Let it read blind.** It deliberately forms its read from the material *before* looking at reviews or sales, so its calls can actually be wrong (and therefore mean something). Don't pre-load it with "everyone loved this" if you want an honest diagnosis.
- **Use it to decide, not just to judge.** The most valuable output for a maker is the recommendations: close *this* gap, choose *this* targeting method on purpose, avoid aiming at a crowd that isn't there.

---

## What it won't do (by design)

- **It won't tell you whether a work's values are good or bad.** It questions *who the work assumes its reader is* — never whether that reader, or those values, are correct. This neutrality is deliberate: it's what keeps the read an instrument rather than a side in an argument. If you want a moral or political verdict, this isn't that tool.
- **It won't guarantee outcomes.** It deals in falsifiable *readings* and probabilities, not promises. A confident prediction still names what would prove it wrong.
- **It won't read your mind about the subject.** Vague or tiny inputs get vague reads. Feed it real material.

---

## Installing the skill

Install the `johnsons-vibe-check.skill` file in your Claude environment, then invoke it as above. Once installed, Claude consults it automatically whenever a request matches — assessing who something is for, whether it'll endure, or why it might be embraced or rejected.

---

## Going deeper

The skill ships with its full reasoning so you can audit or extend it:

- `references/Johnsons-Vibe-Check-grounding.md` — the complete framework: the rehabilitation cycle, the shadow method, the three-question sweep, the falsification discipline, and the glossary.
- `references/Morbius-case-study-off-diagonal.md` — a worked example of a precisely-aimed flop.
- `references/Clerks-case-study-off-diagonal.md` — a worked example of a scrappy, authentic endurer.
- `references/Kenobi-Anchor-grounding.md` — the original calibration case, kept for provenance.

These double as models for what a rigorous, honest report looks like — concede uncertainty, prefer the sharp finding over the flattering one, and keep the read pointed at the encoded audience rather than at anyone's values.
