# Cooper Crane LLC - Website Build

**Business:** Cooper Crane LLC - South Florida crane & boom truck service
**Target (old) site:** https://www.coopercrane.com (Wix)
**Build date:** 2026-06-06
**Repo:** crossfiber/cooper-crane
**Live URL:** https://crossfiber.github.io/cooper-crane/

## Fonts (v2)
- Headlines: Barlow Condensed (500/600/700) - industrial condensed (switched from Oswald in v2 for a less-default feel and to differentiate from sibling builds)
- Body: Barlow (400/500/600/700)
- Google Fonts: https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;600;700&family=Barlow:wght@400;500;600;700&display=swap

## Color palette (v2 - burnt construction orange, not red)
- `--concrete #F5F1EA` warm concrete page bg
- `--concrete-alt #ECE4D6` alt section bg
- `--steel #211B14` warm brown-charcoal (derived from the orange, not a neutral black)
- `--steel-2 #2C241B` raised surface on steel
- `--steel-deep #18130D` footer
- `--orange #C25D1C` burnt/weathered construction orange, CTA/action only (deliberately not hi-vis safety orange). Hover `--orange-hot #9F4912`
- `--ink #1C1813` text on light, `--bone #F5EFE6` text on dark

## Design direction (v2)
Industrial heavy-lift built around real Cooper Crane iron and the language of capacity, in a burnt/weathered construction orange on warm brown-charcoal. The signature element is the Fleet Capacity Ladder: horizontal bars scaled to each machine's rated tonnage (2-ton mini spider up to 40-ton mobile crane), each tagged with the yard that stocks it, and it now LEADS the page (section two) as the identity. v2 was reworked specifically to NOT resemble the P&C Mobile Repair build: orange not red, warm brown-charcoal not neutral black, Barlow Condensed not slab serif, right-clustered nav not centered, capability rows not icon-card grid, image-left about with no overlapping badge, single split service-area panel, single wide pull-quote, and no diagonal caution-stripe motifs anywhere.

## Placeholders still needing real content
- `[REAL PHOTO NEEDED]` - Why Cooper section image (operator running a lift on site). Only one real photo was extractable from the old Wix site (the fleet lineup, used as the hero).
- `[LOGO ASSET NEEDED FROM CLIENT]` - no usable standalone Cooper Crane logo could be extracted (the Wix logo asset is a tiny referrer-blocked CDN file). A typographic "COOPER CRANE" wordmark is used in the nav/footer as a stand-in. Request a high-res logo (SVG or transparent PNG) from the client.
- Testimonials in the Proof section are clearly-labeled placeholders. No verifiable reviews/ratings were found, so none are claimed. Replace with real Facebook reviews or repeat-customer quotes.
- Southeast yard street address (West Park, FL 33023 per third-party listings) is unverified; confirm before publishing. Hours were not verified and are intentionally not shown.

## Hotlinking risks
- The old site is Wix. All `static.wixstatic.com` images are referrer-blocked on hotlink (confirmed: empty cross-origin fetches), so none are referenced. The single hero photo was downloaded and re-hosted locally in `assets/`.

## Reference build consulted
- JOTL (`C:\Users\accc0\Downloads\JOTL\index.html