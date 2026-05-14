---
name: sc301-cheatsheet
description: Apply SC301 exam-cheatsheet rules — 650-750 word essays in user's voice, short direct quotes with page citations, named concepts unquoted, examples mandatory, three co-equal primary sources (presentations + readings + teacher summaries), file structure with question lists before essays, year-tagged past-Qs. Use when producing or revising any L1-L17 cheat-sheet content in this project.
---

# SC301 Cheat-Sheet Style Skill

This skill encodes the rules for producing or editing the 17 lecture-cheat-sheet Markdown files in `cheat_sheets/`. Apply automatically when working in this project on SC301 revision content.

## Scope guardrail

- **Only lectures L1 through L17** are in scope. L18 and L19 are explicitly excluded.
- Lecture roster:
  1. L1 — Rethinking Modernity
  2. L2 — Modernity as a Colonial Project
  3. L3 — Animals
  4. L4 — Language and the World
  5. L5 — Feminism and Social Theory
  6. L6 — Standpoints, Perspectives, Epistemology
  7. L7 — Foucault on Power and Disciplinary Society
  8. L8 — Race and Social Theory
  9. L9 — Post-colonial Theory
  10. L10 — Vision
  11. L11 — Mass Culture and Popular Culture
  12. L12 — Culture Industry Reconsidered (Adorno)
  13. L13 — Public Sphere (Habermas)
  14. L14 — Culture is Ordinary (Williams)
  15. L15 — Structuralism, Semiology, Popular Culture
  16. L16 — Postmodernism
  17. L17 — The Turn to Gramsci and Hegemony

## File structure (strict order inside each `cheat_sheets/L<N>_*.md`)

1. Header — lecture number + title + sources fed in
2. Key concepts & thinkers — ≤200 words, scannable
3. Key notes from the presentation — slide-by-slide compressed; **every slide that poses a question gets a `💡 slide-question` callout**
4. Information from the readings — paraphrased, structured by argument; roughly equal depth to §3
5. Critical analysis with embedded key quotes — 5–10 short verbatim quotes, each formatted `> "..." — Author, *Work*, p. N`, woven into the analysis
6. **List** of past-year exam questions touching this topic — ALL relevant ones, chronologically ordered, YEAR-tagged: `**2023 (Q1):** To what extent ...`
7. **List** of 10–15 mock exam questions, numbered M1–M10/15, mixing 4 styles
8. Essay answers — for each question in §6 and §7, a 650–750-word answer with the question re-stated as a `### YEAR (QN): ...` or `### M<N>: ...` sub-heading

## Essay style rules

- **Length:** 650–750 words. Count words. If over, trim. If under, expand.
- **Question re-statement:** every answer sub-heading begins with the year+Q-number for past-Qs or `M<N>` for mocks, then the question text.
- **Direct quotes ARE allowed.** Format: `"<short quote>" (Author, *Work*, p. N)`. If page number unknown, write `[VERIFY p.?]`.
- **Named technical concepts** stay unquoted in running text — they are concept names, not quotes. Examples: docile bodies, double consciousness, culture is ordinary, hegemony, culture industry, public sphere, biopower, Black Atlantic, standpoint epistemology, structures of feeling, the male gaze, imagined community, symbolic violence, cathexis, the carceral, biopolitics, governmentality, the dialectic of enlightenment, the male/imperial gaze.
- **First-use attribution:** when a concept is first used in an essay, attach a short author tag (*"Foucault's notion of biopower…"*).
- **Examples are mandatory** when the question says "discuss with examples," and strongly preferred otherwise. Use concrete cases: empirical, historical, contemporary. Tie example to thinker.
- **Argumentative structure:** every essay should have a thesis (in the intro), 2–4 main argumentative moves (each one paragraph), engagement with at least one counter-argument or limitation, and a conclusion that returns to the thesis with development.

## Source-priority hierarchy

**Co-equal primary** — give each roughly equal time/depth when drafting:

1. Lecture presentation slides (`materials/Autumn Presentations/`, `materials/Spring Presentations/`)
2. Curated readings (`materials/Autumn Readings/`, `materials/Spring Readings/`)
3. Teacher summaries (`materials/Summaries from the teacher/`)

**Secondary** — consult for triangulation and to identify high-priority topics:

4. Revision docs (`materials/revisions/Revision 2025.pdf`, `Revision autumn and spring 2026.pdf`, `SC301-6-FY Rubric.pdf`)
5. Additions (`materials/Additions/`) — public-sphere supplements, teacher's email about Section B changes
6. Past exams (`past_exams/`) — for §6 list + mock-Q style calibration

## Mock-Q style mix (10–15 per lecture, blend all four)

- **"To what extent…"** — open-ended weighing
- **Single-author discussion** — "Discuss X's account of…"
- **Author comparison** — "Compare X's and Y's accounts of…"
- **"Discuss with examples"** — explicit demand for empirical grounding

## Out of scope / never do

- Sentence-length verbatim without attribution
- Editing or deleting anything in `materials/` or `past_exams/`
- Producing material for L18 or L19
- Generic LLM filler — every claim should be grounded in a source or labelled as the user's argumentative move

## When in doubt

- Mark page numbers `[VERIFY p.?]`
- Flag thin past-Q coverage inline
- Keep the user's voice ("I argue", "it can be shown") rather than passive academese
- Refer to `PLAN.md` and `CLAUDE.md` for project context
