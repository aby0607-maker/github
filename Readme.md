# Daily Inspiration

A single-page quote app that fetches a random inspirational quote from an API,
with a local fallback list to keep the experience smooth if the request fails.

## What it does
- Renders a centered quote card with icon, text, and author.
- Fetches a random quote from `https://dummyjson.com/quotes/random`.
- Falls back to a local quote list on errors or invalid responses.
- Shows loading states and disables the refresh button while fetching.
- Uses subtle transitions when updating the quote.

## How it works
- `index.html` contains the markup, styles, and JavaScript.
- `fetchQuote()` handles API requests and validation.
- `displayQuote()` updates the UI and re-enables the button.

## Run it locally
Open `index.html` in a browser.

## Screenshot
Add a screenshot at `assets/screenshot.png` and update the path below.

```text
![Daily Inspiration](assets/screenshot.png)
```

## Notes
- The app is dependency-free and runs in any modern browser.
- Offline use will always fall back to local quotes.
