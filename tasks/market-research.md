# Market Research Task

This is the market-research portion of the plan, run as a scheduled task at
8am (see `.github/workflows/market-research.yml`). It is the prompt that drives
the scheduled run, and the spec for what that run should produce.

> Configure the scope below before the first scheduled run. The placeholders in
> **Scope** are intentionally generic because the target product/market was not
> specified when this task was created.

## Scope

- **Product / area under research:** _<fill in: what are we researching?>_
- **Target market / segment:** _<fill in: who is the customer?>_
- **Geography:** _<fill in, or "global">_

## Objectives

1. **Market size & growth** — estimate TAM/SAM/SOM and recent growth trend,
   with sources and dates.
2. **Competitive landscape** — identify the main competitors, their
   positioning, pricing, and notable strengths/weaknesses.
3. **Customer needs & gaps** — summarize the top unmet needs or pain points
   in the segment.
4. **Trends & signals** — call out recent shifts (regulatory, technological,
   demand) that affect the opportunity.
5. **Recommendation** — a short, opinionated take on where the opening is.

## Method

- Use up-to-date web sources; prefer primary sources and recent reports.
- Cite every non-obvious claim with a link and a date.
- Flag low-confidence figures explicitly rather than presenting them as fact.

## Output

Write the findings to `research/market-research-<YYYY-MM-DD>.md` and open a pull
request (or an issue, if PRs are not desired) summarizing the key takeaways so
the result is reviewable.
