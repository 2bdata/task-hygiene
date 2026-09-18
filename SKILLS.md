# Shared Skills

## task-hygiene-review-loop
Review sessions over last 24hrs; codify tasks that failed initially then worked via another method.
- Session: 20260917_170609_7bf2a258 — memory-hygiene skill was created but the batch rename to task-hygiene FAILED because skill_manage can't patch a non-existent name in one atomic call. Working method: write_file the new SKILL.md directly, then delete old + create new via separate skill_manage calls (delete must be sole op).
