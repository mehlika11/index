# WordLens

WordLens is a single-page vocabulary lookup tool for English learners. The app lets a user type a word, then shows a simple definition, short example sentences, common word patterns, and similar words.

## What is inside

- `index.html` contains the full app: HTML, CSS, and JavaScript in one file.
- The interface includes quick-start word buttons, a search bar, tabs for examples/patterns/similar words, and image support for visual words.
- The JavaScript asks an AI model to generate learner-friendly vocabulary data, then renders the response in the page.

## How to open it

Open `index.html` in a browser, or publish this repository with GitHub Pages and use the generated website link.

## Note

The page currently calls the Anthropic Messages API from browser JavaScript. For a real public deployment, the API call should go through a small backend or serverless function so the API key stays private.
