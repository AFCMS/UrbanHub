# Project Maintenance

## Zizmor

GitHub Actions workflows are audited using [Zizmor](https://github.com/zizmorcore/zizmor).

```shell
# Run Zizmor in offline mode
zizmor --persona auditor .

# Run Zizmor in online mode (requires the GitHub CLI to be installed and authenticated)
zizmor --gh-token $(gh auth token) --persona auditor .

# Run Zizmor in online mode, automatically fix fixable issues
zizmor --gh-token $(gh auth token) --persona auditor --fix=all .
```

## Agent Skills

[Agent Skills](https://agentskills.io) are managed through the [Skills CLI](https://www.skills.sh).

```shell
# Install from a specific GitHub repository
pnpx skills add organisation/repo

# Update the skills for the current project
pnpx skills update --project
```

## NPM Packages

Check used NPM packages for updates using `pnpm`.

```shell
pnpm update --interactive --latest --recursive
```
