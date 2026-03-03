# log_error slash command

Portable slash-command package for:

- Claude Code
- Codex
- OpenCode

## Canonical prompt

Use `COMMAND.md` as the source of truth.

## Suggested pathing per tool

- Claude Code: install as `/log-error` command from `COMMAND.md`
- Codex: map your custom slash command to `COMMAND.md`
- OpenCode: map your custom slash command to `COMMAND.md`

## Logging output target

The command expects:

- `/errors/error-XXX.md`
- `/metadata.json`

Create these in your active project when using the command.
