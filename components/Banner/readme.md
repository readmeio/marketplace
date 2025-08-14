# Banner

## Overview

Banners can be used to visually highlight important information, announcements, or calls to action directly inside a page. You can customize the message, text, and colors, as well as the position whether it's inline or at the top of the header.

<img src="banner.png" width="800" />

## Usage

```mdx
<Banner
  isInline={false}
  message="This banner is displayed inline. Set isInline to false to move it seamlessly into your page's header!"
  color="#118cfd"
  textColor="#ffffff"
  fontSize="14px"
  fontWeight="bold"
/>
```

## Props

| Prop         | Type    | Description                                                          |
| ------------ | ------- | -------------------------------------------------------------------- |
| `isInline`   | boolean | Determines whether the banner is rendered in the page or the header. |
| `message`    | string  | The text content displayed inside the banner.                        |
| `color`      | string  | The background color of the banner.                                  |
| `textColor`  | string  | The text color of the banner.                                        |
| `fontSize`   | string  | The size of the banner’s text.                                       |
| `fontWeight` | string  | The thickness of the banner’s text.                                  |
