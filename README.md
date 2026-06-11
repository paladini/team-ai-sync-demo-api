# team-ai-sync demo API

This public repository is a target in the public
[`team-ai-sync`](https://github.com/paladini/team-ai-sync) demonstration.

It represents an API repository that started with stale AI guidance and then
received synchronized files from
[team-ai-sync-demo-source](https://github.com/paladini/team-ai-sync-demo-source).

## Demo context

- [team-ai-sync](https://github.com/paladini/team-ai-sync) provides the GitHub
  Action.
- [team-ai-sync-demo-source](https://github.com/paladini/team-ai-sync-demo-source)
  stores the shared `AGENTS.md`, `CLAUDE.md`, `.editorconfig`, instructions,
  prompts, and `sync-config.json`.
- [team-ai-sync-demo-web](https://github.com/paladini/team-ai-sync-demo-web)
  is the second target repository in the same demo.

## Sync result

The Action opened and updated
[API pull request #1](https://github.com/paladini/team-ai-sync-demo-api/pull/1),
which synchronized the shared team guidance into this repository.

The final verification run in the source repository reported no remaining
changes:
[final dry run](https://github.com/paladini/team-ai-sync-demo-source/actions/runs/27316035674).
