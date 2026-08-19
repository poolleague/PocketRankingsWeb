# AGENTS.md — PocketRankingsWeb

This repo inherits every rule in `PLATFORM_AGENTS.md`
(`PocketRankingsPlatform` repo). This file covers only what's specific to
Web.

## Scope of this product

- Marketing/landing pages, pricing page, and checkout UI.
- Calls Account for entitlement checks; never stores entitlement state
  itself.
- Checkout submits through `IPaymentProvider`
  (PLATFORM_AGENTS.md Section 4) — today, a no-op implementation per
  Section 3's beta-included-access policy.

## Explicitly out of scope here

- No real payment processing until a live provider is explicitly approved
  (PLATFORM_AGENTS.md Sections 4 and 8).
- No League/Tournament/Player Profile domain logic — Web only links out to
  those products once entitlement is confirmed.

## Status

Scaffolding only. No controllers/services/models implemented yet — real
implementation starts next session, per owner approval, per
PLATFORM_AGENTS.md Section 8 (Approval Boundaries).
