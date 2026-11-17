---
name: linkedin-icp-definer
description: Turn an offer into a sharp Ideal Customer Profile and 3 pain points for LinkedIn content. Use first, before writing any post; every other LinkedIn skill takes its output as input.
---

# LinkedIn ICP Definer

## Why this skill exists
Copying a top creator's style gets reach. **Leads** come from talking to one specific buyer about one specific problem. This skill pins that buyer down before you write anything.

## Inputs (ask for any that are missing, max 3 questions)
1. **Offer:** what you sell, in one sentence.
2. **Best customers so far:** 1–3 real examples (role, company size, industry). If there are none, say "hypothesis".
3. **Price point / sales cycle:** rough is fine.

## Process
1. **Who signs the cheque?** Name one job title and one company type. If the user lists more than two, push back and ask which one pays the most and buys the fastest.
2. **Trigger events:** list 3 moments when this person starts looking for a solution (e.g. "new CMO hired", "missed Q3 pipeline target").
3. **Pain points:** write 3, each in the buyer's own words, as a sentence they'd say to a colleague. No jargon.
4. **Desired outcome:** what "solved" looks like to them, with a number if possible.
5. **Objections:** the top 2 reasons they'd say no.
6. **Content angles:** for each pain point, 2 post ideas: one story, one lesson.

## Output format
```
ICP CARD
Buyer: [title] at [company type, size, market]
Triggers: 1) … 2) … 3) …
Pains (their words):
  P1: "…"
  P2: "…"
  P3: "…"
Outcome they want: …
Top objections: 1) … 2) …
Content angles:
  P1 → Story: … | Lesson: …
  P2 → Story: … | Lesson: …
  P3 → Story: … | Lesson: …
Soft CTA idea: [one low-friction next step, e.g. free checklist, 15-min audit]
```

## Quality bar
- A stranger can read the card and name a real person who fits it.
- Each pain is concrete enough to be a post hook on its own.
- If the offer is too broad ("we help companies grow"), stop and say so before filling in the card.

## Hands off to
`linkedin-hook-writer` → `linkedin-story-post` → `linkedin-post-formatter`
