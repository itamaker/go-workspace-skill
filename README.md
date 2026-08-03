# go-workspace-skill

Standalone agent skill for configurable multi-repo Go workspaces.

This repository is structured for the open `skills` installer ecosystem and contains a single skill: `go-workspace-skill`.

## Install

```bash
npx skills add itamaker/go-workspace-skill
```

## Repository Layout

```text
skills/
  go-workspace-skill/
    SKILL.md
    agents/
    assets/
    references/
    scripts/
```

## Usage Examples

- `Use $go-workspace-skill to sync all repos in this workspace.`
- `Use $go-workspace-skill to pull only skillforge and runlens.`
- `Use $go-workspace-skill to build the workspace.`
- `Use $go-workspace-skill to run workspace tests.`
- `Use $go-workspace-skill to list which repos are Go projects.`
- `Use $go-workspace-skill to create a workspace config for this repo set.`

## License

[MIT](./LICENSE)
