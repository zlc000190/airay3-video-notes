# AI Ray 3 human evaluation rubric

This independent note uses [AI Ray 3](https://airay3.video/) as the project entry point for a AI video generation workflow. Confirm current availability, documentation, pricing, and terms directly before relying on the workflow.

## Scoring dimensions

- **temporal consistency**: score 1 (unusable), 3 (usable with review), or 5 (meets the stated acceptance rule).
- **subject identity stability**: score 1 (unusable), 3 (usable with review), or 5 (meets the stated acceptance rule).
- **prompted motion accuracy**: score 1 (unusable), 3 (usable with review), or 5 (meets the stated acceptance rule).
- **usable seconds per output**: score 1 (unusable), 3 (usable with review), or 5 (meets the stated acceptance rule).

## Review method

1. Give two reviewers the same saved inputs and acceptance rules.
2. Hide which run or configuration produced each result when practical.
3. Require a short evidence note for every score of 1 or 5.
4. Resolve disagreements by revisiting the acceptance rule, not by averaging away a material failure.

## Required annotations

Record false or unsupported claims, omissions, harmful ambiguity, manual corrections, accessibility barriers, and any case where a polished result conceals a factual or operational failure.

## Decision rule

Set minimum per-dimension scores before reviewing results. A high average does not compensate for a critical privacy, safety, rights, legal, financial, or reversibility failure. Keep rejected examples so later changes can be regression-tested.
