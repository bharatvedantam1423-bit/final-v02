# CCBP v02: Programmes section

"Three programmes. One is yours." Three programme cards (Academy, Intensive,
NIAT). Hovering a card expands it to show the photo, feature list and CTA; the
other two cards collapse into slim tabs.

- `index.html`: markup
- `styles.css`: layout, states and animation (Outfit for the headline, Inter for everything else)
- `script.js`: hover, focus and tap handling
- `assets/`: exported Figma images (see `assets/README.md`)

Open `index.html` in a browser to preview. Behaviour:

- **Desktop:** hover or keyboard-focus a card to expand it. Moving the pointer out resets the cards.
- **Mobile (<900px):** the cards stack; tap one to open or close it.
- Honours `prefers-reduced-motion`.
