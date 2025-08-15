# `<GitHubCallout />`

## Overview

This component mimics the undocumented way that GitHub renders callouts. https://github.com/orgs/community/discussions/16925

![GitHubCallout](callout.png)

It also supports dark mode:

![GitHubCallout dark mode](callout-dark.png)

## Usage

It supports five different types of callouts: `note`, `tip`, `important`, `warning`, and `caution`.

```jsx
<GitHubCallout type="note">
  This is a note!
</GitHubCallout>
```
