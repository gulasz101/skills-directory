# AGENTS.md

## Commit requirements

Every commit in this repository MUST include:

1. Model used for the commit (for example: `gpt-5-codex`, `claude-sonnet-4`, etc.)
2. CLI/tool used for the commit (for example: `codex`, `claude code`, `opencode`)

Required commit message footer format:

```
Model: <model-name>
CLI: <tool-name>
Plan: <plan-file-path-or-N/A>
Plan-Commit: <commit-sha-or-N/A>
```

## Plan and commit linkage

If a plan file exists for work:

- The commit MUST reference the plan file path in the `Plan:` footer.
- The plan file MUST include a `Commit:` line with the exact commit SHA.

This two-way linkage is required so plan review can jump directly to the browser commit page.

## Plan file convention

Store plans in `docs/plans/` and include at minimum:

- `Title`
- `Date`
- `Scope`
- `Steps`
- `Commit: <sha>` (filled after commit)
