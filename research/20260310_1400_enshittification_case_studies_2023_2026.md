# Enshittification Case Studies (2023-2026)

**Research Date:** 10 March 2026

---

## Twitter/X API

- **February 2023**: End of free API access.
- **Old**: Free tier, 25,000+ tweets/day.
- **New**: Free (write-only), Basic ($200/mo), Pro ($5,000/mo). Reading 10,000 tweets costs $100/month.
- **Impact**: Student researchers, indie developers, bot creators priced out. Many Twitter-connected apps shut down.
- **February 2026**: Shifted again to pay-per-use credit model.

Sources: [X API Pricing](https://devcommunity.x.com/t/announcing-the-launch-of-x-api-pay-per-use-pricing/256476), [SociaVault](https://sociavault.com/blog/twitter-api-alternative-2025)

## Reddit API

- **April 2023**: Charges announced after 15 years of free access (since 2008).
- **Pricing**: $0.24 per 1,000 API calls. Apollo estimated ~**$2 million/month** (~$20M/year) based on 7B monthly requests.
- **Apps killed**: Apollo, BaconReader, Boost, Reddit Is Fun, Sync — all shut down.
- **Protest**: June 12, 2023: **8,000+ subreddits** went dark.
- Reddit did not reverse; IPO'd March 2024.

Sources: [CNBC](https://www.cnbc.com/2023/06/01/reddit-eyeing-ipo-charge-millions-in-fees-for-third-party-api-access.html), [TechTarget](https://www.techtarget.com/whatis/feature/Reddit-pricing-API-charge-explained)

## Unity Runtime Fee

- **September 2023**: Per-install "Runtime Fee" announced, effective January 2024.
- **Pricing**: Up to $0.20 per install above 200K installs / $200K revenue.
- **Backlash**: Charges on pirated copies, reinstalls, demos. Applied retroactively. Cult of the Lamb developer threatened to delete their game.
- **Resolution**: Runtime fee cancelled entirely. CEO John Riccitiello resigned.

Sources: [BairesDev](https://www.bairesdev.com/blog/unity-pricing-controversy/), [RocketBrush](https://rocketbrush.com/blog/unity-cancels-runtime-fee-what-this-means-for-developers)

## Heroku Free Tier

- **August 2022**: Salesforce announced end of free Dynos, Postgres, Redis.
- **November 2022**: Free tier discontinued.
- **Impact**: Affected significant portion of 13M account base. Hobbyists, students, indie developers hit hardest.
- **New minimums**: Dynos $7/mo, Redis $15/mo, Postgres $9/mo.

Sources: [Heroku FAQ](https://help.heroku.com/RSBRUH58/removal-of-heroku-free-product-plans-faq), [The Register](https://www.theregister.com/2022/08/25/heroku_delete_inactive_free_tier/)

## Google Maps API

- **July 2018**: Overhaul to pay-as-you-go.
- **Old**: 25,000 map loads/day free (750,000/month). $0.50 per 1,000 additional.
- **New**: Only 28,000 free requests/month (~30x reduction). Price per 1,000 jumped from $0.50 to $7 (**14x increase**).
- **Impact**: Average price increases of ~**1,400%**. Mass migration to Mapbox, OpenStreetMap.

Sources: [Geoawesome](https://geoawesome.com/developers-up-in-arms-over-google-maps-api-insane-price-hike/), [Jungleworks](https://jungleworks.com/impact-of-the-new-pricing-model-of-google-maps/)

## Other Notable Examples

- **Google Search**: Legally found to have intentionally degraded search quality through increased ads.
- **Samsung**: $3,500 smart fridge began showing ads (2025).
- **Volkswagen**: Software-locked basic features (e.g., full engine power) behind subscriptions.
- **"Enshittification"** named 2023 Word of the Year (American Dialect Society) and 2024 Word of the Year (Macquarie Dictionary).

Sources: [Wikipedia - Enshittification](https://en.wikipedia.org/wiki/Enshittification)

---

## The Pattern

Every case follows the same sequence:
1. **Attract**: Generous free tier / open API / great documentation
2. **Lock in**: Users build dependencies, workflows, businesses on the platform
3. **Extract**: Prices increase 10-1,400x; free tiers eliminated; APIs restricted

The subsidy period is funded by investors. The extraction is the return on investment. The users' dependency is the product.
