# `<Grid/>`

## Overview

Organize content into a grid layout for structured layouts

<img src="grid.png" width="800" />

## Usage

```mdx
<Grid columns={2} gap="20px">
  <div>item one</div>
  <div>item two</div>
  <div>item three</div>
  <div>item four</div>
</Grid>
```

## Props

| Prop       | Type   | Default | Description                                                        |
| ---------- | ------ | ------- | ------------------------------------------------------------------ |
| `columns`  | number | `2`     | Number of columns in the grid (minimum 2).                         |
| `children` | node   |         | Content to render inside the grid.                                 |
| `gap`      | string |         | Gap between all grid items (sets both row and column gap).         |
| `gapX`     | string |         | Column gap. Falls back to `gap` if not provided.                   |
| `gapY`     | string |         | Row gap. Falls back to `gap` if not provided.                      |
| `padding`  | string |         | Padding around the entire grid.                                    |
| `paddingX` | string |         | Left and right padding. Overrides `padding` on the horizontal axis.|
| `paddingY` | string |         | Top and bottom padding. Overrides `padding` on the vertical axis.  |
| `style`    | object |         | Additional inline styles applied to the grid container.            |
