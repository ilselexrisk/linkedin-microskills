# Project notes & decision log

## Status
**v0.1, 2026-11-17:** first 4 skills shipped in EN + SV, plus research on 10 creators.

## Decisions
| Date | Decision | Why |
|---|---|---|
| 2026-11-17 | Rank creators by B2B lead-gen relevance, not follower count | Follower lists are full of celebrity CEOs whose style can't be copied |
| 2026-11-17 | Skills are generic Markdown prompts with SKILL.md front matter | Works in Claude and can be pasted into any other AI tool |
| 2026-11-17 | Skills are not tied to a specific offer | Requested by Ilse; the ICP definer captures the offer at run time |
| 2026-11-17 | Two parallel folders `en/` and `sv/` | One version per language, as requested. Swedish is adapted for tone |
| 2026-11-17 | Ship 4 skills first (ICP, hooks, formatter, story) | Smaller MVP: use them, then expand |
| 2026-11-17 | Lead CTA folded into formatter + story post | The separate lead-magnet skill was deferred; leads still need a CTA path |
| 2026-11-17 | Soft CTA by default; comment-gating only on request | Top creators disagree on gating; soft CTAs are safer for trust |
| 2026-11-17 | Research file in English only | Reference material, not a skill; can translate later if needed |
| 2026-11-17 | Repo created **private** | Safer default; can be made public in one click |

## Open items
- [ ] Test the full chain on one real offer and story, then tune the skills
- [ ] Decide on the next skill to add (suggestion: `linkedin-lead-magnet-cta`)
- [ ] Revisit the research in ~6 months, since algorithm data changes every year
