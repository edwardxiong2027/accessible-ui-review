---
name: accessible-ui-review
description: Review an interface for practical accessibility problems and turn them into reproducible fixes. Use when: Before shipping a page, component, or generated UI.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Accessible UI Review

Review an interface for practical accessibility problems and turn them into reproducible fixes.

## When to use

Before shipping a page, component, or generated UI.

## Workflow

1. Inspect keyboard use, focus order, names, and contrast.
2. Test narrow screens and zoom.
3. Report the exact element and impact.
4. Suggest the smallest semantic fix and retest.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Review [page/component] for usability and accessibility. Inspect semantic structure, keyboard navigation, visible focus, accessible names, contrast, motion, error feedback, and small-screen behavior. For each issue report: location, user impact, steps to reproduce, severity, and smallest recommended fix. Separate observed defects from guesses. Do not claim WCAG conformance without checking the relevant criteria. If code is available, make only scoped fixes and report how each was verified.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
