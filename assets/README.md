# App Store asset sources

The icon and screenshots on this website are existing assets from the public
[Scrap Metal Intel App Store listing](https://apps.apple.com/us/app/scrap-metal-intel-live-prices/id6763932885),
verified on October 26, 2026 (current listing: version 2.2.2).

These are Apple CDN WebP renditions. The app UI and image contents have not been
edited, composited, or generated. Screenshot values are examples, not current
market prices or yard quotes. Assets are served locally by this repository's
existing GitHub Pages site.

| Local asset | Official listing image |
| --- | --- |
| `prices.webp` | [01_prices.png](https://is1-ssl.mzstatic.com/image/thumb/PurpleSource221/v4/2f/79/06/2f790699-c586-da72-cd91-9b2337dcce7d/01_prices.png/660x1434bb.webp) |
| `my-yard.webp` | [03_myyard.png](https://is1-ssl.mzstatic.com/image/thumb/PurpleSource221/v4/74/aa/4d/74aa4da7-0af5-5a27-7cee-a947e1d8b027/03_myyard.png/660x1434bb.webp) |
| `calculator.webp` | [02_calculator.png](https://is1-ssl.mzstatic.com/image/thumb/PurpleSource221/v4/a5/e5/3c/a5e53ce9-0b95-6f98-70d8-438164582142/02_calculator.png/660x1434bb.webp) |
| `app-icon.webp` | [App Store icon](https://is1-ssl.mzstatic.com/image/thumb/PurpleSource221/v4/43/85/0c/43850cda-c1bf-a2c2-dbb5-c19c3637b5e8/Placeholder.mill/200x200Icon.ApSiOS01-75.webp) |

The landing-page walkthrough uses features confirmed in that listing: commodity
reference prices, user-entered My Yard rates expressed as a percentage of spot
or dollars per pound, rate-confirmation dates, and a weight-based calculator
with haul logging. It makes no promises about actual buying prices or payouts.

## Local preview

This is a buildless static site. From the repository root:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Publication uses the existing GitHub Pages configuration: `main`, repository
root. No analytics, scripts, external fonts, or network-loaded image assets are
used by the landing page.
