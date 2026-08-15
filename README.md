Creative Learning Academy
(working title, subject to change)

**Contributors**

* Greg Livingston
* Derrick

**Status:** Concept & planning. No app built yet.

**What it is**

A tablet learning app for students that feels like a game, not homework. Students pick their grade and work through short "trails" of activities across Math, Reading/ELA, and Science, earning progress along the way with a mascot guide -- the exact look and feel will flex by age (younger grades lean more playful/game-like, high school leans more toward a clean, mature study-tool feel, but both stay standards-aligned underneath).

Starting scope: grades K-12, aligned to Texas TEKS standards, with every activity tagged to the skill it teaches and a parent/teacher view showing exactly what's covered.

Long-term goal: all states, not just Texas. Content built around underlying skills (not Texas-specific codes) so it can map to other states' standards as we expand, instead of rebuilding per state.

**How it makes money**

Parent subscription (first). Free tier + paid tier, same model as ABCmouse/Khan Academy Kids/Prodigy. Also the legally cleanest option -- COPPA bars targeted ads to kids under 13, so ad-supported isn't really viable here.

School/district licensing (later, bigger). Texas has a formal review process (IMRA) for state-approved instructional materials, which schools can then buy with state funding. Bigger payoff, slower process -- pursue once the product's proven.

**Compliance to build around from day one**

* COPPA: applies specifically to kids under 13 -- verifiable parental consent, minimal data collection, documented retention/deletion, no targeted ads. Accounts belong to the parent, not the child for that age range.
* Older students (13-17): not covered by COPPA, but covered by broader Texas minor-protection laws (like the App Store Accountability Act and SCOPE Act) -- different rules, not a free pass just because they're past the COPPA age.
* TEKS alignment: mapped by strand/topic for now, across all grade bands (elementary, middle, high school); needs real review from a teacher/curriculum specialist before we claim certified alignment.

**Roadmap**

Phase 1 -- Prototype. Working K-12 mockup, mock data, no real accounts.
Phase 2 -- COPPA-compliant account model. Parent-vs-child accounts, consent flow, minimal data.
Phase 3 -- Launch in Texas. Real accounts, real subscription billing.
Phase 4 -- Texas IMRA state adoption. Get approved for school/district purchasing.
Phase 5 -- Expand state by state. Map content to other states' standards.

**Curriculum reference -- STAAR study guide**

Before building Phase 1 content, `staar-guide/` holds a full breakdown of exactly what's tested on the STAAR test (Texas's current standardized test), sourced from the official TEKS standards behind it -- grade by grade, subject by subject, with the tested grades/courses called out. It covers Reading/Language Arts, Math, Science, and Social Studies, plus the five high school end-of-course exams (Algebra I, English I, English II, Biology, U.S. History). This is what Phase 1's content map should be built against so activities line up with what students are actually accountable for.

See [`staar-guide/README.md`](staar-guide/README.md) for the full guide.

**Folder structure**

* `staar-guide/` -- STAAR/TEKS curriculum reference (README + one file per tested subject)
* Everything else -- not set up yet.
