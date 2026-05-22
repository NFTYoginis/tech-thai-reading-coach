# Reading ladder — the leveled tech-domain curriculum

Five levels of tech-Thai reading, easiest to hardest. The coach uses the ladder two ways: to **pick a
passage at the learner's current level** (from `level-state.md`), and to **know what "one step up" looks
like** when it's time to stretch. Each level has a definition (what reading at that level feels like) and
a slot for real passages.

> **Passages are operator-supplied — real tech-Thai the operator actually reads.** The level *definitions*
> and *selection rules* below are the structure; the Thai passages that fill each slot are lived content the
> operator adds (a doc line he hit at work, a Thai dev tweet, a paragraph from a Thai AI article). The coach
> never invents a passage — it pulls from this file or asks the operator to drop one in.

> **Every passage has a level-prefixed ID** — `L1-1`, `L2-3`, `L3-5` — that never restarts across levels.
> The coach cites passages by this ID, never a bare "passage 4" (which would be ambiguous across L1-4 / L2-4 / L3-4).

---

## The five levels

### L1 — Anchored single sentences
**What it feels like:** one short Thai sentence built around a single English anchor. Concrete, present-tense,
no subordinate clauses. The anchor (`deploy`, `bug`) carries most of the meaning; the Thai around it is short
and high-frequency. **Goal:** decode the Thai script with a familiar word holding your hand the whole way.

**Passages — L1** *(operator-supplied; the coach reads these verbatim, never reworded):*
**L1-1.** วันนี้ app ล่ม ตอนเช้า
**L1-2.** ผมเจอ บัก หลัง deploy
**L1-3.** โมเดลนี้ ตอบเร็ว มาก
**L1-4.** server ใหม่ ใช้งานได้ แล้ว
**L1-5.** เมื่อคืน update แล้ว แต่ error ยังอยู่
**L1-6.** client ส่ง file ผิด
**L1-7.** AI ตัวนี้ อ่านภาษาไทย ได้ดี
**L1-8.** โค้ดเก่า ทำให้ app ช้า

### L2 — Anchored short passages
**What it feels like:** 2–4 sentences on one small topic, with one or two anchors. Simple connectives appear
(the Thai for *and* / *but* / *because*). One or two Tier-3 loanwords (`โมเดล`, `โค้ด`) show up — the first light-stretch decodes.
**Goal:** hold meaning across more than one sentence; meet the first phonologized loanwords.

**Passages — L2** *(operator-supplied; the coach reads these verbatim, never reworded):*
**L2-1.** เมื่อคืนผม deploy โค้ดขึ้น server ใหม่ แล้วทุกอย่างดูปกติ ตอนเช้ามีคนส่งข้อความมาว่า app เข้าไม่ได้ สุดท้ายเจอ บัก เล็ก ๆ ในระบบ login
**L2-2.** ผมลองใช้ AI ตัวใหม่เพื่อช่วยสรุปบทความภาษาไทย โมเดลตอบเร็วมาก แต่บางครั้งมันเดาคำผิด ถ้า prompt ไม่ชัด ผลลัพธ์ก็จะงงนิดหน่อย
**L2-3.** วันนี้ client ขอให้เพิ่ม feature ใหม่ใน app เดิม แต่โค้ดเก่าค่อนข้างอ่านยาก เวลาแก้อะไรนิดเดียว บางที system ก็พังตรงอื่นอีก
**L2-4.** เมื่อวานผม train โมเดลด้วยข้อมูลชุดใหม่ ตอนแรกผลดูดีมาก แต่พอลองกับข้อมูลจริง accuracy กลับลดลง น่าจะเป็นเพราะโมเดล overfit
**L2-5.** ทีมกำลังย้ายข้อมูลไป cloud ใหม่ ตอนนี้บาง service ยังทำงานช้า เพราะ server เก่ายังปิดไม่ได้ทั้งหมด

### L3 — Mixed paragraphs
**What it feels like:** a real paragraph — multiple sentences, subordinate clauses, several anchors and a few
loanwords, and crucially, **longer noun phrases where word boundaries get genuinely hard** (Thai has no spaces).
The Thai is now carrying real meaning the anchors don't give you. **Goal:** segmentation under load; reading
for meaning, not just decoding word by word.

