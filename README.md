# Elijah | Bible Speed Reader
> *"…the hand of the LORD was on Elijah, and he ran…"* — 1 Kings 18:46

A browser-based RSVP (Rapid Serial Visual Presentation) Bible speed reader. One word at a time, centered on the Optimal Recognition Point so your eyes never move — just read.

**[akridge.github.io/elijah](https://akridge.github.io/elijah)**

![Elijah reader in action](demo.gif)

## Features
- **RSVP display** — Spritz-style ORP alignment keeps the focal letter fixed at center screen
- **KJV Bible** — all 66 books, fetched live from [bible-api.com](https://bible-api.com)
- **Passage selection** — pick book/chapter/verse/end-verse from dropdowns, or type a reference like `Psalms 119:105-120`
- **Speed control** — 60–1000 WPM slider, ±50 WPM with arrow keys
- **Color themes** — Purple, Ocean, Forest, Rose, Gold, and Rainbow (cycles a new color each word)
- **ORP / Word highlight toggle** — highlight only the focal letter, or the whole word
- **Follow mode** — scrolling verse panel below the card highlights each word as it plays
- **Focus mode** — hides the verse panel for a clean, distraction-free view
- **History drawer** — tracks every passage you've read with speed and timestamp, click any entry to jump back in
- **Mobile friendly** — bottom sheets for passage picker and settings on small screens

## Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `←` `→` | Step back / forward one word |
| `↑` `↓` | Speed +50 / −50 WPM |

## How It Works

Bible text is fetched from the free, public-domain [bible-api.com](https://bible-api.com) API at read time. No data is stored server-side. Reading history is saved locally in your browser via `localStorage`.

## License
MIT
