# FUNKO Properties & Homes

A responsive React + Vite real-estate storefront prototype with 30 illustrative property listings, dedicated property detail routes, filters, saved homes, gallery controls, enquiry forms, team, services, about and contact pages.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The production output is `dist/`.

## Deploy to Cloudflare Workers with static assets

This repository includes `wrangler.jsonc` configured to publish `dist/` as static assets with SPA fallback. In a connected Cloudflare Workers Git deployment, use:

- Build command: `npm run build`
- Deploy command: `npx wrangler deploy`
- Root directory: `/`

## Important demo notes

- Property names, prices, reference numbers, availability, neighbourhood assignments and descriptions are illustrative sample content, not verified live listings.
- The location panel is an interactive-looking schematic map, not a geocoded map or route planner.
- Enquiry forms validate in the browser and show a demo confirmation. They do not submit to a CRM or email service.
- WhatsApp links use a demo number (`+2348000000000`). Replace it with the business's verified number before launch.
- Team names and biographies are fictional sample profiles.
- Photography is loaded from Unsplash image URLs. Confirm image licensing and replace with approved property photography before commercial resale or production launch.
- Replace the placeholder email address and business contact details before launch.
