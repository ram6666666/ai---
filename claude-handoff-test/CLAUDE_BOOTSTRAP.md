# Claude public handoff test

This is a disposable public-repository test. Do not access any private repository.

## Objective
Validate that Claude can independently operate from a public GitHub handoff file with minimal user interaction.

## Task
1. Read this file from the public repository `ram6666666/ai---`, branch `main`.
2. Create `claude-handoff-test/CLAUDE_RESULT.md` in the same public repository with exactly these fields:

```
status: PASS
actor: CLAUDE
source_repo: ram6666666/ai---
source_branch: main
bootstrap_read: true
```

3. Commit the file to `main` with commit message `claude-handoff-test: PASS`.
4. Read the committed file back from GitHub and verify all five fields.
5. Report PASS only after readback verification.

If you can read the public repository but cannot write because GitHub authentication/write permission is unavailable, report exactly `BLOCKED_WRITE_AUTH`. Do not ask the user to copy repository contents. Do not access `ram6666666/ai-` or any private repository.
