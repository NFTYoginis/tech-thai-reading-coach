# Level state — the file the coach reads first

<!-- Pass-2 (operator): bilingual Thai labels can be added to the headers and template fields below.
     Left English-only in this scaffold — the coach never authors Thai cold. -->


This is the one file that makes this a *coach* and not a chat. The coach reads it at the
start of every session, meets you exactly where your Thai reading is, and updates it at the
end. **A cold AI has no memory of where your reading is — this file is that memory.**

It is the load-bearing piece of the whole repo. Everything else (the ladder, the
frameworks, the register map) is in service of keeping this file accurate and moving you up it.

---

## How to use this file

1. At the start of a session, paste the **current state block** (below) into your first message
   — either the seed you wrote once, or the version the coach handed you at the end of last session.
2. The coach reads it before responding, so it already knows your level, your known anchors,
   and the weak spots you keep hitting. It does **not** start from zero.
3. At the end of the session the coach hands you an updated block. **Save it** (paste it back here,
   or keep it in a notes file). The updated block is the only thing that carries between sessions —
   so if you lose it, the coach loses your progress.

> **The file *is* the memory.** The coach retains nothing else between sessions. Keep the block current
> and the coaching is continuous; let it go stale and you're back to a cold tutor.

---

## The current-state block (copy this whole block each session)

*This is the **blank template** — the canonical shape of the block, field by field. The **live, filled
version** (the operator's real reading state) is the seed block near the bottom of this file; that's the one
you actually paste at the start of a session.*

```
LEVEL STATE

Date:
  [YYYY-MM-DD]

Reading level:
  [L1–L5 on the reading ladder. See reference/reading-ladder.md for what each level reads like.
   L1 = anchored single sentences · L2 = anchored short passages · L3 = mixed paragraphs ·
   L4 = lightly-edited real tech-Thai · L5 = unedited short tech-Thai articles.
   It is fine to be "L2, edging into L3 on familiar topics." Reading level is not one number —
   note where you're solid and where you're stretching.]

Known anchors:
  [The English tech terms you already recognize on sight inside Thai text and can read around
   without stalling — e.g. for loop, function, deploy, API, model. These are your on-ramps.
   The coach leans on them; growing this list is part of progress.]

Vocab — solid:
  [Thai (non-anchor) content words you now read reliably. Add to this each session. This is the
   list that should grow fastest — it's the visible proof you're moving.]

Vocab — shaky:
  [Thai words you decoded with help but haven't locked in. The coach recycles these into the
   next passages on purpose, so you meet them again before they fade.]

Recurring weak spots:
  [REQUIRED FIELD. Categorize each one as SCRIPT, GRAMMAR, or VOCAB — the category decides which
   framework the coach reaches for. This is what makes the coaching targeted instead of generic.
     · SCRIPT  = decoding the letters themselves: consonant classes, vowel placement (above/below/
                 around the consonant), tone marks, consonant clusters, sara-am, the silent-consonant
                 marker (karan), the same letter taking different sounds.
     · GRAMMAR = the sentence won't parse even when you can sound out the words: word-boundary
                 segmentation (Thai has no spaces), classifiers, particles, word order, topic-comment.
     · VOCAB   = you can read it and parse it but don't know what the word means.
   Write each as e.g. "SCRIPT — I keep misreading a particular vowel cluster" or
   "GRAMMAR — I can't tell where one word ends and the next begins in long noun phrases."]

Session log:
  [One line per past session, newest first. Format: "YYYY-MM-DD — read [what], at L[n]; worked on
   [weak spot]; learned [N] new words." Keep the last ~6 lines; older ones can be trimmed.
   This is your reading diary — it's how you (and the coach) see the trend, not just today.]

Next focus:
  [What the coach decided you should hit next session, written at the end of last session.
   One or two specific things — a weak spot to drill, a level to attempt, vocab to recycle.
   The coach reads this first thing and opens the session on it. If blank, it's a fresh start.]
```

---

## Field-by-field notes

**Date.** Lets the coach gauge time since last session. After a long gap (2+ weeks) it will re-check
your level lightly before pushing, because reading skill fades faster than it builds.

**Reading level.** Maps to `reference/reading-ladder.md`. It is deliberately a *range with texture*
("solid at L2, stretching to L3 on AI topics"), not a single grade — reading level is uneven across
topics and the coach should respect that.

**Known anchors.** The heart of the loanword-anchor method (`reference/register-map.md`). These English
terms are the footholds the coach starts every hard passage from. The list growing means more of any
tech passage is already familiar, so more attention is free for the surrounding Thai.

**Vocab — solid / shaky.** Two lists, not one, on purpose. *Solid* is your progress made visible.
*Shaky* is the coach's queue — it deliberately reuses shaky words in upcoming passages (spaced
repetition by hand) so they get a second and third encounter before they slip.

