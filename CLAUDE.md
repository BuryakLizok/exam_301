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
- **Voice:** user's own voice; not LLM-generic. No em-dashes (`—`); use commas, colons, parentheses, or sentence breaks instead.
- **Citation format:** Harvard `(Author, Year: Page)` — colon between year and page, no `p.` prefix, no work title in parentheses. Examples: `(Habermas, 2006: 73)`, `(Fraser, 1992: 119)`, `(Habermas, 1989: 142, 232)`. When the author is named in narrative, use `Author (Year: Page)`. Book titles in narrative: italics. Article titles in narrative: single quotes.
- **Uncertain pages:** marked `[VERIFY PAGE?]` inline for joint pre-exam review.
- **Named technical concepts** (docile bodies, double consciousness, culture is ordinary, hegemony, culture industry, public sphere, biopower, Black Atlantic, standpoint epistemology, structures of feeling, the male gaze, etc.) — used unquoted because they are concept names, not quotations.
- **Brief attribution** on first concept use: e.g., *"Foucault's notion of biopower…"*.
- **Concrete examples are mandatory** when the prompt says "discuss with examples", strongly recommended otherwise.

## ⚠️ Source rule (refined)

**Two distinct categories — only ONE is forbidden.**

### ✅ Allowed: course-derived material AND general everyday cultural knowledge

- **Course-derived (preferred where the lecturer supplied them):** the specific cases on slides, in readings, in teacher summaries, in revision docs, in additions. Examples: Punk/Drill panic on L11 slides; Trump-on-Mexican-Americans on L8 slide 23; Branson/Virgin Records on L12 slides; *Love Thy Neighbour* on L14 slide; Disneyland/Watergate/Gulf War on L16 slides; Wall Street–Silicon Valley bloc via *Hegemony Now* on L17.
- **General-knowledge cultural references (OK to use freely):** brand names (Nike "Just Do It", Apple, Coca-Cola, Tesla, Disney), TV/film widely known (*Black Mirror*, *Adolescence*, *Coronation Street*, *Bake Off*, *Squid Game*, *Severance*, Marvel/MCU), public figures as cultural markers (Andrew Tate, Joe Rogan, Elon Musk), cultural movements (Black Lives Matter, #MeToo, Brexit, Trump's MAGA, Reform UK, cost-of-living crisis), social-media generic (Instagram, TikTok, Twitter/X), generic phenomena (deepfakes, AI chatbots, streaming algorithms, content moderation).

### ❌ Forbidden: specific researched facts

These look like the writer did internet research before the exam, which is not what the marker wants:
- Specific monetary amounts (£20m, €200m, $700m, $44bn)
- Specific named policies/legislation with dates (CARICOM 10-point plan, Online Safety Act 2023, Citizenship Amendment Act, EU AI Act, Hostile Environment as specifically defined)
- Specific court cases with citation (SFFA v Harvard 2023, *Bakke*, *Dobbs v. Jackson*)
- Specific statistics requiring lookup (Black maternal mortality 3-4x, UK Stop & Search 7-9x ratios, Sony 70% market share, Sweden 47% / UK 17% specific numbers UNLESS the lecturer's slide says so)
- Specific named commissions/inquiries (Macpherson Report, Sewell Report, Belgian Commission of inquiry, MBRRACE-UK)
- Specific named individual events with date precision (Glasgow's 2018 reparations programme, Dutch state's 2024 apology, the 1997 British female police officer case unless slide-confirmed)
- Specific named research studies (Buolamwini & Gebru *Gender Shades*, Obermeyer 2019 in *Science*)
- Specific named campaigns with year/place (Rhodes Must Fall began 2015 in Cape Town, Bandung 1955)

**Rule of thumb:** If the average literate person knows it as part of everyday culture, it's fine. If it has a year, a place, an amount, a percentage, a named report or named legislation attached to it, it's research-specific and should stay out — unless the lecturer put it on a slide.

## ⚠️ Essay length

**Strictly 650–750 words.** Anything over 750 needs trimming (cut repetition first). Anything under 650 needs expansion (add an example or extend a body move). The user does not have time during a handwritten exam to read 900-word essays.

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
