# Register map — the loanword-anchor reading pedagogy

This file is the **on-ramp**. It tells the coach which words in any tech-Thai passage are *anchors*
the English-speaking learner already knows on sight, and which are the *stretch* they have to actually
read. The whole reading method starts here: **find the anchor, then read outward from it.**

> The classification below is the operator-validated 4-tier rule. It began life in a sibling coach as a
> *speaking*-register guide; here it does a different job — it's the map of where the reading is easy and
> where it's hard, for a reader whose native language is English. **Operator validates and extends the
> tiers over time** as real tech-Thai reading turns up new terms.

---

## Why this is the on-ramp (the loanword-anchor idea)

A real tech-Thai sentence is not uniformly hard for an English speaker. Some of it is *already in English*:

> *(Schematic — real passages live in `reading-ladder.md`. The point is the shape:)*
> Thai-grammar-words **`for loop`** Thai-grammar-words **`function`** Thai-grammar-words.

The **`for loop`** and **`function`** are anchors — the reader recognizes them instantly, with zero
decoding cost. That recognition is a foothold. From a known word, the surrounding Thai is no longer a wall
of unfamiliar script; it's "the bit between two things I already understand." The coach uses the anchor to
lower the activation energy, then directs attention to the Thai that's actually the lesson.

This is why the method is **English-speaker-specific** and why no Thai-reading tool built for Chinese or
general learners can offer it: the anchors only work as anchors if English is the language you already own.

---

## The 4 tiers (which words are anchors, which are the stretch)

| Tier | What it is | In the text it appears as | Anchor or stretch? |
|---|---|---|---|
| 1 | **Infrastructural / dev-workflow terms** | **English script**, untranslated | **ANCHOR** — read on sight |
| 2 | **Conceptual field labels** | **English script**, untranslated | **ANCHOR** — read on sight |
| 3 | **Culturally-absorbed consumer-tech loanwords** | **Thai script** (phonologized) | **STRETCH (light)** — decode, but the sound maps back to a familiar English word |
| 4 | **Ultra-common spoken slang** | **Thai script** (shortest form) | **STRETCH (light)** — same, very short |

Everything *else* in the sentence — the Thai grammar words, particles, and non-tech content vocabulary —
is the **real stretch** and the actual reading lesson.

The teaching move per tier:

- **Tier 1 & 2 (English anchors):** the coach points to them first. "You already know `deploy` and `API` —
  let's start from those and read out." No decoding needed; they're the footholds.
- **Tier 3 (phonologized loanwords):** these *look* Thai but *sound* like the English word the learner
  knows — so they're a bridge. The coach teaches the reader to decode the Thai script and hear the English
  underneath: say `โมเดล` out loud and you'll hear *model* wearing Thai letters. A small, high-reward decoding win.
- **Tier 4 (slang):** same as Tier 3 but shorter and more colloquial — a quick decode that pays off because
  the term recurs constantly.

---

## Validated term table (operator-validated; extend over time)

| English term | Appears in Thai text as | Tier | Anchor / stretch |
|---|---|---|---|
| for loop | `for loop` | 1 | Anchor |
| function | `function` | 1 | Anchor |
| argument | `argument` | 1 | Anchor |
| deploy | `deploy` | 1 | Anchor |
| merge | `merge` | 1 | Anchor |
| PR / pull request | `PR` | 1 | Anchor |
| API | `API` | 1 | Anchor |
| logs | `logs` | 1 | Anchor |
| repo | `repo` | 1 | Anchor |
| GitHub | `GitHub` | 1 | Anchor |
| Claude Code | `Claude Code` | 1 | Anchor |
| context window | `context window` | 1 | Anchor |
| prompt | `prompt` | 1 | Anchor |
| overfit | `overfit` | 1 | Anchor |
| regularization | `regularization` | 1 | Anchor |
| AI | `AI` | 2 | Anchor |
| machine learning | `machine learning` / `ML` | 2 | Anchor |
| model | `โมเดล` | 3 | Light stretch — decodes to "model" |
| code | `โค้ด` | 3 | Light stretch — decodes to "code" |
| app | `แอป` | 3 | Light stretch — decodes to "app" |
| debug | `ดีบัก` | 3 | Light stretch — decodes to "debug" |
| token | `โทเค็น` | 3 | Light stretch — decodes to "token" |
| bug | `บัก` | 4 | Light stretch — decodes to "bug" (shortest form; not `บั๊ก`) |

*(Operator extends this table from real tech-Thai reading. When a new term shows up, classify it by tier and
add it. The long tail of technical vocabulary is Tier 1 — English, an anchor — by default.)*

---

## How the coach uses this map in a read

For any passage, before scaffolding, the coach silently scans it through this map:

1. **Mark the anchors** (Tier 1/2 English terms). These are read first and for free.
2. **Mark the light-stretch loanwords** (Tier 3/4). Flag that the *sound* maps to a known English word —
   teach the decode, claim the quick win.
3. **Everything left is the lesson** — the Thai grammar and content vocab. This is where the session's real
   reading work goes (and where the weak spots in `level-state.md` get hit).

The reader is never told "here is tier 1 vs tier 3." The map is the *coach's* tool for deciding where the
easy footholds are and where to spend the reader's attention. The reader just experiences: "oh — I already
knew half of this; the new part is smaller than it looked."

---

## A note the coach can teach (when the reader asks about register)

If the reader wonders *why* so much tech vocabulary stays in English inside Thai text: that's how Thai tech
speech actually works. Real practitioners keep workflow terms in English and wrap them in Thai grammar, and
only the consumer-facing loanwords (Tier 3/4) get a settled Thai-script form. So reading real tech-Thai
*rewards* the English speaker — the hard surface is smaller than a textbook makes it look. The coach can
share this as encouragement; it is not a register *lesson* (this is a reading coach, not a writing one).

---

## What this file is NOT

- **Not a writing/speaking-register guide.** v1 is reading-first. This map exists to locate anchors and
  stretch in *reading*, not to tell the learner how to write or speak.
- **Not a phonologization dictionary.** Most tech vocabulary stays English (Tier 1, an anchor); the
  Thai-script forms are the marked Tier 3/4 exceptions.
- **Not exhaustive or static.** The long tail is Tier 1 by default; the operator extends the table as real
  reading surfaces new terms.

---

*Operator-validated 4-tier classification; repurposed here as the reading on-ramp. Operator owns Thai-term
validation and extension.*
