# MediaSecretsBook.com

## Project
Companion book site to SuccessInMedia.com. Two surfaces: public landing page
(light/warm aesthetic) and bonus portal (portal.html, dark aesthetic). Pure static
HTML + vanilla JS, deployed to Netlify via drag-and-drop.

## Reference
- SIM site: https://sim-todtfeld-2026.netlify.app
- Fonts: Playfair Display + DM Sans
- Gold accent: #c9a84c
- Formspree endpoint: https://formspree.io/f/mgopqgjv
- Calendly: https://calendly.com/jesstodtfeld/15min

## Client
Jess Todtfeld (he/him) — jess@resultsfirsttraining.com
Success in Media, Inc.
Former ABC/NBC/FOX producer (13 years). Guinness World Record holder.
Certified Speaking Professional (CSP). Washington Post-recognized media
training expert. Trained executives at Google, JPMorgan, American Express,
United Nations, and hundreds of Fortune 500 organizations.

## Key decisions
- Landing page: light/warm (#faf8f4 cream background), NOT dark
- Portal: dark palette (matching SIM site)
- No pricing shown anywhere on the site
- All conversion CTAs go to Calendly 15-min fit call
- About Jess is a scrollable block on the landing page, NOT a separate page
- All links to SuccessInMedia.com open in a new tab
- All old ClickFunnels URLs → 301 redirects (see netlify.toml)
- Formspree for form submissions
- localStorage for portal access gate (keys: msb_email, msb_name)
- GMA credential appears as text/badge only — no embedded video
- NEVER mention Goldman Sachs or Korn Ferry
- Always use he/him pronouns for Jess

## File structure
- index.html — public landing page
- portal.html — bonus video portal (localStorage gated)
- prsecretweapons.html — PR consultation page with form
- netlify.toml — redirects + clean URLs
- _headers — security headers
- Images/ — headshot, client logos (copied from SIM site)
