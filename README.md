# tech-thai-reading-coach

A warm, structured **Thai reading coach** for English speakers who already speak some Thai and want to read
it better — using **AI/tech content** as the material, because if you work in or love tech, words like
`for loop`, `deploy`, `API`, and `model` are already yours. They're footholds. The coach starts from what
you know and reads outward into the Thai around them.

It's a folder you drop into a Claude project. The coach instructs in English, reads Thai with you, and —
this is the part that matters — **remembers where your reading is from session to session.**

---

## The method, in one real sentence

Here's an actual sentence from the reading ladder. Watch what happens when you stop treating it as a wall of
Thai and start from what you already own:

> ผมเจอ บัก หลัง deploy

- **`deploy`** — already English. You read it on sight, zero decoding. *(That's an anchor.)*
- **บัก** — *looks* Thai, but say it out loud: *bàk* → **"bug."** A consumer-tech loanword wearing Thai letters.
  A tiny, high-reward decode. *(That's the light stretch.)*
- **ผมเจอ … หลัง** — now *this* is the actual Thai to read: *"I found … after."* Three short words, and they're
  the only part that was ever unfamiliar.

Put it together: **"I found a bug after deploy."** You owned more than half the sentence before you started —
that's the loanword-anchor method, and it only works because English is the language you already have. The
coach does this for you on every passage: finds the footholds first, then spends your attention on the Thai
that's actually the lesson. (The full pedagogy is in [`reference/register-map.md`](reference/register-map.md).)

---

## What this is (and what it honestly isn't)

**What it is:** a structured Thai-reading coach that **tracks your level** and **feeds you tech content you
care about.** It meets you where your reading actually is, scaffolds you up, names what keeps tripping you,
and keeps a running record so every session continues the last one instead of starting over.

**What it isn't:** a claim that it reads or explains Thai better than a fresh AI chat. It doesn't. A cold AI
reads and explains Thai content perfectly well in the moment. **The difference is structure, not capability** —
the one thing a cold chat *can't* do is remember where your Thai reading is across sessions. (Ask one: it'll
tell you it has no memory of your level and point you to a flashcard app.) This coach holds that memory in a
file, and pairs it with a reading method built specifically for English speakers. That integration — tech-domain
reading + English-anchor pedagogy + level-tracking, in one place — is the whole point.

**The honest one-liner:** *Does it read Thai better than a fresh ChatGPT or Claude? No. It remembers where your
reading is, and it reads with you using anchors built for an English speaker. The edge is structure and memory,
not raw capability* — and that's a real edge, because it's the one thing a cold chat structurally can't reproduce.

If you want to read general Thai (cooking, travel, news), or you're a zero-beginner still learning the script,
or you're already fluent and just want a dictionary — this isn't the right tool, and it'll tell you so warmly
and point you somewhere better.

---

## Who it's for

An **intermediate English-speaking Thai learner**: you read the script but slowly, you speak some Thai, and you
work in or care about tech. You're past the beginner apps (too slow) but not ready for native material (too fast).
That middle is exactly where this coach lives.

---

## The moat, stated plainly

The defensible edge isn't the support and isn't the delivery format — both are copyable, and a cold AI already
does the in-session support. The edge is **`reference/level-state.md`**: a file that persists your reading level,
your known anchors, the words you read solidly vs. shakily, the weak spots you keep hitting (tagged script /
grammar / vocab), and what to focus on next. The coach reads it first every session and updates it at the end.
**That cross-session memory is the thing a fresh chat structurally cannot hold** — and it's paired with a
reading method (English tech terms as anchors) that no general-purpose Thai tool offers, because the anchors
only work if English is the language you already own.

This is a personal tool first. Its value to you doesn't depend on out-competing any app — it depends on
remembering where your reading is and helping it climb.

---

## How it works

1. The coach **reads `reference/level-state.md`** before it says anything — so it opens where you are, on the
   focus it set you last time.
2. It pulls a **passage at your level** from `reference/reading-ladder.md` and starts from the **English anchors**
   you already know (`reference/register-map.md`).
3. It **scaffolds you to the meaning** — finds the anchor, segments the phrase, decodes the loanword — using the
   named methods in `reference/reading-frameworks.md`. It doesn't hand you the translation; the reading is the rep.
4. When something keeps tripping you, it **names it, tags it, and drills it** directly.
5. At the end it **updates your level-state**, narrates the wins, and writes your next focus — then hands the
   block back for you to save.

---

## Setup (about 5 minutes)

1. Create a new **Claude Project** (or any assistant that can read a folder of files).
2. Add these files as project knowledge: `identity.md`, `rules.md`, `examples.md`, and everything in `reference/`.
3. **Seed your level-state once.** Open `reference/level-state.md`, copy the current-state block, and fill it with
   your *real* current reading level — honest, not aspirational (see the "seed entry" notes in that file). This is
   the one thing only you can supply: the coach never invents your level.
4. **Add a few passages.** `reference/reading-ladder.md` has level slots (L1–L5); drop in real tech-Thai you've
   encountered. A handful is enough to start; you add more over time.
5. Start a session by **pasting your level-state block** as your first message. The coach takes it from there.

Each session after that: paste the **updated** block the coach gave you at the end of the last one. That block
is the memory — keep it current and the coaching is continuous.

---

## Try it — three things to test

1. **Reading-scaffold.** Paste a Thai AI sentence and ask for help reading it. → The coach should anchor on the
   English term, scaffold the Thai around it warmly, and *neither* dump a full translation *nor* refuse.
2. **Level-tracking (the moat).** Run a short session, let the coach update your level-state at the end, then start
   a *fresh* session by pasting that updated block. → The coach should name your level and your prior weak spot and
   pick up the exact thread — the thing a cold chat can't do.
3. **Honest-scope.** Ask it to teach you Thai cooking vocabulary. → It should warmly keep you in the tech-Thai lane
   and point you elsewhere for general Thai, without making you feel wrong for asking.

---

## What's in the folder

| File | What it holds |
|---|---|
| `identity.md` | Who the coach is, who it serves, its forced first action (read level-state). |
| `rules.md` | How it coaches — the modes, the two warm boundaries, level-progression rules. |
| `examples.md` | Seven worked sessions, beat by beat. |
| `reference/level-state.md` | **The moat.** Your reading level + anchors + vocab + weak spots + log + next focus. Read first, updated each session. |
| `reference/reading-ladder.md` | The L1–L5 tech-Thai curriculum (passage slots you fill with real content). |
| `reference/register-map.md` | The loanword-anchor pedagogy — which words are your English anchors, which are the stretch. |
| `reference/reading-frameworks.md` | The four named scaffolding methods. |
| `LICENSE` | MIT. |

---

## Scope (v1)

- **Reading-first.** Writing and speaking are later phases — reading is the goal here, and it's visual.
- **No voice/audio.** Reading is visual; voice serves speaking/listening, which isn't the v1 goal.
- **Tech-Thai only.** The tech vocabulary is the on-ramp; general Thai is out of lane (the coach redirects warmly).

---

## A note on the Thai content

The English coaching is built in; the **Thai passages, the term tiers, and your level-state seed are yours to
supply** — real tech-Thai you actually read, and your real current level. The coach is built to never fabricate
Thai content: where a passage slot is empty, it asks you for one rather than inventing it. That's deliberate —
invented Thai reads as inauthentic, and your trust in the material is the whole point.

---

*By Gabe — Your AI Specialist. MIT-licensed. A structured Thai-reading coach that tracks your level and feeds you
tech content you care about.*
