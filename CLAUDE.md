# SC301 — Open-Book Exam Cheat-Sheet Project

This project produces revision notes for the user's SC301 (Sociology / Social Theory) open-book exam.

The full execution plan lives in `PLAN.md` (this folder). This file is short on purpose — read `PLAN.md` for full detail.

## Scope

- 17 lectures: **L1 through L17** only. L18 and L19 are **out of scope** (not on the exam).
- 17 self-contained Markdown files in `cheat_sheets/`, one per lecture.

## File structure of each `L<N>_*.md` (strict order)

1. Header (lecture #, title, sources fed in)
2. Key concepts & thinkers (≤200 words)
3. Key notes from the presentation (slide-by-slide, mark every slide-question as `💡 slide-question`)
4. Information from the readings (paraphrased, structured by argument)
5. Critical analysis with embedded **key quotes** (5–10 short, attributed: Author, *Work*, p. N)
6. **List** of past-year exam questions for this topic — YEAR-tagged (`2023 (Q1): …`), chronological, ALL relevant past-Qs (not filtered to top 2–3)
7. **List** of 10–15 mock exam questions in 4 styles (to-what-extent, single-author, comparison, discuss-with-examples)
8. Essay answers — for every question in §6 and §7, a 650–750-word model answer with the question re-stated as a sub-heading

## Style rules for all essay answers

- **Length:** 650–750 words each
- **Voice:** user's own voice; not LLM-generic
- **Direct quotes ARE allowed** from readings, short, with full citation `(Author, *Work*, p. N)`. Uncertain page numbers marked `[VERIFY p.?]` for joint review.
- **Named technical concepts** (docile bodies, double consciousness, culture is ordinary, hegemony, culture industry, public sphere, biopower, Black Atlantic, standpoint epistemology, structures of feeling, the male gaze, imagined community, symbolic violence, cathexis, the carceral, etc.) — used unquoted because they are concept names, not quotations.
- **Brief attribution** on first concept use: e.g., *"Foucault's notion of biopower…"*.
- **Concrete examples mandatory** when prompt says "discuss with examples"; strongly recommended otherwise. Example mappings: panopticon → modern surveillance / school discipline; culture industry → streaming algorithms / Hollywood franchises; Black Atlantic → music & diaspora; standpoint epistemology → care work / women in STEM; etc.

## Source priority (when drafting)

**Co-equal primary** (spend roughly equal time on each):

1. **Lecture presentations** (`materials/Autumn Presentations/`, `materials/Spring Presentations/`) — mine slide-questions specifically as exam cues
2. **Readings** (`materials/Autumn Readings/`, `materials/Spring Readings/`) — pre-curated by user to specific chapters/pages, high-yield
3. **Teacher summaries** (`materials/Summaries from the teacher/`) — especially Spring's weekly Word docs from the new teacher

**Secondary**:

4. **Revisions** (`materials/revisions/`) — Revision 2025.pdf, Revision autumn and spring 2026.pdf, `SC301-6-FY Rubric.pdf`
5. **Additions** (`materials/Additions/`) — supplementary readings + teacher's email about Section B changes (`Links from the emails.docx`)
6. **Past exams** (`past_exams/`) — 27 papers, 2001–2025; source of past-Q section + mock-Q style calibration

## Mock-Q style mix (per user observation of past papers)

- "To what extent…" (open-ended)
- Single-author critical discussion ("Discuss X's account of…")
- Author comparison ("Compare X's and Y's accounts of…")
- "Discuss with examples" (mandates empirical illustration)

## Final joint revision pass

After all 17 MD files are produced, user and Claude verify every cited page number against the actual reading PDFs, spot-check quote accuracy, confirm attributions, trim/expand essays as needed.

## Out of scope

- L18, L19
- Modifying / deleting existing `materials/` or `past_exams/` content
- Sentence-length unattributed verbatim (verbatim with citation is fine)

---

**Last updated:** 2026-05-14. Source of truth for full spec: `PLAN.md`.
