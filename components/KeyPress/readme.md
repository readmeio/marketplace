# KeyPress Component

The `KeyPress` component allows you to render children elements based on a specific key combination being pressed.

## Usage

```mdx
<KeyPress keyCombo="Ctrl+d">
  <div>You hit control + d. GREAT JOB!!!!</div>
</KeyPress>
```

## Props

- `keyCombo` (string, required): The key combination to listen for. Keys should be separated by a `+` (e.g., `Ctrl+Alt+a`).
- `children` (ReactNode, optional): The elements to render when the key combination is pressed.
- `onPress` (function, optional): A callback function to execute when the key combination is pressed.

## Example

```mdx
<KeyPress keyCombo="Ctrl+d" onPress={() => alert('Control + D pressed')} />
```

## Notes

- The `keyCombo` prop is case-insensitive.
- Special keys like `Ctrl`, `Alt`, `Shift`, and `Meta` are normalized to `control`, `alt`, `shift`, and `meta` respectively.
