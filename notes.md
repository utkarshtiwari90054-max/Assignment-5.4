# Assignment 5.4 - Notes

- `tokens.css` defines all variables in `:root`: colors (primary, secondary, background, text, plus surface and text-on-color), spacing (small 8px, medium 16px, large 32px) and font sizes (small, medium, large, xlarge).
- `style.css` uses only `var(...)` for these values in headings, buttons (`.btn-primary`, `.btn-secondary`, `.btn-outline`) and cards (`.card`).
- **Verification (step 6):** change `--color-primary` in `tokens.css` (e.g. `#1d6fa5` to `#2e7d4f`), or click the color buttons on the page. The h1/h2/h3 headings, primary and outline buttons, and card top borders all change together. Changing `--space-medium` likewise adjusts padding and gaps across cards, buttons and paragraphs.
