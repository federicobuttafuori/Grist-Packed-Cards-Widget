# Grist Board Widget

Custom Grist widget that lists table records as packed cards, in the same style as Scanner Jerky board view: white rectangles, optional size by a numeric column, bin-packed layout.

## Using the widget in Grist

Host this folder (GitHub Pages or any HTTPS URL) and paste the URL into **Custom widget URL**.

Until published, open `index.html` locally or serve the folder, then use that URL in Grist.

1. Add a **Custom widget** on the page.
2. Point it at the table you want to list.
3. Open settings (gear) and pick title, subtitle, image, size, and color columns.

Clicking a card selects that row in Grist.

## Settings

- **Title / subtitle / image** — fields shown on each card.
- **Size column** — numeric field used to scale card zoom (like package weight on the board).
- **Color column** — Choice or text used for the inset tint.
- **Extra fields** — additional columns shown on the card body.
- **Group by** — optional section headers.
