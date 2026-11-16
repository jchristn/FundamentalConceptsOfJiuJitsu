# Fundamental Concepts of Jiu Jitsu

Subtitle: `A Mental Model for Every Stage of the Journey`

This repository contains a first-pass draft for a conceptual Brazilian jiu jitsu book by Joel Christner. The manuscript is being built through an interview-driven ghostwriting loop. The goal is not to create a technique encyclopedia. The goal is to capture Joel's mental model for understanding why jiu jitsu works across positions, attacks, escapes, pins, and transitions.

GitHub repository: `https://github.com/jchristn/BjjBook`

Buy the book on Amazon: [Fundamental Concepts of Jiu Jitsu](https://www.amazon.com/Fundamental-Concepts-Jiu-Jitsu-Journey/dp/B0HNJGJ2Z5/)

## Repository Layout

- `markdown/`: reader-facing manuscript, one Markdown file per chapter. Kept in sync with the latest Word revision.
- `word/`: Word manuscript revisions (`.docx`). The newest dated revision is the source of truth for the published copy.
- `images/`: photographs for the book.
- `covers/`: cover artwork.

## Restart Prompt

If the harness, chat, or agent process crashes, reopen this folder and use this prompt:

```text
Keep going. Continue the interview-driven ghostwriting loop for `Fundamental Concepts of Jiu Jitsu: A Mental Model for Every Stage of the Journey`.

Start in C:\Users\joelc\Documents\Books\Jiu_Jitsu_Fundamentals.

First read, in order: `README.md`, `dev/36_Draft_Status.md`, `dev/38_Manuscript_Map.md`, `dev/39_Manuscript_Style_Sheet.md`, `dev/HOW_JOEL_RESPONDS.md`, `dev/QUESTIONS_FOR_JOEL.md`, `dev/35_Author_Interview_Queue.md`, and `dev/00_Book_Outline.md`.

Treat Joel as the author and the agent as ghostwriter/interviewer. Ask targeted, specific, concept-first questions. Use Joel's answers to update the manuscript, `dev/HOW_JOEL_RESPONDS.md`, `dev/QUESTIONS_FOR_JOEL.md`, `dev/35_Author_Interview_Queue.md`, `dev/36_Draft_Status.md`, and `dev/39_Manuscript_Style_Sheet.md` where appropriate. Keep the book conceptual, cross-reference related sections, preserve Joel's voice, remove answered questions, add better follow-up questions when new gaps appear, validate against `C:\Code\Agents\requirements\WRITING_DOCUMENTS.md`, then commit and push to origin main when the pass is complete or when Joel asks.

Current next question: three new Part Two chapters were scaffolded as placeholders and need Joel's concepts, why-first: `markdown/28_Takedowns.md`, `markdown/29_Turtle.md`, and `markdown/30_Front_Headlock.md`. A whole-manuscript cross-reference and tone pass has already run (explicit "(refer back to X)" and "(you'll learn more about this in X)" ties added throughout, and the last buys/costs phrasing removed). Start with takedowns: ask for the standing version of the four battles and which one decides the takedown; the read for shooting, throwing, pulling guard, or staying standing; how Joel's boxing and wrestling background shaped how he teaches the standing game to fundamentals students; and the safety concepts that keep standing drilling injury-free. Then turtle (shell versus launchpad; the top player's back-or-front-headlock fork) and front headlock (why head control controls the body; guillotine/anaconda/darce as two-on-one; the neck-or-back dilemma; choke versus crank). Keep proposing option menus when Joel delegates example-generation.

Standing constraints:
- Stay conceptual. Do not turn the book into a technique manual. Concrete sequences belong only when they expose a decision rule, concept, mindset, safety boundary, or recurring mistake.
- Do NOT frame tradeoffs as "this buys me / this costs us." Use mechanism and consequence, or Joel's "no free lunch."
- When an answer arrives as a research-style writeup with citations, keep only the mental model, rewrite it in Joel's voice, and strip external citations and outside instructor names. Attribution policy: Ron Keslar/AKA, Rudy Sanchez/Smash Gyms, Andrew Kerfoot/Nexus, Refuge Jiu Jitsu.
- State Joel's preferences as preferences and respect players who disagree.
- Avoid generic AI prose, canned `matters` bridge constructions, and anecdote-led chapter openings.
```

## Files to Read First

Read these before continuing work:

1. `README.md`
2. `dev/36_Draft_Status.md`
3. `dev/38_Manuscript_Map.md`
4. `dev/39_Manuscript_Style_Sheet.md`
5. `dev/HOW_JOEL_RESPONDS.md`
6. `dev/QUESTIONS_FOR_JOEL.md`
7. `dev/35_Author_Interview_Queue.md`
8. `dev/00_Book_Outline.md`

Use `C:\Code\Agents\requirements\WRITING_DOCUMENTS.md` for publication prose. Use `C:\Code\Agents\writing\WRITING_BOOKS.md` and `C:\Code\Agents\writing\WRITING_LIKE_JOEL.md` for the reusable book-writing process and Joel's broader writing style.

## Interview Style

The agent should operate as a ghostwriter and interviewer, not as a generic BJJ explainer. Questions should be targeted, specific, and willing to go deep. Ask about how Joel thinks, what he notices first, what mistake he sees repeatedly, what sentence he uses while coaching, what both players want in a position, and which concept explains the exchange.

Weight the questions toward the `why`, not the `how`. The point of nearly every question is to surface the reason a thing works, the problem it solves, the read that tells Joel to reach for it, and the principle that lets a reader recognize the same situation elsewhere. A question that only produces a sequence of steps has usually failed. When a technique has to come up, ask why it exists and what it answers, not how to perform it. If a `how` detail is needed at all, it is only to expose a `why`: a decision rule, a recurring mistake, a safety boundary, or a transferable concept. Prefer questions of the form "why does this work," "what problem does this solve," "what tells you to choose it," and "why this instead of that" over questions of the form "what are the steps."

Stay concept-first. Joel has explicitly corrected the interview when it became too instructional. Do not ask for every pathway a match could take. Concrete sequences belong when they expose a decision rule, reveal a transferable concept, or give the reader a better diagnostic question. Highly specific route-completion details usually do not belong unless Joel asks for a technical manual.

Follow-ups are encouraged. If Joel gives a strong answer, ask the next question that pulls on that thread. The interview can meander among positions when the concept calls for it. It should still be deliberate: closed guard, half guard, side control, mount, back control, leg entanglements, top and bottom mindset, offensive and defensive jobs, safety, attribution, and reader application all need periodic attention.

Joel often answers by contrasting common understanding with his own. Preserve that structure when it helps:

- Traditional view: fundamentals as basic techniques.
- Joel's view: fundamentals as positional understanding, safety, control, advancement, attack, defense, recovery, and the ability to diagnose why something is working or failing.

## Thematic Elements

The manuscript is organized around recurring concepts, not isolated moves:

- Four battles: head height, hip height, grips, and posture/base.
- Quadrants and directional sweeping.
- Konami Code as an opportunity scan.
- Centerline, inside position, and strike zone.
- Two-on-one control.
- Cutting the opponent in half.
- Every submission starts as a pin.
- Fulcrums, levers, posts, frames, wedges, and obstacles.
- Spinal alignment and misalignment.
- Yin and yang: each position has opposite jobs.
- Dilemmas: real threats that force useful choices.
- Making and taking space.
- Top-player and bottom-player mindset.
- Safety, restraint, catch and release, and respect for training partners.

The reader is the cerebral student who wants the why behind jiu jitsu. They may be lost, or they may already be good and trying to understand why their jiu jitsu works. The book should help both beginners and advanced practitioners see the same recurring problems at different stages of the journey.

The book should function as a pointer rather than a reference. Readers should take one or two ideas to training, search for one thing at a time, highlight heavily, write in the margins or keep a journal, and let the mat tell them what needs attention next.

## Procedural Loop

For each meaningful interview pass:

1. Read the current queue in `dev/QUESTIONS_FOR_JOEL.md` and the compact queue in `dev/35_Author_Interview_Queue.md`.
2. Ask the highest-impact question or a small set of related questions.
3. Fold Joel's answer into the relevant reader-facing chapter or appendix.
4. Update `dev/HOW_JOEL_RESPONDS.md` whenever the answer reveals tone, phrasing, communication pattern, teaching priority, safety standard, or structure.
5. Update `dev/QUESTIONS_FOR_JOEL.md` by removing answered questions, refining partially answered questions, and adding new high-value follow-ups.
6. Update `dev/35_Author_Interview_Queue.md` so a fresh agent can see the next compact priorities quickly.
7. Update `dev/36_Draft_Status.md` with what changed, current gaps, counts, and next-pass priorities.
8. Update `dev/39_Manuscript_Style_Sheet.md` when a new term, concept rule, attribution, writing preference, or publication boundary appears.
9. Cross-reference related manuscript sections where continuity helps the reader connect concepts.
10. Validate against `C:\Code\Agents\requirements\WRITING_DOCUMENTS.md`.
11. Commit and push to `main` when Joel asks, or after a complete substantive pass if that is the standing direction.

## Writing Rules

Preserve Joel's voice: direct, concept-first, practical, analytical, and mat-tested. He does not want generic story-openings that are tied back to a point. He presents data, guides the reader through a narrative, and supports the conclusion along the way.

Avoid canned publication phrasing, especially generic `matters` bridge constructions. Avoid paragraph openings listed in `C:\Code\Agents\requirements\WRITING_DOCUMENTS.md` unless there is a specific reason. Avoid turning chapters into lists. Avoid generic AI transitions.

Use reader-facing obstacle language: `put things in the way` and `get things out of the way`.

Treat third-party song lyrics and similar copyrighted text carefully. Use only short attributed excerpts unless Joel obtains permission, and paraphrase the larger idea in Joel's own language.

Preserve attribution:

- Ron Keslar and American Kickboxing Academy: every belt and stripe, major lineage, likely foreword candidate.
- Rudy Sanchez and Smash Gyms: critically important to Joel's progression toward black belt; two-on-one concepts and side-control pin framework.
- Andrew Kerfoot and Nexus Jiu Jitsu: conceptual influence; strike zone attribution.
- Refuge Jiu Jitsu: current teaching home.

Do not document student-identifying safety incidents. For escalation or unsafe submissions, use abstract room standards: stop the round, get new partners, let heads cool down, respect the tap, apply slowly, and keep training partners safe.

## Repository Files

- `markdown/00_Title_Page.md`: reader-facing title page.
- `dev/00_Book_Outline.md`: structure, throughline, and tone.
- `markdown/01_Foreword.md` through `markdown/32_Acknowledgments.md`: main reader-facing manuscript.
- `markdown/33_Glossary.md`: shared vocabulary for recurring concepts.
- `markdown/34_Reader_Observation_Drills.md`: short mat-observation drills tied to the chapters.
- `dev/35_Author_Interview_Queue.md`: compact queue for future interview passes.
- `dev/36_Draft_Status.md`: current draft state, remaining gaps, counts, and next priorities.
- `dev/37_External_Context_Notes.md`: source-linked development notes for rule-set and safety questions.
- `dev/38_Manuscript_Map.md`: reader-facing order and development-file boundaries.
- `markdown/35_Rules_and_Safety_Note.md`: reader-facing appendix on ruleset variation and training safety.
- `dev/39_Manuscript_Style_Sheet.md`: voice, terminology, and revision rules for future ghostwriting passes.
- `dev/QUESTIONS_FOR_JOEL.md`: curated active interview queue for the highest-impact remaining gaps.
- `dev/HOW_JOEL_RESPONDS.md`: notes on Joel's voice, emphasis, phrasing, and response patterns.
- `dev/DEV_Feedback_and_Development_Notes.md`: development notes, scope risks, and future revision ideas.

## Pre-Commit Checks

Before ending a substantive pass, run checks for:

- Stale filenames and table-of-contents drift.
- Scaffold markers such as `Chapter Purpose`, `Points to Cover`, `Suggested Opening Draft`, or `[AUTHOR NOTE:`.
- Banned `matters` bridge constructions and generic paragraph openings from the writing requirements.
- Raw obstacle profanity in reader-facing prose.
- ASCII-only Markdown.
- Word/page count estimates.
- `git diff --check`.

Then commit with a clear message and push to `origin main`.
