# LinkedIn Micro-Skills 🇬🇧 🇸🇪

Small, single-purpose AI skills for writing LinkedIn content that brings in **B2B leads**, not just likes. They're based on research into 10 top LinkedIn creators (see [`research/top-10-creators.md`](research/top-10-creators.md)).

Each skill is a plain Markdown prompt. It works as a Claude skill (`SKILL.md`), and you can also paste it into ChatGPT, Gemini or any other AI tool.

## The chain

```
01 ICP definer  →  04 Story post  →  02 Hook writer  →  03 Post formatter  →  publish
   (who + pain)     (the body)        (the opening)      (polish + CTA)
```

Run **01** once per offer and reuse its ICP card for every post.

| # | English | Svenska | Does one thing |
|---|---|---|---|
| 01 | [`linkedin-icp-definer`](en/01-icp-definer/SKILL.md) | [`linkedin-icp-definierare`](sv/01-icp-definierare/SKILL.md) | Offer → buyer, triggers, 3 pains, content angles |
| 02 | [`linkedin-hook-writer`](en/02-hook-writer/SKILL.md) | [`linkedin-krokskrivare`](sv/02-krokskrivare/SKILL.md) | 10 hooks from 8 proven patterns, top 3 ranked |
| 03 | [`linkedin-post-formatter`](en/03-post-formatter/SKILL.md) | [`linkedin-inlaggsformaterare`](sv/03-inlaggsformaterare/SKILL.md) | Draft → scannable mobile post + one CTA |
| 04 | [`linkedin-story-post`](en/04-story-post/SKILL.md) | [`linkedin-berattelseinlagg`](sv/04-berattelseinlagg/SKILL.md) | Real experience → Story/Lesson/Steps/You + bridge to offer |

The Swedish versions are **adapted, not just translated**. They use a more *lagom* tone, no American-style hype, and include a Swedish language check.

## How to use

**Claude (Claude.ai / Claude Code):** copy a skill folder into your skills directory, or upload it as a skill. Claude loads it automatically when the description matches the task.

**Any other AI tool:** open `SKILL.md`, copy everything below the `---` front matter, paste it as your first message (or as custom instructions), then give your inputs.

## Principles baked into every skill

1. **One idea per post.**
2. **Never invent stories, clients or numbers.**
3. **No links in the post body.** Put them in the first comment.
4. **One CTA, soft by default.**
5. **Write the hook last.**

## Roadmap (not built yet)

- `linkedin-lead-magnet-cta`: comment/DM funnels and lead magnets
- `linkedin-carousel-outliner`: 6–10 slide carousel structures
- `linkedin-comment-strategy`: value-adding comments for reach (Daniel Murray's comment-first approach)
- `linkedin-profile-optimizer`: headline, About and Featured sections that convert profile visits

See [`NOTES.md`](NOTES.md) for the decision log.
