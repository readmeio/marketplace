# DataTables Component

The `DataTables` component adds interactive filtering, searching, and export tools to every Markdown-rendered table on the page. It enhances ReadMe’s default table output using [DataTables](https://datatables.net/), without requiring any special syntax or wrapping.

## 🧰 Features

* Adds a toggle button to each table
* Enables:
  * Column visibility control
  * CSV, Excel, and PDF export
  * Table search/filtering
  * Copy and print options
* All enhancements can be toggled off to restore the original table

## Usage

You **do not** need to wrap your tables.

Instead, add the `<DataTables />` component anywhere on the page—preferably at the bottom or top of your doc:

Then write your tables like normal in Markdown:

```markdown
### Table: API Endpoints

| Endpoint      | Method | Description           |
| ------------- | ------ | --------------------- |
| `/users`      | GET    | List users            |
| `/users/{id}` | GET    | Get a specific user   |
| `/users`      | POST   | Create a new user     |
```

> ✅ Once the page loads, each table will show a toggle button that activates DataTables functionality when clicked.

## Notes

* No props are required—this component acts globally and automatically.
* External dependencies (jQuery, DataTables, export plugins) are loaded automatically.
* Accessible by keyboard and screen readers with labeled buttons and inputs.