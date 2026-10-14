# .github

Shared defaults for every repository in this organisation. GitHub uses these files in any repo
that does not have its own:

| File | What it does |
| --- | --- |
| `.github/pull_request_template.md` | Pre-fills every new pull request, starting with a `Closes #` line that links it to its ticket. |
| `.github/ISSUE_TEMPLATE/` | The **Task** and **Bug** forms offered when someone opens a new issue. |
| `CONTRIBUTING.md` | How work moves from a ticket to a merged change. Linked from every repo's "New issue" and "New pull request" pages. |

A repo that needs something different adds its own file of the same name, which takes precedence.

This repository is public because GitHub requires it for organisation-wide defaults. It holds
templates only. Nothing here is client data or configuration.
