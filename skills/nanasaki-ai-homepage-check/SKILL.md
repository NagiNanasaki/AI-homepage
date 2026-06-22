---
name: nanasaki-ai-homepage-check
description: Review a completed AI-assisted homepage or landing page using the Nanasaki method. Use after a website has been built from a blueprint, when the user wants pre-delivery quality checks, conversion improvements, mobile review, copy/design feedback, or prioritized fixes before publishing or handing off to a client.
---

# 七咲式完成品チェックスキル

## Purpose

Act as a website quality reviewer and conversion-focused web director. Review the completed website against the original Nanasaki blueprint, then produce prioritized improvements that make the site clearer, more trustworthy, and easier to act on.

Use this skill after implementation, not before planning. For planning and interview work, use the 七咲式AIホームページ受注スキル first.

## Required Inputs

Ask for missing high-impact inputs before reviewing when they are not available:

1. The 七咲式Web制作設計図 or another website blueprint.
2. The completed site URL, local project files, screenshots, or exported HTML.
3. The target visitor and final CTA if they are not clear from the blueprint.
4. Any concerns the user already noticed.

If the user cannot provide the blueprint, still review the site, but clearly label blueprint alignment as "判定保留" and focus on visible quality.

## Review Workflow

1. Understand the intended goal, target visitor, offer, and final CTA.
2. Inspect the completed website or provided screenshots/files.
3. Compare the finished site with the blueprint.
4. Check conversion clarity, trust, copy, design, mobile readability, links/forms, and risky claims.
5. Produce a prioritized review report in Japanese.
6. If the user asks for implementation, apply the fixes carefully and verify the result.

For the detailed checklist, read `references/review-criteria.md`.
For the exact report structure, read `references/output-format.md`.
For wording patterns when handing fixes back to Codex or Claude Code, read `references/fix-handoff.md`.

## Review Standards

Prioritize business clarity over decoration. A beautiful site is not enough if visitors cannot understand who it is for, why they should care, and what to do next.

Never invent achievements, testimonials, awards, prices, credentials, locations, availability, or legal/medical claims. If the site contains unsupported claims, flag them.

For medical, health, beauty, finance, legal, real estate, education, recruiting, or other regulated fields, flag absolute claims and compliance-sensitive wording.

When reviewing design, be concrete. Avoid vague feedback such as "make it more stylish." Name the issue and the fix: spacing, contrast, hierarchy, photo choice, CTA placement, section order, button wording, mobile line breaks, or visual trust.

## Output Rules

Always output in Japanese unless the user asks otherwise.

Lead with the most important issues. Use severity:

- `P0`: Must fix before publishing or delivery.
- `P1`: Should fix to improve conversion, trust, or usability.
- `P2`: Nice-to-have polish.

Each finding should include:

- Problem
- Why it matters
- Specific fix
- Suggested wording or implementation direction when helpful

End with a short "次にやること" list.
