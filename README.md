# Gunaydin Baku: Digital Menu

A simple digital menu website for Gunaydin, Baku. Guests open the site, pick a menu, and read it like a real book: pages turn with a flip animation and a soft page-turn sound.

## Features

- **Landing page** with two menu cards (Main Menu and Steak Menu), a floating logo, ember particles, and hover effects. Both cards fit on screen without scrolling.
- **Flipbook menus.** Each menu opens as a PDF that turns like a book. Pages flip when you swipe or click, with a page-turn sound.
- **Responsive.** Works on phones, tablets, and desktop.
- **Accessible.** Keyboard focus is visible, and animations are reduced when the visitor's system asks for less motion.
- **No build step.** Plain HTML, CSS, and JavaScript.

## Project structure

```
/
├── index.html      Landing page
├── logo.png        Logo shown on the landing page
├── favicon.png     Browser tab icon
├── menu1/          Main Menu (flipbook)
└── menu2/          Steak Menu (flipbook)
```

## Run locally

No installation is needed. Open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## License

This project is licensed under the [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0). You can read the code, learn from it, and use it for personal, educational, or other non-commercial purposes.

**Commercial use is not allowed** without written permission from the author.

See the [LICENSE](LICENSE) file for the full terms.

## Credits

The landing page photos are loaded from [Unsplash](https://unsplash.com) and remain subject to the Unsplash License. The logo and menu content belong to Gunaydin.