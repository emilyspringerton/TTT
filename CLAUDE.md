# TTT

## What this is

Stub repo — see `README.md` for the real background. The actual "Tyler Teaches Typing" VS0
implementation lives in `SHANKPIT` (`docs2/NORTHSTAR_TYLER_TEACHES_TYPING.md`,
`packages/simulation/typing_lesson.h`/`.c`), not here. This repo's own purpose hasn't been given
real founder direction yet — don't assume scope or stack, same posture `CarePyre`'s own CLAUDE.md
took when it was a stub.

## Related Repos

- `SHANKPIT` — the real VS0 implementation
- `TYLER` — source dialogue

## Founder Real-Time Direction

Whenever the founder gives real-time direction — a new ask, a correction, a "can we also..." —
route it through `emily observe -s info "Founder real-time: <summary>"` first, even if it isn't
this repo's usual domain, then sprint-plan it into `EMILY/BACKLOG.md` (`emily backlog curate`,
scoped into a real SECTION/sub-item, not just a one-line log), and only then implement. See
`EMILY/docs/THE_EMILY_WAY.md` Principle 18 ("Pave the Cow Paths").

## Commit Protocol (standing instruction)

Always commit and push completed work immediately — don't wait to be asked. This is the default for every repo in this monorepo.

Every commit — human-written or produced by automated code paths (git-commit helpers in emily-agent, emily.cli, IDUNA handlers, etc.) — must carry the active `emily session` fingerprint as a `session: <tag>` trailer (blank line, then the trailer). This was silently missing from several independently-implemented automated commit helpers across the monorepo until an audit on 2026-08-10 (founder, real-time: "where in the fuck is my llm session id anywhere"). If you add a new automated git-commit code path anywhere, wire in the session tag the same way — don't assume an existing helper already does it.
