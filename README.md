# Pocket Rankings — Web

Public marketing site and paywall for the Pocket Rankings platform. This
is the front door: pricing, plan info, and checkout, gating access to
League, Tournament, and Player Profile.

Checkout is real UI wired to a real code path, but currently terminates in
a no-op payment provider — see `PocketRankingsPlatform/PLATFORM_AGENTS.md`
Section 4. No live charges happen from this repo today.

## Structure

Matches `PoolLeagueWeb`'s layout: the actual project lives under
`src/PocketRankingsWeb/`, with `docs/` and `tests/` at repo root.

## Status

Scaffolding only — no runtime code yet. See `AGENTS.md` for repo-specific
rules; platform-wide rules live in `PocketRankingsPlatform`.
