# Task Hygiene & Skill Codification

Review your recent sessions and codify tasks that **failed initially then worked using another method**. This turns recurring discoveries into durable skills so you don't re-fail the same way next time.

## The review loop (session_search)

1. Run `session_search` for tasks in the last ~24hrs that failed at first but eventually succeeded via an alternate approach.
2. Identify the working method — what changed between the failure and the success.
3. Codify it: create a new skill, or patch an existing one with the fix.

## Codification rules

- Capture the exact command/config/sequence that worked (not just "it worked").
- Note why the first attempt failed — this prevents re-failing next time.
- Keep entries terse; the skill is a lookup, not a log.

## Example: Job 8 backup script pitfall → fix

**First attempt:** GNU tar under MSYS on Windows paths fails with `tar (child): Cannot connect to C: resolve failed` / exit code 2.

**Working method:** Switch to Python's `tarfile` module, which handles native Windows paths correctly without MSYS path translation. See the memory+skills backup repo for the full script.

## Directory layout

- This README documents the review loop and codification workflow.
- Related scripts live in the companion **memory+skills-backup** repo (`repo-memory-skills-backup/`).
