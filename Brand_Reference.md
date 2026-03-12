# Powder River Media — Brand Reference
*Last updated: March 2026*

## Authority Note
`Brand Presentation/PRM-Brand-Presentation.html` is the single source of truth for all logo specs. If there is any conflict between this document and the brand presentation, the brand presentation wins.

## Typography
- **Display / Headings:** Cormorant SC (serif) — weight 600 for name, 500 for sub-label
- **Body / Sub-labels:** DM Sans (sans-serif) — weight 500
- **Font files:** `Cormorant_SC,DM_Sans.zip` in Logo/Fonts/

## Color Palette
| Name        | Hex       | Usage |
|-------------|-----------|-------|
| Aqua        | `#3ABFBF` | River mark, active states, hover accents — primary brand accent |
| Dark Teal   | `#1D2B2E` | Primary dark background |
| Gold        | `#C9B882` | Eyebrows, CTAs, stat numbers, footer links |
| Coral       | `#E8826A` | Secondary accent only — never in primary logo lockup; use for campaigns, seasonal content |
| Warm White  | `#FAFAF8` | Primary light background |
| BG Alt      | `#F2F0EB` | Alternate background sections |
| Ink         | `#1C1C1C` | Body text |
| Mid Gray    | `#5A5A5A` | Secondary text |
| Light       | `#E8E6E1` | Borders, dividers |
| Black       | `#000000` | Logo variant background only |

## Logo Mark — Final Specs
**Icon geometry:**
- Horizon line: stroke `#606060` (dark grey, not black), weight `1.8`, `stroke-linecap="square"`
- River curve: stroke `#3ABFBF` (aqua), weight `2.4`, `stroke-linecap="square"`
- Both lines use square caps — this was a deliberate final decision
- ViewBox for stacked/vertical use: `"2 16.5 36 17"` (cropped tight to remove phantom padding)
- ViewBox for horizontal/icon use: `"0 0 40 40"`

**Icon dimensions in lockups:**
- Horizontal lockup: `44×44` (uses square viewBox)
- Vertical/stacked lockup: `46×20` (uses cropped viewBox)

**Wordmark:**
- Primary name: "POWDER RIVER" in Cormorant SC weight 600, letter-spacing 0.08em
- Sub-label: "REAL ESTATE MEDIA" in DM Sans weight 500, letter-spacing 0.2em
- Note: "Real Estate Media" — NOT "Powder River Media" — is the sub-label in lockups

**Spacing:**
- Horizontal lockup gap (icon to text): 8px
- Vertical lockup gap (icon to wordmark): 2px
- Sub-label margin-top: 5px
- Minimum clear space around logo: 32px on all sides
- Sub-label text: nudged 1.7px right to optically align "R" in Real with "P" stem in Powder (compensates for serif overhang)

## Lockup Variants
Three official lockup types, each with full color set:
1. **Horizontal** — icon left, wordmark right. Use for: nav, email headers, letterheads
2. **Vertical** — icon above, "POWDER RIVER" on one line, "REAL ESTATE MEDIA" below. Standard lockup
3. **Stacked** — icon above, "POWDER" on one line, "RIVER" below, "REAL ESTATE MEDIA" below that. Use for: tight square formats, hats, merchandise, stamps

**Color variants available for all lockups:**
- Aqua color, dark on transparent
- Aqua color, white on dark teal
- Aqua color, white on black
- Aqua color, dark on white
- Coral color variants (same backgrounds)
- B&W dark on transparent / white / dark teal / black
- B&W white on transparent / dark / black

## Coral as Secondary Accent
Coral (`#E8826A`) is a secondary accent with full logo variants. Rules:
- The river mark in the primary lockup is **always aqua**
- Coral never replaces aqua in the main logo
- Coral can appear in: seasonal campaigns, social story covers, email accent colors, designed layouts

## Watermarks
- White only — no aqua or accent color
- Available horizontal and vertical
- For: photo watermarking, video lower-thirds, document footers

## Logo Files Location
All logo files in: `Logo/` folder
- `Logo/Lockups/Horizontal/` — all horizontal variants
- `Logo/Lockups/Stacked/` — all stacked variants
- `Logo/Lockups/Vertical/` — all vertical variants
- `Logo/Icon Only/` — social profile images + icons (also used as favicon)
- `Logo/Watermarks/`
- `Logo/Fonts/` — Cormorant SC + DM Sans zip
- `Logo/favicon.ico`

**File naming convention:**
- `PRREM-` prefix = full wordmark lockup (Powder River Real Estate Media)
- `PRM-Icon-` prefix = icon only
- Filename includes: color description, background, pixel width
- Transparent background files say "on-transparent" in name

## Logo Animation Sequence (Placeholder Page Only)
1. Horizontal bar — present immediately, static
2. River curve — begins drawing slowly (~2.2s total)
3. Wordmark — fades in at 0.6s (while river is still mid-draw)
4. Loader clears at 3.2s

## Brand Personality & Story
- Confident, professional, direct
- Brief and punchy — "Rooted in Baltimore." energy
- Named after the Powder River in Wyoming (Jeff's home state)
- "Powder River, Let 'er Buck" — Wyoming battle cry meaning "let's roll" — the spirit behind the name
- Jeff hiked the Appalachian Trail in 2008 under the trail name "Powder River"
- The logo mark has a deliberate resemblance to a cattle brand — intentional nod to Wyoming ranching heritage
- This backstory does NOT need to be visible in the brand; it's a private foundation that informs authenticity

## Website Nav Logo
- Currently uses text + inline SVG (not a PNG/image file)
- Correct approach for now — perfectly scalable, no extra file request
- Will switch to SVG file when mark is fully finalized
- Nav sub-label: "Real Estate Media" (no "Baltimore" — geography handled elsewhere on page)
