# `<AdvancedTable/>`

## Overview

Interact with tabular data that supports real-time filtering, column sorting, pagination for large datasets, and CSV exporting.

<img alt="Table with filter, sorting, and pagination options" src="advanced-table.png" width="800" />

## Usage

```mdx
<AdvancedTable
  data={[
    {
      code: 'APIKEY_EMPTY',
      status: 'Unauthorized',
      description: 'An API key was not supplied.',
      message: 'You must pass in an API key.',
    },
    {
      code: 'APIKEY_MISMATCH',
      status: 'Forbidden',
      description: "The API key doesn't match the project.",
      message: "The API key doesn't match the project.",
    },
    {
      code: 'APIKEY_NOTFOUND',
      status: 'Unauthorized',
      description: "The API key couldn't be located.",
      message: "We couldn't find your API key.",
    },
    {
      code: 'API_ACCESS_REVOKED',
      status: 'Forbidden',
      description: 'Your ReadMe API access has been revoked.',
      message: 'Your ReadMe API access has been revoked.',
    },
    {
      code: 'API_ACCESS_UNAVAILABLE',
      status: 'Forbidden',
      description: 'Your ReadMe project does not have access to this API. Please reach out to support@readme.io.',
      message: 'Your ReadMe project does not have access to this API. Please reach out to support@readme.io.',
    },
    {
      code: 'APPLY_INVALID_EMAIL',
      status: 'Bad Request',
      description: 'You need to provide a valid email.',
      message: 'You need to provide a valid email.',
    },
    {
      code: 'APPLY_INVALID_JOB',
      status: 'Bad Request',
      description: 'You need to provide a job.',
      message: 'You need to provide a job.',
    },
    {
      code: 'APPLY_INVALID_NAME',
      status: 'Bad Request',
      description: 'You need to provide a name.',
      message: 'You need to provide a name.',
    },
    {
      code: 'CATEGORY_INVALID',
      status: 'Bad Request',
      description: "The category couldn't be saved.",
      message: "We couldn't save this category ({error}).",
    },
    {
      code: 'CATEGORY_NOTFOUND',
      status: 'Not Found',
      description: "The category couldn't be found.",
      message: "The category with the slug '{category}' couldn't be found.",
    },
    {
      code: 'CHANGELOG_INVALID',
      status: 'Bad Request',
      description: "The changelog couldn't be saved.",
      message: "We couldn't save this changelog ({error}).",
    },
    {
      code: 'CHANGELOG_NOTFOUND',
      status: 'Not Found',
      description: "The changelog couldn't be found.",
      message: "The changelog with the slug '{slug}' couldn't be found.",
    },
  ]}
/>
```

## Props

| Prop   | Type  | Description                                             |
| ------ | ----- | ------------------------------------------------------- |
| `data` | array | An array of objects representing the rows of the table. |
