# `<PostList/>`

## Overview

Fetch and display a list of posts from an API endpoint with a loading indicator while fetching and handles errors. Ideal for demonstrating async data fetching with React hooks and Tailwind CSS styling.

## Usage

| Prop | Type   | Required | Default                                                     | Description                     |
|------|--------|----------|-------------------------------------------------------------|---------------------------------|
| `url`  | string | No       | https://jsonplaceholder.typicode.com/posts?_limit=5    | API endpoint to fetch posts from |

```jsx
<PostList url="https://your.api.com/posts?limit=10" />
