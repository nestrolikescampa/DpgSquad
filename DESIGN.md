# DPG Squad

## Palette and type
A dark, player-first palette takes its cue from the attached round DPG badge: deep teal ground, pale readable text and bright green for selected navigation and calls to action. All colors, faces, spacing, radii, type and shadows live in `src/theme.css`. One dark scheme, no operating-system override.

Space Grotesk headlines and Inter body/labels load together in `src/fonts.css`.

## Shell
A compact top bar keeps the badge at left and the three primary destinations — History, Members, Videos — at right. At narrow widths the navigation becomes a full-width row below the badge. Each route shares a modest footer. The history is the home route; the members and videos tabs are `/members` and `/videos`.

## Brand mark
The attached DPG Squad badge at `/images/dpg-squad-logo.webp` is the site's mark, used as supplied. `src/components/Brand.tsx` centralizes its use. The favicon is a simple green and teal circle. The settings control uses Lucide Settings at stroke width 2; the small video play mark uses a text glyph.

## Imagery
The attached badge is the only supplied squad image. Member portraits and video URLs have not been provided, so member cards use typographic numbered placeholders and video panels clearly state that links are coming soon. No external or invented squad imagery is used.

## Preferences
A settings popover toggles motion and a music preference, saved locally on the visitor's device. The music toggle is a preference placeholder only; no audio track has been supplied or connected.

## Voice
Direct, friendly and player-first. History stays `[BLANK]` until the owner provides it; member names, roles and video links are intentionally placeholders.
