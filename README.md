# Chefpreneur® Workshop Landing Page

Responsive React + TypeScript landing page for the Personal Chef Business Blueprint Workshop, built with Vite.

## Development

Requires Node.js 20.19+ or 22.12+ and npm.

```sh
npm ci --cache /tmp/chefpreneur-npm-cache
npm run dev
```

## Validation and production

```sh
npm run build
npm run preview
```

The build runs TypeScript checks and creates `dist/`. Deploy that directory with any static hosting provider.

## Before launch

- Replace the announced-later schedule with confirmed dates, times, and time zone.
- Connect all registration calls to action to the chosen registration service. Currently they scroll to an honest “registration opening soon” panel; no personal information is collected.
- Add approved privacy policy and terms destinations before enabling registration.
- Supply licensed webfonts for Acherus Grotesque and Bison if desired. Current headings use Montserrat as a fallback; body text uses Montserrat with system fallbacks. The official logo is extracted as vector artwork from the supplied Illustrator brand guide.
- The culinary blueprint illustration is bundled locally. Montserrat/Barlow Condensed are loaded from Google Fonts with system fallbacks. Supply approved local font assets for a fully self-contained deployment.

The visual palette uses flat gold #D4AF37 and deep charcoal #0B1D21 from the supplied Illustrator guide. All FAQ answers disclose the optional VIP upgrade and implementation offer. No backend or payment integration is included.
