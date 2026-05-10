# Unshackled Kings Website

This is a beginner-friendly static website. It does not need a build tool, database, or paid software to run.

## Files

- `index.html` controls the page content and structure.
- `styles.css` controls colors, layout, spacing, and mobile responsiveness.
- `script.js` controls the mobile menu.
- `Unshackled King logo.png` is the main premium hero logo.
- `c23fb289-f10c-4840-b6e0-3547687c296a.png` is the header and footer wordmark.
- `d99c902a-1bf2-4835-9545-0d1ecaa430d9.png` is the cinematic hero and final CTA background.
- `2b3f12b2-5c06-46d3-a6c8-64f7b3af8081.png` is the secondary program and offer badge.
- `ee8384ed-894c-45dd-af90-1cc748cf33e0.png` is the crown and broken-chain emblem used as a section accent.
- `Webpage content.txt` is the original source copy.

## How to preview it

1. Open the `Unshackled King` folder on your computer.
2. Double-click `index.html`.
3. The website should open in your browser.
4. If you make changes, save the file and refresh the browser.

## Easy edits

### Change the price

Open `index.html`, search for `$47`, and replace it with your new price.

### Add your checkout link

Open `index.html` and find this line:

```html
<a class="button button-primary" href="mailto:you@example.com?subject=I%20want%20to%20join%20Unshackled%20Kings">Start the 30-Day Reset</a>
```

Replace the `href="..."` value with your payment link from Stripe, Gumroad, PayPal, Shopify, or another checkout provider.

Example:

```html
<a class="button button-primary" href="https://your-checkout-link.com">Start the 30-Day Reset</a>
```

### Change an image

Put the new image in this folder, then update the matching `src="image-name.jpg"` in `index.html`.

## Best workflow with Codex and ChatGPT

1. Use ChatGPT for strategy, copywriting, offer ideas, audience research, and content drafts.
2. Save approved copy into this folder as text files, then ask Codex to update the website with that copy.
3. Use Codex for coding, layout changes, file edits, testing, and fixing bugs.
4. Keep all images, text, and notes inside this same project folder so Codex can use them.
5. Work in small requests, such as "change the hero copy," "add a testimonials section," or "make the pricing section stronger."

## Launch checklist

- Replace the email button with a real checkout link.
- Add a real contact email.
- Add testimonials when you have them.
- Test on phone and desktop.
- Publish with Netlify, GitHub Pages, or another static website host.
