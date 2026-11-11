# MCX Lead Exchange — Pressure Washing

Independent consumer-facing landing page for pressure-washing service requests in Southwest Louisiana, beginning with the Lake Charles area.

## Project isolation

This repository is separate from the main MCX Digital website. Keep all page code, styles, scripts, images, icons, fonts, and deployment configuration here. Do not import assets or deployment configuration from the main MCX website.

## Structure

```text
.
├── public/
│   ├── index.html
│   ├── styles/
│   │   └── style.css
│   ├── scripts/
│   │   └── main.js
│   └── assets/
│       ├── images/
│       ├── icons/
│       └── fonts/
├── wrangler.jsonc
└── README.md
```

## Deployment

The Wrangler configuration is reserved for a separate Cloudflare Worker named `mcx-lead-exchange-pressure-washing`. Static website files are served from `public/`.

Do not deploy or modify the existing `mcx-digital` Worker as part of this project.

## Initial scope

- White-label consumer-facing brand.
- Southwest Louisiana / Lake Charles service area.
- Pressure washing only for the initial launch.
- Separate industry subdomain: `pressurewashing.mcxdigital.net` (proposed; DNS not yet connected).
- Centralized MCX Lead Exchange database remains separate from this website repository.

The current page is only a starter shell. Branding, imagery, service copy, intake form integration, disclosures, and final responsive design are still to be developed.
