# StatusPage

## Overview

A `<StatusPage />` can be used to embed the current operational status, health, or uptime of a service or system. It fetches live status information from a public [Statuspage](https://www.atlassian.com/software/statuspage) endpoint (e.g. https://www.githubstatus.com) and displays the status indicator and description.

<img src="status-page.png" width="800" />

## Usage

```mdx
<StatusPage title="ReadMe Status" url="https://www.readmestatus.com" />
```

## Props

| Prop    | Type   | Description                       |
| ------- | ------ | --------------------------------- |
| `title` | string | The heading displayed at the top. |
| `url`   | string | The URL of the status page.       |
