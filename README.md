# TryAmie Website

Marketing landing pages for TryAmie telehealth platform.

## Pages

- `index.html` - Homepage (weight loss focused)
- `tirzepatide.html` - Compounded Tirzepatide product page
- `little-pink-pill.html` - Little Pink Pill (libido) product page
- `hrt.html` - HRT (Hormone Replacement Therapy) product page

## Deployment

This site is deployed on Netlify. Any push to `main` branch auto-deploys.

## Local Development

Just open any HTML file in a browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node
npx serve
```

Then visit `http://localhost:8000`

## Editing with Claude Code

1. Open terminal in this folder
2. Run `claude` to start Claude Code
3. Ask Claude to make changes, e.g.:
   - "Update the tirzepatide price to $299"
   - "Add a new testimonial to the HRT page"
   - "Change the hero headline on the homepage"
4. Claude edits files directly
5. Run `git add . && git commit -m "your message" && git push` to deploy

## File Structure

```
tryamie-site/
├── index.html
├── tirzepatide.html
├── little-pink-pill.html
├── hrt.html
├── images/
│   ├── hrt-bundle.jpg
│   ├── estradiol-cream.jpg
│   ├── estradiol-patch.jpg
│   └── progesterone.jpg
└── README.md
```

## Brand Colors

- Primary Blue: `#4A90A4`
- Accent Peach: `#E8B4A0`
- Cream Background: `#FDF8F5`
- Purple (hormones): `#9580C0`

## Fonts

- Headings: Playfair Display
- Body: DM Sans
