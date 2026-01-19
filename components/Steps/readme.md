# `<Steps/>`

## Overview

A step-by-step guide component with numbered steps, vertical connecting lines, and copy-to-clipboard functionality for step links. Each step can be individually linked and appears in the table of contents. Great for tutorials, quickstart guides, and sequential instructions.

## Usage

```mdx
<Steps name="quickstart">
  <Step number={1} title="Create an API key">
    Sign up for an Acme account and navigate to your API settings to generate a new API key.
  </Step>

  <Step number={2} title="Authenticate your request">
    Include your API key in the Authorization header of your requests.
  </Step>

  <Step number={3} title="Make your first API call">
    You're all set! Start making requests to the Acme API.
  </Step>
</Steps>
```

## Props

### `Steps`
| Prop           | Type   | Description                                                      |
| -------------- | ------ | -----------------------------------------------------------------|
| `name`         | string | Unique identifier for this steps instance, used for step IDs. Default: `"steps"`. |

### `Step`
| Prop           | Type   | Description                                                      |
| -------------- | ------ | -----------------------------------------------------------------|
| `number`       | number | The step number displayed in the button. Default: `1`.          |
| `title`        | string | The heading for the step (appears in TOC).                      |
| `children`     | node   | The content displayed below the step title.                      |

## Features

- ✅ **Copy-to-clipboard** – Click any step number to copy a direct link to that step
- 🎨 **Dark mode support** – Automatically adapts to light and dark themes
- 🔗 **TOC integration** – Steps automatically appear in the table of contents
- ♿ **Accessible** – Semantic HTML and ARIA attributes for screen readers
- 🎯 **Interactive hover states** – Visual feedback when hovering over step numbers
