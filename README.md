# Cooper Crane LLC - Website Build

**Business:** Cooper Crane LLC - South Florida crane & boom truck service
**Target (old) site:** https://www.coopercrane.com (Wix)
**Build date:** 2026-06-06
**Repo:** crossfiber/cooper-crane
**Live URL:** https://crossfiber.github.io/cooper-crane/

## Fonts
- Headlines: Oswald (500/600/700) - condensed industrial
- Body: Barlow (400/500/600/700)
- Google Fonts: https://fonts.googleapis.com/css2?family=Oswald:wght@500;600;700&family=Barlow:wght@400;500;600;700&display=swap

## Color palette
- `--concrete #F4F2EE` page bg (cement/jobsite neutral)
- `--concrete-alt #E9E4DC` alt section bg
- `--steel #1E1916` dark warm charcoal (deepened from brand red), dark sections
- `--steel-deep #161210` footer
- `--red #C41E2A` brand crane red, CTA/action only (sourced from the red Cooper Crane boom trucks and crane booms in the fleet photo)
- `--red-hot #A4141F` CTA hover
- `--ink #1A1614` text on light, `--bone #F4EFE8` text on dark

## Design direction (one paragraph)
Industrial heavy-lift built around real red-and-white Cooper Crane iron and the language of capacity. The signature element is a Fleet Capacity Ladder: horizontal bars scaled to each machine's rated tonnage (2-ton mini spider up to 40-ton mobile crane), each tagged with the yard that stocks it. Deliberately avoids the cold national-fleet look the big rental chains use; Cooper reads as a reachable two-yard local operator.

## Placeholders still needing real content
- `[REAL PHOTO NEEDED]` - Why Cooper section image (operator running a lift on site). Only one real photo was extractable from the old Wix site (the fleet lineup, used as the hero).
- `[LOGO ASSET NEEDED FROM CLIENT]` - no usable standalone Cooper Crane logo could be extracted (the Wix logo asset is a tiny referrer-blocked CDN file). A typographic "COOPER CRANE" wordmark is used in the nav/footer as a stand-in. Request a high-res logo (SVG or transparent PNG) from the client.
- Testimonials in the Proof section are clearly-labeled placeholders. No verifiable reviews/ratings were found, so none are claimed. Replace with real Facebook reviews or repeat-customer quotes.
- Southeast yard street address (West Park, FL 33023 per third-party listings) is unverified; confirm before publishing. Hours were not verified and are intentionally not shown.

## Hotlinking risks
- The old site is Wix. All `static.wixstatic.com` images are referrer-blocked on hotlink (confirmed: empty cross-origin fetches), so none are referenced. The single hero photo was downloaded and re-hosted locally in `assets/`.

## Reference build consulted
- JOTL (`C:\Users\accc0\Downloads\JOTL\index.html`) for code structure only. See `borrowed-patterns.md`. Borrowed: mobile drawer + scroll lock, single-open accordion, novalidate form + mailto, flex card bottom-align, breakpoint ladder. NOT borrowed: colors, fonts, copy, transparent nav (replaced with solid-from-load), marquee signature.

## Notes
- `credentials.md` is local-only and excluded from the repo via `.gitignore`.
- Contact form is static: JS validation + `mailto:` routing to the correct yard inbox (SW -> Coopercranefm@gmail.com, otherwise Coopercranefl@gmail.com).
