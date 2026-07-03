# CraftRadar

CraftRadar is a personal market-research tool that helps me choose products and
keywords for my own Etsy shop.

It reads public listing and shop data through the official
[Etsy Open API v3](https://developers.etsy.com/documentation/) on a weekly
schedule and computes aggregate niche statistics — listing counts, price
distributions, review counts — alongside Google search-volume data. Results are
shown in a private dashboard used only by me.

- Uses the official Etsy Open API only; does not scrape etsy.com
- Respects Etsy's rate limits and caching policies
- Read-only: no shop management, no write operations
- Personal use: no third-party users

CraftRadar is not affiliated with or endorsed by Etsy, Inc.
