# Renovate config

Shared defaults for a detailed Dependency Dashboard: individual updates,
dependency inventory, warnings, vulnerability summaries, and stale packages.
No automatic update branches or PRs; automerge is disabled.

Add `renovate.json` to each repository's default branch, then enable
[Renovate](https://github.com/apps/renovate) and Issues:

```json
{
  "extends": ["github>vladleesi/renovate-config"]
}
```

Leave dashboard action checkboxes unchecked: selecting one can request a branch
or PR. The hosted app retains write permissions and may maintain existing branches.
Local settings can override this preset.

OSV summaries cover direct dependencies and are experimental. Enable Dependency
graph and Dependabot alerts for GitHub vulnerability reporting.

[MIT License](LICENSE).
