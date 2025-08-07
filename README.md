# 73nko Theme

A custom VS Code theme featuring a rich purple and pink color palette.

## Color Palette

- `#210a31` - Deep purple (background)
- `#dc91a4` - Light pink
- `#975d90` - Medium purple
- `#624a8c` - Purple blue
- `#859eca` - Light blue
- `#663269` - Dark purple
- `#472f71` - Medium dark purple
- `#ddd5e2` - Light lavender
- `#da3e49` - Red
- `#be5e7d` - Rose
- `#ca3e5a` - Pink red
- `#c0bedf` - Pale purple
- `#e0726f` - Coral
- `#6b5578` - Gray purple
- `#8695ab` - Blue gray

## Installation

1. Copy this folder to your VS Code extensions directory:
   - **Windows:** `%USERPROFILE%\.vscode\extensions`
   - **macOS:** `~/.vscode/extensions`
   - **Linux:** `~/.vscode/extensions`

2. Restart VS Code

3. Open Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)

4. Type "Preferences: Color Theme" and select it

5. Choose either:
   - `73nko Dark` for the dark variant
   - `73nko Light` for the light variant

## Development

To package this theme for distribution:

```bash
npm install -g vsce
vsce package
```

This will create a `.vsix` file that can be installed in VS Code.

## License

MIT