# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository holds public-facing **privacy policy documents** for apps published by **Spectrum Works** (contact: developer@tkb.us). There is no application code, build system, or test suite.

## Documents

- `LOADOUT_privacy_policy.md` — Privacy policy for LOADOUT, a firearm maintenance and ammo inventory tracking app. Uses Supabase for optional cloud sync/auth; otherwise fully local (SQLite). Effective April 12, 2026.
- `PRISM_privacy_policy.md` — Privacy policy for Prism, a visual clock app for neurodivergent children (ages 4–12). No data collection; fully local storage; COPPA/GDPR compliant. Effective April 12, 2026.

## Key Constraints When Editing

- **LOADOUT** collects user-entered data and optionally syncs to Supabase. Any edits must accurately reflect what the app actually does — do not add or remove data types without confirming with the developer.
- **PRISM** is a children's app (COPPA/GDPR applies). Privacy claims are strong ("no personal information collected") — any weakening of those claims requires careful legal consideration.
- Both policies state that continued use after policy changes constitutes acceptance. Update the `Effective Date` / `Last Updated` fields whenever material changes are made.
- Third-party service tables (LOADOUT) and third-party sections (PRISM) must stay in sync with the actual SDKs/services used in the respective apps.
