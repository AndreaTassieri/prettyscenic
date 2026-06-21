# prettyscenic

Company website for an existing company — a free design cleanup for the owner.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Single-page website (semantic HTML5) |
| `styles.css` | All styles — clean, minimal, mobile-responsive |

## Customizing the content

The following items in `index.html` should be updated to match the live site exactly:

- **Hero headline & subtitle** — lines 27-28
- **About copy** — lines 39-48
- **Service names & descriptions** — lines 70-95
- **Contact email** — line 114 (`mailto:` href + visible text)
- **Contact phone** — line 118 (`tel:` href + visible text)
- **Contact location** — line 122
- **Footer copyright year** — line 132

To replace the grey photo placeholder (About section) with a real image, swap the
`<div class="placeholder-image">` block with a standard `<img>` tag and remove the
`.placeholder-image` rule from `styles.css`.

## Running locally

Open `index.html` in any browser — no build step or server needed.
