# painpoint-public — public external mirror of 痛點科技

This repo is the **public, read-only mirror** of the externally-shareable content from `痛點科技` (Pain Point Technologies (B2B AI agency)).

## What's here

Markdown pages that the 痛點科技 team has explicitly tagged `audience: external` and (where applicable) cleared via cultural-review processes. This is the canonical source of truth for any read-only AI agent serving customer-facing roles.

## What's NOT here

- Internal operational data — sales pipeline, MEDDPICC fields, deal sizes, contact details
- NDA-flagged or confidential content
- Personal information about the owner or team members
- Contact attendees, internal emails, calendar metadata
- Any frontmatter fields that could leak workflow internals — they're stripped before publication

If something is not here, it was not approved for external visibility. **Do not infer or speculate about its contents.**

## How this repo updates

A daily automated job (`external-publish.py` in `AlexChanshuo/alexmind-ops`, fired by `launchd` at ~04:11 Asia/Taipei) syncs `wiki/external/` from the private vault to this mirror, scrubbing internal frontmatter fields and enforcing cultural-review gates. Direct edits to this repo will be overwritten on the next sync.

## For agents using this content

A portable agent skill describing how to read this content properly is at `_ops/agent-skills/external-readonly-skill.template.md` in `AlexChanshuo/alexmind-ops`. Generate a customized skill via `_ops/generate-skill.sh` and install it as your operating instructions.

## Last sync

- Synced at: 2026-07-16T20:24:00Z
- Pages published: 0
- Pages unchanged: 0
- Pages blocked (failed publication gates): 0
- Pages deleted (removed from vault since last sync): 0
