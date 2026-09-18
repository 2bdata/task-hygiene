---
name: task-hygiene-review-loop
description: Review sessions; codify failed-then-fixed tasks as skills.
---

# Task Hygiene & Skill Codification (Review Loop)

## When to load this
After reviewing sessions over the last ~24hrs, or when a task repeatedly failed initially then worked using another method.

## The review loop (session_search)
1. Run session_search for tasks in the last ~24hrs that failed at first but eventually succeeded via an alternate approach.
2. Identify the working method — what changed between the failure and the success.
3. Codify it: create a new skill, or patch an existing one with the fix.

## Codification rules
- Capture the exact command/config/sequence that worked (not just "it worked").
- Note why the first attempt failed — this prevents re-failing next time.
- Keep entries terse; the skill is a lookup, not a log.

## Updated 2026-09-18
