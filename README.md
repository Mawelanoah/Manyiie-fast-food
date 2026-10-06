# Manyiie Fast Food – Mobile Ordering Website

Professional, mobile-first ordering website for **Manyiie Fast Food** (Soshanguve).

## Features

- **Mobile-first** design optimised for phones
- Real menu (Kotas R21–R55, Chips, Combos) taken from official board
- Sticky cart + multi-step Delivery / Collection flow
- WhatsApp order generation (no online payment)
- Live OPEN / CLOSED status based on opening hours
- Customer reviews with owner moderation
- Owner admin dashboard (menu, hours, delivery areas, reviews, promo, social)
- Smooth lightweight animations + reduced-motion support
- Real logo and branding colours (red / yellow)

## How to run

Open `index.html` in a browser (or serve the folder with any static server).

```bash
# Example
npx serve .
```

## Admin

1. Open `admin.html`
2. Password (demo): `manyiie2026`
3. Manage menu, hours, delivery areas, reviews, etc.

**Important:** Data is stored in browser localStorage for this demo.  
For production, connect a real backend (Supabase, Firebase, or custom API) so data is secure and shared.

## WhatsApp number

Orders are sent to: **069 974 4994** (configurable in admin).

## Credit

Website built by **Noah Mawela**

## Production next steps

1. Host on Netlify / Vercel / Cloudflare Pages
2. Replace localStorage with Supabase (or similar) for:
   - Menu
   - Reviews
   - Settings
   - Auth
3. Add real food photos (replace “PHOTO COMING SOON”)
4. Optional: online payments later without rebuilding the cart flow
