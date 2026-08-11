# TTT

Stub repo. Scope not yet decided.

## Background

"Tyler Teaches Typing" started as a bit — a blog post written as a real NORTHSTAR document "for
a product that does not exist and — on current evidence — cannot exist" (`okemily.com/blog/
tyler-teaches-typing/`, 2026-07-25). The founder promoted it to a real feature request
(2026-08-09): *"can we find the northstar for tyler teaches typing in the blog posts and promote
it to a real northstar in shankpit we want to convert the cave option on the shankpit menu that
does some cool typing on the screen - we want to actually have that be mvp vs0 of tyler teaches
typing."*

The actual VS0 implementation lives in **SHANKPIT**, not here:
`SHANKPIT/docs2/NORTHSTAR_TYLER_TEACHES_TYPING.md` has the full design, and
`SHANKPIT/packages/simulation/typing_lesson.h`/`.c` has the real, working logic layer (state
machine, WPM/accuracy calc, a 13-line slide table sourced verbatim from `TYLER/episodes/`
dialogue) as of 2026-08-11 — see that repo's own CLAUDE.md and NORTHSTAR doc.

This repo (`TTT`) exists on GitHub (`emilyspringerton/TTT`) but its own purpose relative to
SHANKPIT's implementation hasn't been given real founder direction yet — same "stub only, more
direction to follow" status `CarePyre` had when it was created. Not assumed to be a code home,
a marketing/landing-page repo, or anything else without that direction landing first.

## Related

- `SHANKPIT` — where the real VS0 implementation actually lives
- `TYLER` — the source dialogue every lesson line traces back to
