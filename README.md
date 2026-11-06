# GAAD: GenAI Assisted Development

A project template for developing software with coding agents. People and agents follow the same workflow: a spec by example, append-only decisions, small plans, and tests first with a checkpoint before each commit.

## Use it

```sh
cp -a template/. <repo>/
```

Then run the `/start-a-project` in your agent, or follow `docs/workflow/start-a-project.md` to fill in any placeholders like `{{Project}}` in the template.

## What's in it

- `README.md`: why, who and what, with the roles and domain entities
- `CONTRIBUTING.md`: the working agreement
- `AGENTS.md` (and `CLAUDE.md`): extra rules for coding agents
- `docs/spec/`: the specification for the software
- `docs/decisions.md`: why things are the way they are (append-only)
- `docs/plans/`: the backlog, including specific plans for implementing features/slices
- `docs/workflow/`: documentation of the development process
- `.agents/skills/`: a markdown file for steps in the development process, symlinked as `.claude/skills`
- `.claude/agents/reviewer.md`: a read-only reviewer agent
