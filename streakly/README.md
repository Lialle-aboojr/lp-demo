# Streakly Landing Page Demo

This is a simple one-page landing page demo for **Streakly**, a fictional productivity and habit tracking app. It is built with plain HTML, CSS, and vanilla JavaScript so it can be shared quickly as an Upwork proposal sample or adapted into Framer, Carrd, Webflow, or a custom site.

## Files

- `index.html` contains the page structure and placeholder landing page copy.
- `styles.css` contains all visual styling, responsive layout rules, and CSS variables.
- `script.js` handles the mobile navigation toggle and dynamic footer year.

## How to edit the text

Most content lives directly in `index.html`. Search for comments that begin with `Replace this...` to find the safest places to swap in real client copy, including:

- Logo or product name
- Hero headline and subtext
- Feature card titles and descriptions
- Benefit points
- Testimonial or user statistic
- Final call-to-action copy

## How to replace the app mockup

The current hero visual is a CSS/HTML placeholder mockup. To replace it with a real screenshot or exported app mockup:

1. Add the image file to this folder, for example `app-mockup.png`.
2. In `index.html`, find the commented `app-mockup` block in the hero section.
3. Replace that block with:

```html
<img class="app-screenshot" src="app-mockup.png" alt="App dashboard screenshot" />
```

4. Add or adjust styling in `styles.css`:

```css
.app-screenshot {
  width: min(100%, 430px);
  margin-inline: auto;
  border-radius: 28px;
  box-shadow: var(--shadow-soft);
}
```

## Customization tips

- Update brand colors in the `:root` section of `styles.css`.
- Keep section IDs the same if you want the navigation links to continue working.
- The pricing section is intentionally simple and can be changed to a waitlist or beta signup block.
- The contact CTA currently uses `mailto:hello@example.com`; replace it with the client's real signup URL, booking link, or email address.
