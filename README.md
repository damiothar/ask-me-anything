# ask-me-anything

A Magic 8-Ball in the browser: ask a question, get a random answer. Answers come from the classic 20-option list, or from a custom list you build yourself.

**Live:** [damiothar.github.io/ask-me-anything](https://damiothar.github.io/ask-me-anything/)

## Running it locally

There is no build step and no dependencies — plain HTML, CSS and JavaScript. Open `index.html` in a browser, or serve the folder if you prefer a real origin:

```sh
python3 -m http.server
```

## Deployment

GitHub Pages serves the repository root of `main`. Every push to `main` is a deploy; there is no CI step. Configured under Settings → Pages → Deploy from a branch → `main` / `(root)`.
