# Powder River Media — Website Notes

## Current Site
- **URL:** powderrivermedia.com
- **Type:** Single-page placeholder
- **Hosting:** GitHub Pages
- **Status:** LIVE (as of early March 2026)

## Page Sections (top to bottom)
1. **Nav** — Fixed/sticky, logo with animation, "Get in Touch" CTA
2. **Hero** — Headline, subtext (mentions full website coming soon), single CTA
3. **Services Strip** — Photography, Video Tours, Drone, Floor Plans (+ "and more")
4. **About Powder River Media** — Two-column: text left, dark brand box right
5. **Our Approach** — Three pillars
6. **Contact Form** — 17hats embed placeholder
7. **Footer** — Logo, email, phone, Instagram, copyright

## Hero Copy
- Subtext includes: "Our full website is coming soon; in the meantime, scroll down to learn more or book a shoot below."
- No "Learn More" button — single CTA only

## About Section
- **Left column:** "Based in Baltimore..." copy about the business
- **Right dark box headline:** "Professional Media That Reflects Your Brand"
- **Right dark box body:** Riffs on the idea that photography reflects back on the agent's brand; ends with "...seriously."
- **Word cloud:** "Proudly serving Central Maryland." / "Rooted in Baltimore City." followed by community word cloud with size hierarchy

## Our Approach / Pillars
1. **Service & Relationships** — Being the photographer agents come back to
2. **Speed** — Fast turnaround, reliability
3. **Full Media Suite** — One-stop shop

## Contact Form
- Placeholder styled for 17hats swap-in
- Fields: name, email, phone, address, service type, date, notes
- Swap instruction: replace `.form-placeholder` block with 17hats embed snippet

## Footer
- Year: 2026
- Instagram: @powderriver.media
- Email: info@powderrivermedia.com
- Phone: 410-929-5407

## Technical Notes
- Scroll reveal animation: DISABLED (was causing blank sections when viewed locally)
- No Cloudflare scripts (were removed — had hitchhiked in from a hosted preview)
- Email addresses: rendered as `mailto:` links, not plain text (spam protection)
- Logo animation: JS-driven with setTimeout dismissal at 3.2s

## Known Spam Issue
- Received 2 spam form submissions within minutes of going live
- Cause: Domain registration is public; bots scrape WHOIS for new domains
- 17hats spam filter should be set to medium+ sensitivity
- Consider adding CAPTCHA to the form

## Hosting Roadmap
- **Now:** GitHub Pages — fine for placeholder
- **Full site launch:** Consider switching to Vercel for auto-deploy workflow
  - Vercel connects to GitHub repo, auto-redeploys on every push
  - Faster CDN, preview URLs, analytics
  - Neither GitHub Pages nor Vercel has meaningful SEO difference

## SEO Priorities (before full site)
1. Submit site to Google Search Console
2. Set up Google Business Profile — highest ROI for local search
3. Full site content (portfolio, service pages, location copy) — coming later

## HTML File
- Filename: `index.html`
- Location: `Website/index.html`
- This is the live file — edit here in Cowork, then push to GitHub to update the live site
- 659 lines as of March 2026

## Website Strategy
`index.html` IS the website going forward. It started as a stand-in/placeholder but Jeff likes it enough that it will become the foundation of the full site — content and sections will be added to it rather than replacing it with something else.

The earlier "prm-final" build (created first in Claude.ai) is outdated as the main site but should be **kept for reference** — it contains useful work (SEO schema, pricing structure, portfolio layout, booking form) that can be drawn from when building out index.html. Jeff to save this file to `Website/prm-final.html` when located.

## What Needs to Be Added to index.html (Full Site Build)
- Real portfolio photos (expected soon — first shoots done March 2026)
- Pricing section
- Full About/bio section with real headshot
- Working contact/booking form (replace 17hats placeholder with real embed or Formspree)
- SEO overhaul (not yet done on this version)
- Any additional sections as determined

## SEO — To Be Done on index.html
The following was done on the older/outdated prm-final build but needs to be applied to index.html:
- Dual JSON-LD schema: ProfessionalService + FAQPage
- Full meta tags: max-snippet, max-image-preview, OG tags, Twitter card
- Performance: preconnect, dns-prefetch, hero image preload, lazy loading
- Accessibility: skip-to-content, aria labels, landmark roles
- Descriptive alt text on all images