**Recurring weak spots.** The most load-bearing field after reading level. The SCRIPT / GRAMMAR / VOCAB
tag is not decoration — it routes the coaching. A SCRIPT weak spot gets a decoding drill; a GRAMMAR
weak spot gets a word-by-word segmentation pass; a VOCAB gap gets recycling. If you only fill one
field besides level, fill this one.

**Session log.** Your reading diary. The coach uses it to spot trends ("you've stalled at L2 for three
sessions on the same weak spot — let's drill it directly this time") rather than treating every session
as new. This is the longitudinal view that a cold AI structurally cannot produce.

**Next focus.** Written by the coach at session-close, read by the coach at session-open. It is the
hand-off that turns separate sessions into one continuous arc.

---

## What the coach does at end-of-session (Session-close mode)

At the end of every session the coach hands you an updated block. Specifically it:

1. Updates **Date**.
2. Adjusts **Reading level** only if there's real evidence you moved (not after one good passage —
   it names what it saw, e.g. "you read an L3 paragraph with only two stalls; I'm marking you L2→L3 on
   AI topics").
3. Moves newly-locked words from **shaky → solid**, and adds today's new words to **shaky**.
4. Updates **Recurring weak spots** — removes one only when you've cleared it across more than one
   session; adds a new one if a pattern showed up today.
5. Appends one line to the **Session log**.
6. Writes a specific **Next focus** for the opening of next session.

The coach narrates these updates briefly so you see your own progress — the update is part of the
encouragement, not silent bookkeeping.

---

## The seed entry — the live current state

Your **first** state block is the seed. Because you are the lived user, the honest seed is your *real*
current Thai reading level — not an aspirational one. Be candid about where you stall: that's what makes
the first session land where you actually are.

The block below is **live** — it's the operator's own honest reading state, written once and from here on
self-updating at every session-close. Paste it as your first message; the coach reads it before it says
anything. (When the coach hands you an updated block at the end of a session, replace this one with it.)

```
LEVEL STATE

Date: 2026-05-22

Reading level: L2 solid (anchored short passages), edging into L3 (mixed paragraphs) on familiar tech & wellness topics. Reading is fragmented, not linear: I recognize chunks, decode loanwords, infer from anchors. Bottleneck is reading automaticity + tone-decoding-while-reading, NOT grammar (grammar runs ahead of reading speed).

Known anchors: deploy, server, model/โมเดล, บัก, overfit, and English/phonologized tech terms generally.

Vocab — solid (by domain): yoga, anatomy, movement, wellness, travel, food, relationships, scheduling, casual business/social, mixed AI-workflow Thai-English.

Vocab — shaky: (none logged yet — first sessions populate)

Recurring weak spots:
  SCRIPT — slow recognition of less-common consonants & consonant clusters
  SCRIPT — tone decoding while reading (tone rules interacting with unfamiliar words)
  VOCAB  — breadth in formal / dense written Thai

Session log: (empty — first session fills)

Next focus: (blank — fresh start)
```

This seed is the operator's to write and own; the coach never invents or edits a level. It only updates the
block at session-close, narrating what it changed and why.

---

## What this file is NOT

- **Not a profile or a CRM record.** It's a working reading-state, updated every session.
- **Not optional.** The forced first action in `identity.md` reads this file before the coach responds to anything.
- **Not a goals doc.** "Read Thai news fluently in a year" belongs in a journal elsewhere. This file is about
  where your reading *is* and what's *next* — the concrete, not the aspirational.
- **Not exhaustive vocab storage.** It tracks the moving edge (recent solid / shaky / weak spots), not every
  word you've ever seen. A full vocab bank belongs in a flashcard tool; this file is the coach's working memory.

---

*This file is the moat. A cold AI reads Thai well but cannot hold your level across sessions — that's exactly
the gap this fills.*
