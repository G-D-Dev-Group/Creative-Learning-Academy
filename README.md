Creative Learning Academy
(working title, subject to change)

**Contributors**

* Greg Livingston
* Derrick

**Status:** Concept and planning. No app built yet.

**What it is**

A tablet learning app for students that feels like a game, not homework. Students pick their grade and work through short "trails" of activities across Math, Reading/ELA, and Science, earning progress along the way with a mascot guide. The look and feel changes by age. Younger grades lean more playful and game like, high school leans more toward a clean, mature study tool feel, but both stay standards aligned underneath.

This will be a downloadable app for tablets and phones, and also a website. The app is the main experience for kids. The website is there for parents and teachers to log in from a browser, check progress, and manage accounts without installing anything.

Starting scope is grades K through 12, aligned to Texas TEKS standards, with every activity tagged to the skill it teaches and a parent/teacher view showing exactly what's covered.

Long term goal is all states, not just Texas. Content gets built around the underlying skills, not Texas specific codes, so it can map to other states' standards as we expand instead of rebuilding everything per state.

**How it makes money**

Parent subscription first. Free tier plus paid tier, same model as ABCmouse, Khan Academy Kids, and Prodigy. It's also the legally cleanest option since COPPA bars targeted ads to kids under 13, so ad supported isn't really viable here.

School and district licensing comes later, and it's the bigger opportunity. Texas has a formal review process (IMRA) for state approved instructional materials, which schools can then buy with state funding. Bigger payoff, slower process. Pursue this once the product is proven.

**Compliance to build around from day one**

* COPPA applies specifically to kids under 13. That means verifiable parental consent, minimal data collection, documented retention and deletion, and no targeted ads. Accounts belong to the parent, not the child, for that age range.
* Older students, ages 13 to 17, aren't covered by COPPA, but they are covered by broader Texas minor protection laws like the App Store Accountability Act and the SCOPE Act. Different rules apply. Being past the COPPA age isn't a free pass.
* TEKS alignment is mapped by strand and topic for now, across all grade bands (elementary, middle, high school). It needs a real review from a teacher or curriculum specialist before we can claim certified alignment.

**Placement test prep courses**

Along with the core grade level curriculum, the app should offer placement test prep for every grade. These are short courses built around the tests families actually use to move a student between tracks: gifted and talented screening, magnet or charter school entrance exams, AP or dual credit qualifying exams, grade skipping or acceleration assessments, and district run math or reading placement tests that decide whether a student lands in honors, advanced, or remedial classes. This is a different bucket from the core STAAR aligned content. It's optional, higher stakes, and only matters to families actively trying to test into something.

**Note to self: school district guidelines are not all the same**

TEKS and STAAR are the state floor, but individual districts layer their own stuff on top, and it's not uniform. Different pacing guides, extra local benchmark tests, different qualifying scores for gifted and talented or advanced placement, different report card standards. Placement test content especially can't be treated as one size for the whole state.

Before actually building the placement prep courses:
* Look into how placement tests and cutoffs differ across a few big Texas districts first, like Houston ISD, Dallas ISD, Austin ISD, and Fort Worth ISD, to see how much they actually diverge from each other.
* Decide on a content model before building anything: one shared placement track with notes for each district, or fully separate tracks per district. This affects how the data gets structured from the start.
* Don't advertise or label any placement content as matching a specific district's test until it's actually been checked against that district's real guidelines.

**Roadmap**

Phase 1: Prototype. Working K through 12 mockup, mock data, no real accounts.
Phase 2: COPPA compliant account model. Parent versus child accounts, consent flow, minimal data.
Phase 3: Launch in Texas. Real accounts, real subscription billing, app and website both live.
Phase 4: Texas IMRA state adoption. Get approved for school and district purchasing.
Phase 5: Expand state by state. Map content to other states' standards.

**Curriculum reference: STAAR study guide**

Before building Phase 1 content, `staar-guide/` holds a full breakdown of exactly what's tested on the STAAR test, Texas's current standardized test, sourced from the official TEKS standards behind it. It's organized grade by grade and subject by subject, with the tested grades and courses called out. It covers Reading/Language Arts, Math, Science, and Social Studies, plus the five high school end of course exams: Algebra I, English I, English II, Biology, and U.S. History. This is what Phase 1's content map should get built against, so activities line up with what students are actually accountable for.

See [`staar-guide/README.md`](staar-guide/README.md) for the full guide.

**Folder structure**

* `staar-guide/`: STAAR/TEKS curriculum reference (README plus one file per tested subject)
* Everything else: not set up yet.