**Passages — L3** *(operator-supplied; the coach reads these verbatim, never reworded):*
**L3-1.** เวลาผม deploy ระบบใหม่ ผมพยายามแยกทีละส่วนก่อน ถ้า update ทุกอย่างพร้อมกัน เวลาเกิด error จะหาสาเหตุยากมาก บางครั้งปัญหาไม่ได้อยู่ที่โค้ดใหม่ แต่เกิดจาก config เก่าที่ยัง cache อยู่ใน server พอระบบเริ่มรับ traffic จริง ปัญหาถึงค่อยโผล่ขึ้นมา คนส่วนใหญ่คิดว่า deploy เสร็จแล้วคือจบ แต่จริง ๆ แล้วช่วงหลัง deploy สำคัญพอ ๆ กับตอนเขียนโค้ด
**L3-2.** ช่วงนี้ผมเริ่มอ่านบทความ AI ภาษาไทยมากขึ้น ตอนแรกผมอ่านช้ามาก เพราะมีทั้งคำไทยยาว ๆ และคำอังกฤษปนกันในประโยคเดียว แต่พอเริ่มจับ anchor ได้ เช่น model, prompt, API หรือ training ผมเริ่มเดาความหมายของประโยครอบ ๆ ได้เร็วขึ้น วิธีนี้ช่วยให้ผมไม่หยุดอ่านทุกครั้งที่เจอคำใหม่
**L3-3.** ปัญหาของโมเดลนี้ไม่ใช่เรื่อง accuracy อย่างเดียว แต่เป็นเรื่องข้อมูลที่ใช้ train ด้วย ข้อมูลส่วนใหญ่เป็นภาษาอังกฤษ พอให้มันตอบภาษาไทย คำตอบบางช่วงเลยดูแปลก ๆ โดยเฉพาะเวลาต้องอธิบายคำที่มี context ทางวัฒนธรรม ทีมเลยต้องเพิ่ม dataset ภาษาไทยเข้าไป และปรับ prompt structure ใหม่ทั้งหมด
**L3-4.** บางครั้งเวลาอ่านเอกสาร tech ภาษาไทย ผมเข้าใจ grammar โดยรวม แต่ติดตรงการแบ่งคำ เพราะภาษาไทยไม่มี space เหมือนภาษาอังกฤษ ถ้าประโยคมี noun phrase ยาว ๆ หรือศัพท์เฉพาะหลายคำติดกัน สมองจะเหนื่อยเร็วมาก โดยเฉพาะเวลาอ่านบนมือถือ แต่ถ้ามี loanword อย่าง server หรือ model อยู่ในประโยค ผมจะกลับมาจับ flow ได้ง่ายขึ้น
**L3-5.** ตอนนี้หลายบริษัทเริ่มใช้ AI ช่วยตอบลูกค้าอัตโนมัติ แต่ปัญหาคือคนส่วนใหญ่คิดว่าแค่ต่อ API แล้วทุกอย่างจะทำงานได้ทันที จริง ๆ แล้วต้องใช้เวลาปรับ prompt, จัดการ context และทดสอบคำตอบอีกเยอะมาก ถ้าระบบตอบผิดเพียงครั้งเดียว ลูกค้าอาจเสียความเชื่อมั่นทันที เพราะงั้น workflow หลังบ้านสำคัญไม่แพ้ตัวโมเดลเลย

### L4 — Lightly-edited real tech-Thai
**What it feels like:** actual tech-Thai from the wild — a doc blurb, a README line, a dev tweet, a forum
answer — lightly trimmed for length but not simplified. Anchors are present but sparse; idioms and natural
phrasing appear. **Goal:** read the language as it's really written, with the training wheels mostly off.

> *Passage slot — L4. Operator fills: real snippets he's encountered — Thai dev Twitter/X, a Thai package
> README, a Stack Overflow-style answer in Thai, a product doc. Light edits for length only; keep the natural
> phrasing. Note the source so the learner knows it's real.*

### L5 — Unedited short tech-Thai articles
**What it feels like:** a full short article or a complete blog paragraph, unedited. Anchors are now a small
fraction of the text; the Thai carries the load and the reading is close to native-difficulty for the topic.
**Goal:** sustained reading of authentic tech-Thai; this is the destination the ladder climbs toward.

> *Passage slot — L5. Operator fills: 2–4 unedited short articles or substantial paragraphs from Thai tech
> blogs / news / docs. No simplification. These are the "graduation" reads — the coach uses them to confirm a
> learner has truly reached L5, not just decoded one lucky paragraph.*

---

## How the coach selects a passage

1. **Read `level-state.md`** → current reading level (with its texture — e.g. "solid L2, stretching L3 on AI").
2. **Default to a passage at the solid level**, not the stretch — warm sessions start where the learner *wins*,
   then push. (Confidence is fuel; the coach doesn't open on the hardest thing.)
3. **Pick for the weak spot when there's a `next focus`.** If `level-state.md` names a GRAMMAR weak spot, choose
   a passage that contains that structure so the drill has real material.
4. **Recycle shaky vocab.** Prefer passages that re-use words sitting in the learner's "shaky" list, so they get
   a second/third encounter (spaced repetition by hand).
5. **Stretch deliberately, one level at a time.** When the learner has read at their level comfortably, the coach
   offers a single passage one level up and names it as a stretch ("this one's an L3 — let's see how it feels").

---

## How levels move (progression rule)

A learner moves up a level when, **across more than one session**, they read passages at the next level with
only occasional stalls and can pass a comprehension-check (restate the meaning) without the coach decoding it
for them. The coach does **not** promote on a single good passage — it names what it saw and waits for the
pattern, then updates `level-state.md` and tells the learner why. Movement is evidence-based and narrated, so
the learner sees their own progress rather than being told an abstract grade.

---

## What this file is NOT

- **Not a vocabulary list.** Vocabulary lives in `level-state.md` (the moving edge) and in the learner's own
  flashcard tool (the bank). This file holds *passages* organized by difficulty.
- **Not generated content.** Every passage is real tech-Thai the operator supplies. The coach never fabricates
  a passage to fill a slot — if a level has no passage yet, it says so and asks for one.
- **Not fixed-length.** Operator adds passages over time; the ladder gets richer with use. Empty slots are
  expected early — they're a to-fill list, not a defect.

---

*Level definitions and selection rules: build structure. Passages: operator-supplied real tech-Thai.*
