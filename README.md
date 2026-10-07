# Strativa Consulting – landing page

Single-file landing page for a German IT infrastructure consultancy: the outsourced IT department for companies without one (email, devices, networks, backups, security, helpdesk).

- `index.html` – the whole page (HTML, CSS and JS inline; fonts from Google Fonts). Open it directly in a browser or drop it on any static host.
- Palette: monochrome after the "Kinesthetic" reference: light grey `#E4E4E4` base, near-black `#121212` text and accent, grainy gradient panels (`#D6D6D6` to `#8F8F8F` with blurred dark blobs and an SVG noise overlay), dark grain chapters `#171717`. Light and dark themes via CSS tokens.
- Type: Outfit 200–400 (display), DM Sans 300–500 (body and tracked uppercase captions).

## Content policy
The page contains no invented clients, reviews, case studies, certifications or company figures. Everything on it is a description of the offer and the German setup. Add real proof (client logos, references, certifications, team size) only once you can back it up.

## Before going live

- Add street addresses in the Contact section and the legal details (registered office, commercial register number, managing director, VAT ID) required for the German Impressum.
- Wire the contact form submit handler (bottom of `index.html`) to your CRM or form endpoint.
- Point the EN / FR / DE switcher at translated pages and fill the legal links (Impressum, privacy, whistleblowing).
