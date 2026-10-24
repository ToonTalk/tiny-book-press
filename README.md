# Tiny Book Press

Turn one sheet of A4 or US Letter paper into an eight-page folded mini-book.

**Use it:** https://toontalk.github.io/tiny-book-press/

Each page has a heading, some words and a picture. A picture can be:

- **imported** from a file (or dropped onto a page of the sheet),
- **asked for** from an AI (Claude, Gemini or ChatGPT, with your own API key):
  with a Gemini or ChatGPT key it can be **painted** by their image models,
  otherwise it is drawn as shapes (SVG),
  and in desktop Chrome, Gemini Nano (built into the browser) needs no key at all,
- **drawn** in the built-in drawing program, in black and grays or in color,
  with stamps the AI makes for you that you can move, resize and turn.

Type, or press the microphone and say, what picture or stamp you want.

**My books** keeps books in this browser and can save a book to a file and open it
again (or drop a book file on the sheet). The example book is there too.

Download the sheet as a PDF, print it landscape at 100%, crease the dashed lines,
cut the one solid line, and fold it into a book. "How to fold" in the app shows the steps.

## Keys

API keys go straight from your browser to the company that made the AI. They are
kept only until you close the page, unless you tick "Remember my keys in this
browser". They are never saved in your book.

When the app runs as a claude.ai artifact it uses Claude on the viewer's own
claude.ai account instead, and needs no key.

## Files

Everything is in `index.html`: no build step, no server. The only outside
resources are Google Fonts and jsPDF from cdnjs.

## License

MIT, see [LICENSE](LICENSE).
