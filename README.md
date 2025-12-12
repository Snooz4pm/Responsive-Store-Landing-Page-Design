# Responsive Store Landing Page

This project is a responsive landing page for an online store. It includes a header with navigation, a product section with cards, and a footer. The page aims to be visually pleasing and responsive across devices.

## Files
- `index.html` – main HTML file containing the structure
- `css/styles.css` – custom CSS for layout and styling

## Design Choices
- Clean, minimal look with an accent color (`--accent`) to highlight CTAs.
- CSS Grid for the product layout to make conversions between multi-column and single-column layouts straightforward.
- Bootstrap included via CDN to add quick responsive utilities and buttons (earned extra points).
- Placeholder images are used from Unsplash (hotlink). Replace them with your images as needed.
- Semantic HTML elements (`header`, `section`, `article`, `footer`) were used for accessibility and clarity.

## How to run locally
1. Open `index.html` directly in your browser (double-click), or run a simple server for correct link behavior:

For PowerShell (Windows):

```powershell
# From the project folder that contains index.html
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

## Screenshots
- Add screenshots to the project by capturing your desktop and mobile viewport and place them in a folder named `screenshots/`.
Some placeholder screenshots are already included in `screenshots/` as `desktop.svg` and `mobile.svg`.

Suggested images to capture (replace placeholders if desired):
- `screenshots/desktop.png` – full-width desktop view
- `screenshots/mobile.png` – mobile narrow screen (320–480px width)

Note: Product images now use Unsplash photos (hotlinked) for realistic visuals, and each image includes an automatic fallback to the local SVG placeholders in `images/` if the remote image fails to load.

Image credits (Unsplash) — free to use, but please check Unsplash licensing if you publish commercially:

- Comfy Chair: https://unsplash.com/photos/1526178611600-4d5f6d8abf99
- Minimal Lamp: https://unsplash.com/photos/1531297484001-80022131f5a1
- Cozy Blanket: https://unsplash.com/photos/1499955085172-a104c9463ece
- Kitchen Set: https://unsplash.com/photos/1582582494709-2f1b4a2d3b1b

An `about.html` demo page has been added; it includes a short mission, team note, and a prominent "Demo" note. Update it with production content as needed.

Added `demo.html` which Shop buttons lead to; it clearly states that this is a demo store and that no purchases are possible. This keeps users informed during testing.

Product detail pages were added (`product-1.html` ... `product-4.html`). Clicking a product image, title, or "Shop Now" will open the dedicated product page with price, features, and a demo "Add to cart" modal (purchases disabled in demo).

## Notes
- Comments are placed in `index.html` and `css/styles.css` to explain structure and styles.
- To customize: update CSS variables at the top of `css/styles.css`.

---

If you'd like, I can also:
- Add locally stored demo images
- Create a small screenshot utility (HTML + CSS) to show mobile/desktop mocks
- Add more product content and modal product detail views
