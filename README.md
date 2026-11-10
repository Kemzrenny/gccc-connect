# GCCC Connect

One-page link hub for **Glory Centre Community Church, Ojodu**: the page behind the QR codes on chair stickers and first-timer cards.

Sections: welcome hero with a gathering badge that alternates every 5 seconds between today's gatherings and the next one (Lagos time), the next-step cards, grouped as Give, Grow, Watch & listen, Special Programmes and Explore GRM, weekly meetings, PZak's welcome and first-timer playlists, and social links.

## Editing links

All links live in the `LINKS` object near the bottom of `index.html`. Empty values stay inactive until filled.

| Key | Card |
| --- | --- |
| `spotify` | Take the Word with you (Watch & listen), Spotify pill |
| `youtube` | Relive our services (Watch & listen), YouTube pill |
| `instagram`, `facebook`, `mixlr` | Social pills |
| `give` | Give card, mobile Give button |
| `fol` | Festival of Life |
| `believers` | Believers' Class |
| `teens` | Glory Realms Teens Church |
| `aaac` | AAAC |
| `gloryHomes` | Glory Homes |
| `grm` | Explore GRM (set to gloryrealmsministries.org) |
| `welcomeForm` | First-timer welcome card |
| `messages`, `worship` | First-timer playlists |

## Weekly meetings

Edit the `SCHEDULE` array in `index.html`. `mins` sets how long the "Happening now" badge shows.

## QR codes

- Chair sticker "Scan to see what's next": the page URL
- First-timers card: the page URL + `#new`
- "Scan to GIVE": the giving link directly

## Fonts

Clash Display 600 is embedded as a base64 `@font-face` at the top of the stylesheet. When this page moves onto gloryrealmsministries.org, remove that block and use the site's own Clash Display. Body text uses Poppins from Google Fonts.
