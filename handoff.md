# Handoff Reference

This repo follows the shared workflow documented at the websites root.

- Master session notes: `../handoff/SESSION_NOTES.md`
- Co-dev reminders: `../REMINDER.md`

## Site-Specific Notes

- [ ] Confirm `www.austinbjohnson.com` serves the GitHub Pages build over HTTPS and update docs once the alias resolves. (2025-10-07 04:31 UTC: still serves Squarespace 404.)
- [ ] Investigate the Firefox redirect loop (likely leftover Squarespace redirect vs. apex records) and document the fix. Apex `austinbjohnson.com` continues to 301 toward the Squarespace-backed `www` host.
- [ ] Simplify the homepage footprint—remove contact CTA, add Strava/Goodreads placeholders, and propose two additional lightweight modules (e.g., Now, automation lab notes).
- [ ] Once placeholders exist, wire them to live Strava/Goodreads data feeds as automation endpoints become available.
