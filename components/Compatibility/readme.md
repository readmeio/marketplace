# `<Compatibility />`

## Overview

If you have features that aren't available on every plan or configuration, this module is for you! You can list out plans and a true/false to indicate if it's available.

*Coming Soon: Mobile support, darkmode, more options*

![Compatibility](compat.png)

## Usage

You can use it to show features:

```jsx
<Compatibility title="Feature Name" subtitle="This is a description of the feature" plans={{ "Free": false, "Business": true, "Enterprise": true }} />
```

Or user roles:

```jsx
<Compatibility title="Feature Name" subtitle="This is a description of the feature" plans={{ "Member": false, "Admin": true, "Super Admin": true }} />
```
