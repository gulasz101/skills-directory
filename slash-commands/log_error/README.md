# log_error slash command

Portable slash-command package for:

- Claude Code
- Codex
- OpenCode

## Credit

Original author/source: https://docs.google.com/document/d/1I9r21TyQuAO1y2ecztBU0PSCpjHSL_vZJiA5v276Wro/edit?tab=t.0

## Canonical prompt

Use `COMMAND.md` as the source of truth.

## Suggested pathing per tool

- Claude Code: install as `/log-error` command from `COMMAND.md`
- Codex: map your custom slash command to `COMMAND.md`
- OpenCode: map your custom slash command to `COMMAND.md`

## Logging output target

The command expects:

- `~/errors/error-XXX.md`
- `~/metadata.json`

Create these under your home directory when using the command.
