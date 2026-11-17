---
name: linkedin-hook-writer
description: Write 10 scroll-stopping LinkedIn hooks (first 1–3 lines) for one topic, using patterns from top B2B creators. Use whenever a LinkedIn post needs an opening.
---

# LinkedIn Hook Writer

## Why this skill exists
LinkedIn shows about the first 140 characters before "…see more". If that click doesn't happen, nobody reads the rest of the post. Top creators (Justin Welsh, Jasmin Alić) often write the hook **last**, once they know what the post actually delivers.

## Inputs
- **Topic or draft:** what the post is about (a draft body is best).
- **ICP card** (from `linkedin-icp-definer`), or at least: who it's for and which pain it addresses.
- **Proof:** any real numbers, timeframes or results you can use.

## The rule
A hook is a **promise**. The body must keep it. Never write a hook the post can't deliver.

## 8 hook patterns (sourced from top creators)
| # | Pattern | Shape | Inspired by |
|---|---|---|---|
| 1 | **Dense credibility** | Result with real numbers + new challenge + open loop ending in ":" | Adam Robinson |
| 2 | **Story drop-in** | Start mid-scene: a specific moment, place, time | Lara Acosta, Dave Gerhardt |
| 3 | **Promise + rehook** | Line 1 = the promise. Lines 2–3 = why it matters / what's at stake | Jasmin Alić |
| 4 | **Contrarian** | "[Common belief] is wrong." + the reason in line 2 | Chris Walker |
| 5 | **Signposting** | How you know: "After [N] [things] I've learned…" | Jasmin Alić |
| 6 | **Specific list** | "[N] [things] that [specific outcome] in [timeframe]:" | Justin Welsh |
| 7 | **Before / after** | "[Month/Year]: [bad state]. Today: [good state]." | Common creator format |
| 8 | **Surprising fact** | A real stat or news item + "here's what it means for [ICP]" | Justin Welsh, Ruben Hassid |

Avoid "Have you ever wondered…?" questions. Data across 309K posts (Ordinal) shows story hooks outperforming question hooks.

## Process
1. Find the **one** thing the reader should take away. Write it as a single sentence.
2. Write 10 hooks using at least 6 different patterns from the table.
3. For each hook, check:
   - Under ~140 characters before the first line break?
   - Contains something **specific** (a number, a name, a timeframe)?
   - Speaks to the ICP's pain, not to "everyone"?
   - Does the body actually deliver on it?
4. Rank the top 3 and give a one-line reason for each.

## Output format
```
CORE TAKEAWAY: …

HOOKS
1. [pattern] …
…
10. [pattern] …

TOP 3
#… — why
#… — why
#… — why
```

## Don'ts
- No clickbait the body can't pay off. It kills trust, and trust is what turns readers into leads.
- No emoji walls, no ALL CAPS, no "🚨 BREAKING".
- No fake numbers. If you have no data, use a story hook instead.

## Hands off to
`linkedin-story-post` (if no body yet) or `linkedin-post-formatter` (if the body exists).
