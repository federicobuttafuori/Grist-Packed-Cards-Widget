# grist-packed-cards-widget

Custom Grist widget that lists table records as packed cards, in the same style as Scanner Jerky board view: white rectangles, optional size by a numeric column, bin-packed layout.

## Using the widget in Grist

Host this folder (GitHub Pages or any HTTPS URL) and paste the URL into **Custom widget URL**.

Repo: **[https://github.com/federicobuttafuori/grist-packed-cards-widget](https://github.com/federicobuttafuori/grist-packed-cards-widget)**

Until published, open `index.html` locally or serve the folder, then use that URL in Grist.

1. Add a **Custom widget** on the page.
2. Point it at the table you want to list.
3. Open settings (gear) and pick title, subtitle, image, size, price, and color columns.

Clicking a card opens that row in Grist card view.

## Settings

- **Title / subtitle / image** — fields shown on each card.
- **Size column** — numeric field used to scale card zoom (shown with `g`).
- **Price column** — numeric field shown as `€` with 2 decimals.
- **Color column** — Choice or text used for the inset tint.
- **Extra fields** — additional columns shown on the card body.
- **Group by** — optional section headers.
