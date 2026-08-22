# PROJECT STATE — HITCHHIKER'S GUIDE / MITOCHONDRIAL SELF

**Hand this to the next steward before anything else.** It replaces the need to read the previous conversation.

Author: Ammon M. Covino.

---

## 1. CURRENT FILES

| File | Status |
|---|---|
| `HITCHHIKERS_REPO` (this repo, markdown) | **CURRENT TRUNK — v3.1.** Work from these files. |
| `..._v3_PROOFED.pdf` | Rendered snapshot for reading and distribution |
| `THE_MITOCHONDRIAL_SELF_v2.docx` | Book Two. Not yet revised to match Book One's standard. |
| earlier versions v1–v7 | Keep. Do not delete. Reference only. |

Book One: ~42,000 words, 14 chapters, 25 endnotes, 85 index entries.

---

## 2. STANDING RULES — NON-NEGOTIABLE

1. **Never compress the author's own words.** His dictation, his phrasing, his account. Compress your own prose freely; never his.
2. **New version file every time.** Never overwrite. He reads one version while the next is built.
3. **Run a diff after every build.** Report paragraph count, unchanged count, and change regions by chapter. He caught silent drift once and was right.
4. **No global find-and-replace without asking first.** Em-dash removal, spelling normalization and whitespace cleanup have each silently rewritten every chapter in this project.
5. **Never invent or assume a citation.** If a source is unverified, the note says so. If the author encountered something via a video, the note names the video, not a book he has not read.
6. **Surgical edits only.** One anchored string at a time. Do not touch chapters that were not asked about.
7. **Verify factual claims before they enter the text.** Several of his recollections have been right and several have been wrong. Check, then report both outcomes plainly.

---

## 3. SETTLED DECISIONS

- **Title:** *The Hitchhiker's Guide to the Homo Sapiens*. Final **s** required.
- **Subtitle:** *The Operating Manual*. He has expressed preference for *An Operating Manual for Life*. **Not yet decided.**
- **Title-page epigraph:** *The examined life is the life that finally examines the examiner, and finds the mitochondria looking back.*
- **No em dashes anywhere in prose.** All were removed deliberately. Do not reintroduce.
- **American spelling** throughout.
- **Byline:** "Ammon M. Covino" here; "Ammon Covino" on Alpha-Omega. **Unresolved.**
- **Book One / Book Two.** The line is *Read Book One first. Book Two was there first.* "Neither half is first" was removed everywhere.
- **Series line:** *Energy flows from within. Meaning radiates without. Life is the bridge.* Currently back cover only.
- The Reddit/Epstein piece is **not** book content; separate file.
- The personal account lives at the back as **Afterword**, not in the Preface.

---

## 4. STRUCTURE

Cover → Title page → Inside leaf → Contents → Preface → Introduction → Prologue → Ch 1–13 → Afterword → Notes → Index → Back cover

**Front matter is 5,422 words, 14% of the book.** The Prologue alone is 3,343 of that. If length is raised again, the Prologue is the target, not the Preface.

**Chapters:** 1 Inner Map · 2 Arcs, Bolts, Flip · 3 Words Are Spells · 4 Personal Position · 5 The Room Writes the Mind · 6 Scripture Engine · 7 Prophecy Engine · 8 Policing Empire · 9 Parasite and Host · 10 Money Is a Container · 11 Erase All Debt · 12 Stories They Told Us · 13 The Weld

---

## 5. OPEN ITEMS

**Five orphaned symbols** — introduced before Chapter One, never used again. Author has been told; no decision yet.
- *scale / north / legend* — the Preface's opening image. Proposed fix: return it in Ch 13.
- *mirror and oracle* (fairest / wisest) — proposed fix: move to Ch 12 with the other stories.
- *gadfly / diagnostician* — proposed fix: connect to the steward in Ch 3.
- *ego death* and *Logic and Roger* — testimony rather than tools; may not need reuse.

**Other open items**
- Chapter Six may need splitting; it carries four story analyses.
- Whether the Prologue should become Chapter One.
- Book Two has not been brought to Book One's standard.
- Author is compiling source notations — YouTube videos and studies — to be added. **Musashi came from AfterSkool on YouTube, not a book.** Note 3 already corrected.
- Covers exist but are not attached to the document.

---

## 6. WORKING METHOD

The book is built by a Node script using the `docx` library, not edited as a Word file. Each version has its own build script. Edits are made by exact string replacement in the script, then the whole document is regenerated. This is why the diff matters: the rebuild is deterministic, so untouched text comes out byte-identical, but a global operation touches everything.

Current version: v3.1 (markdown source of truth). Older `build_v8.js` / docx builds are superseded.

The author's preferred process from here: **chapter by chapter.** He reads a chapter, dictates his notes, and that triggers a rewrite of that chapter only. He does not want other chapters touched in the same pass.

---

## 7. WHAT THE BOOK ARGUES

So the next steward does not have to reverse-engineer it.

The territory is what is actually there. The map is any account of it you carry instead. Every map is a reduction, so every map leaves something out, so somebody decided what to leave out. That gap is the subject.

Three tools recur: the **Arc** (threat, protector, price), the **Bolt** (oath, sunk cost, paradox — the thing making departure cost more than staying), and the **Flip** (invert a system's claim about itself and look at the gap). Plus the **Alpha–Omega inversion**: you are always shown the finished institution, never the need that produced it.

The book's most original claim is that **humans have no findable Alpha**. Every other system can be traced to founders and dates; nobody can name the first person who said there is a place people go when they die. That absence is why the belief has been so hard to examine.

The closing move is **the weld**: mind, heart and gut examining what arrives before it becomes belief, with no override above them.
