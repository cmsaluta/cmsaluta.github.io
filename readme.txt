# Developer portfolio (static site)

A single-page portfolio built with semantic HTML, custom CSS, and a small amount of vanilla JavaScript (theme toggle and scroll reveals).

## Project layout

```
website/
├── index.html          # Main page (open this in a browser or serve via any static host)
├── README.md
├── css/
│   └── styles.css      # Layout, theme variables, animations
├── js/
│   └── main.js         # Dark/light mode + scroll reveal
└── images/
    └── mt-fuji.jpeg    # Hero background (add your own file here)
```

## How to view locally

- **Quick:** double-click `index.html`, or drag it into a browser.
- **Recommended:** use a local server so paths behave like production (some browsers are strict with `file://`):

  ```bash
  npx serve .
  ```

  Then open the URL shown (often `http://localhost:3000`).

## Customization checklist

1. Replace **Your Name** in `index.html` (title, logo, footer).
2. Add **`images/mt-fuji.jpeg`** (or change the path in `css/styles.css` under `.hero::before`).
3. Update contact links, projects, and skills to match your experience.
4. Deploy by uploading the whole folder to **Netlify**, **Vercel**, **GitHub Pages**, or any static host.

## Typography

This site uses **[Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)** from Google Fonts—readable, modern, and widely used on product and portfolio sites. Weights loaded: 400–700 (plus italic 400).

**Why this font:** It stays clear at small sizes, pairs well with UI-style layouts, and feels more “product” than generic system Arial. Good alternatives if you want to swap the Google Fonts link in `index.html`: **DM Sans**, **Source Sans 3**, **Inter**.

## Browser support

Uses CSS variables, `backdrop-filter`, and `prefers-reduced-motion`. Works in current Chrome, Firefox, Safari, and Edge.

## License

Use and modify freely for your personal portfolio.
