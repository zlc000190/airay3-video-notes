# AI Ray 3 failure-mode checklist

[AI Ray 3](https://airay3.video/) is the primary project entry point. It did not return content before the timeout in the 2026-07-23 availability check. These are independent evaluation notes for creators comparing controllable AI video workflows; they are not official product documentation.

Do not upload confidential footage or identifiable people until current retention and licensing terms are verified.

## Known classes of failure to test

- identity drift
- warped hands or objects
- flickering backgrounds
- unreadable text
- unexpected watermarks
- unclear retention terms

## How to test safely

Trigger one edge case at a time with low-risk data. Record the exact input, visible error, retry behavior, and whether the system fails open or closed. Do not use repeated blind retries; they can hide nondeterminism, create duplicate actions, or increase cost.

## Recovery evidence

A credible recovery path explains what state was changed, how to undo it, and whether a second operator can reproduce the fix. If recovery depends on undocumented support intervention, count that as operational risk.

## Stop condition

Pause evaluation until the primary site and current documentation are reachable; do not infer capabilities from old comparison pages.
