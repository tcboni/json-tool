# JSON Tool

A fast, modern JSON viewer, editor, and diff tool that runs entirely in your browser.

**[→ Open JSON Tool](https://tcboni.github.io/json-tool/)**

## Features

### Explorer Mode
- 📝 **Paste & Parse** — Paste JSON and instantly see it as an interactive tree
- 🔧 **Auto-fix** — Tolerates common JSON errors (extra whitespace, trailing commas, characters before/after JSON)
- ✏️ **Live Editing** — Edit values in the tree or raw text, both stay in sync
- 🔍 **Search** — Find keys and values quickly with highlighting
- 📦 **Format & Minify** — Prettify or compress JSON with one click
- 💾 **Copy & Download** — Export your JSON easily

### Diff Mode
- ⇄ **Compare JSON** — Paste two JSON objects and see differences highlighted
- ➕ **Added** — Shows new keys/values in green
- ➖ **Removed** — Shows deleted keys/values in red
- 🔄 **Changed** — Shows modified values in orange with old → new
- 🔀 **Swap** — Quickly swap the two inputs

### Tree Editing
- **Click to edit** — Click any key or value to edit inline
- **Smart type detection**:
  - `true` / `false` → boolean (with checkbox toggle)
  - `123` or `45.67` → number
  - `"text"` (with quotes) → string
  - Empty or `null` → null
  - `[1,2,3]` or `{"a":1}` → parsed as array/object
- **Add items** — Hover over objects/arrays to see the `+` button
- **Delete items** — Hover over any row to see the `×` delete button
- **Expand/Collapse** — Click `+`/`−` or anywhere on the row

### Other Features
- 🎨 **Dark theme** — Easy on the eyes
- 📋 **Clipboard detection** — Auto-detects JSON in clipboard on load
- 📊 **Stats** — Shows file size, line count, and nesting depth
- 🔗 **Path display** — Shows JSON path of selected element
- ⌨️ **Keyboard shortcuts**:
  - `Ctrl+Shift+F` — Format JSON
  - `Ctrl+F` — Focus search
  - `Esc` — Clear search

## Privacy

All processing happens locally in your browser. No data is sent to any server.

## Tech

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Single file (~2300 lines)
