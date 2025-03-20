# `GitHubBadge`

## Overview

This component displays a badge that links to a GitHub actions workflow status. It is useful for showing the status of a CI/CD pipeline or other automated workflows.

## Usage

The `GitHubBadge` component accepts the following props:

- `owner` (string, required): The GitHub username or organization name that owns the repository.
- `repo` (string, required): The repository name where workflow is located.
- `workflow` (string, required): The name of the workflow file (e.g., `ci.yml`, `release.yml`).
- `branch` (string, default: "main"): The branch name to display the badge for.

```jsx
<GitHubBadge owner='readmeio' repo='rdme' workflow='release.yml' branch='main' />
```
