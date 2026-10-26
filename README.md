# A Little Place to Breathe

A gentle friendship scrapbook for Nivi, built from the existing 3D book with HTML, CSS 3D transforms, and vanilla JavaScript. It contains ten supportive spreads and keeps the page turns, touch swipes, keyboard navigation, autoplay, reset, and reduced-motion support.

## Run locally

Open this folder in VS Code and start **Live Server** from `index.html`, or run a simple static server from this directory:

```powershell
py -m http.server 8000
```

Then open <http://localhost:8000>.

No build step or package installation is required. The Google Fonts link is optional; local system fallbacks are included.

## Personalize the scrapbook

Edit the `friendName` variable and the spread text in `js/scrapbook-data.js`. The friend's name is interpolated into the title, subtitle, letter, and other reminders. Each spread contains `left` and `right` page objects, with its title, text, tone, ornaments, and optional illustration. The six interactive comfort notes are in the same file under `window.emergencyCards`.

The small SVG illustrations are in `assets/decorations/`. They are symbolic decorations, not claims about Nivi's personal memories or favorite things. The suggestions on the small-joys spread are possibilities, not assumptions about what she likes.

## Notes

- Google Fonts loads when internet access is available; the experience remains usable offline with fallback fonts.
- Comfort notes open in a keyboard-accessible dialog. Use Escape or the close button to return to the book.
