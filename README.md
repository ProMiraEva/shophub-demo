# ShopHub — Premium Products Store Template

A complete, production-ready online store template built as a single `index.html` file. No frameworks, no build tools, no servers required.

## What You Get

- `index.html` — Complete store with cart, checkout, filters, and EN/BG language switcher
- `README.md` — This documentation
- `thumb-shophub.jpg` — Preview image

## Quick Start

1. Download and extract the zip file
2. Open `index.html` in any modern browser
3. Start editing the `PRODUCTS` array with your items
4. Upload to Netlify, Vercel, or GitHub Pages

## Features

✅ Shopping cart with localStorage persistence
✅ Checkout form with validation and order copy
✅ Category filters (Electronics, Fashion, Home, Beauty, Sports)
✅ EN/BG language switcher
✅ Responsive design (desktop, tablet, mobile)
✅ Dark/light mode (automatic)
✅ No dependencies, no build tools
✅ Payhip integration ready

## Customization

### Add/Edit Products

Find the `PRODUCTS` array in the `<script>` section and edit:

```javascript
{ 
  id: 'p1', 
  name: 'Product Name', 
  category: 'electronics', 
  price: 49.99, 
  image: 'https://your-image-url.jpg', 
  desc: 'Product description', 
  payhip: 'https://payhip.com/b/XXXXX' 
}
```

### Change Store Name

Search and replace "ShopHub" in the HTML with your brand name.

### Change Colors

Edit CSS variables in the `:root` selector:

```css
:root {
  --accent: #2563eb;        /* Primary color */
  --accent-hover: #1d4ed8;  /* Hover color */
  --bg: #f8f9fa;            /* Background */
  --surface: #ffffff;       /* Card background */
}
```

### Add Payhip Links

Replace the empty `payhip` field in each product with your Payhip product URL. The "Buy Now" button will link directly to it.

## Deployment

### Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file
3. Get your live URL in seconds

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### GitHub Pages
1. Push `index.html` to a GitHub repo
2. Enable Pages in repo settings
3. Your site will be live at `https://username.github.io/repo`

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

Personal and commercial use. You may modify and deploy for your own projects. Resale of the template itself is not permitted.

## Support

Questions? Contact me through Gumroad or email. I typically respond within 24 hours.
