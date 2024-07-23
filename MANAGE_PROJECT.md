# Manage a GitHub Project

In this repository, [a GitHub Actions Workflow is run periodically](https://github.com/szksh-lab/.github/actions/workflows/update-project.yaml) to add GitHub Issues and Pull Requests of my OSS to [a GitHub Project](https://github.com/orgs/szksh-lab/projects/1) automatically.

- [Workflow](.github/workflows/update-project.yaml)
- [ghproj](https://github.com/suzuki-shunsuke/ghproj)
- [ghproj.yaml](ghproj.yaml)
- [GitHub Project](https://github.com/orgs/szksh-lab/projects/1)

## Blog Posts

- https://zenn.dev/shunsuke_suzuki/articles/add-github-issue-pr-to-project

## GitHub App

Permissions:

- `Repository permissions`: `metadata: read-only`
- `Organization permissions`: `Projects: Read and write`

Installed repositories:

- Only this repository
