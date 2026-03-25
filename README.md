# 🐱 Purrfect Random Numbers

A fast, single-file HTML/CSS/JavaScript random number generator with a cute cat theme.

## What this is

- **One file**: `purrfect-random.html`
- **No frameworks / no external libraries**
- **Works offline** (open directly in your browser; no server required)
- **Typography**: Times New Roman (system font, no imports)
- **Colors**: white background, medium blue accent, black text

## How to run (local)

1. Download / clone this repo
2. Open `purrfect-random.html` in a browser:
   - **Double-click** the file in Finder, or
   - In Safari/Chrome press **⌘O** and choose the file

## Features

- **Min / Max inputs** with labels
- **Generate** button (also press **Enter** while focused in an input)
- Large, bold result number with a subtle pop/fade animation
- **Copy to Clipboard** button (appears after the first result)
- **History log** of the last **5** generated numbers
- **Clear History** button
- Friendly **input validation**:
  - empty fields
  - min greater than max
  - non-integer values

## Accessibility & UX

- Proper `<label>` elements for inputs
- Buttons include descriptive `aria-label`s
- Status/error messages announced via `aria-live`
- Keyboard accessible (Tab through controls; Enter to generate from inputs)

## Files

- `purrfect-random.html` — the entire app (HTML + CSS + JS)
- `README.md` — this documentation

---

🐱 Made with ❤️ and lots of cats

