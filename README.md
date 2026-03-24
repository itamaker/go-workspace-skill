# go-workspace-skills

Standalone agent skill for configurable multi-repo Go workspaces.

This repository is structured for the open `skills` installer ecosystem and contains a single skill: `go-workspace-skills`.

## Install

```bash
# List skills in this repository
npx skills add itamaker/go-workspace-skills --list

# Install the skill
npx skills add itamaker/go-workspace-skills --skill go-workspace-skills
```

## Repository Layout

```text
skills/
  go-workspace-skills/
    SKILL.md
    agents/
    assets/
    references/
    scripts/
```

## Usage Examples

- `Use $go-workspace-skills to sync all repos in this workspace.`
- `Use $go-workspace-skills to pull only skillforge and runlens.`
- `Use $go-workspace-skills to build the workspace.`
- `Use $go-workspace-skills to run workspace tests.`
- `Use $go-workspace-skills to create a workspace config for this repo set.`

## License

[MIT](./LICENSE)
