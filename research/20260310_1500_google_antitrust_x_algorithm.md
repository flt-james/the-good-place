# Google Antitrust Case & X/Twitter Algorithm

**Research Date:** 10 March 2026

---

## 1. US v. Google — DOJ Antitrust Case

### The Ruling

**Judge Amit P. Mehta**, U.S. District Court for the District of Columbia, ruled on **August 5, 2024** that Google violated Section 2 of the Sherman Antitrust Act by maintaining an illegal monopoly in general search and search text advertising.

> **"Google is a monopolist, and it has acted as one to maintain its monopoly."**

277-page opinion. Google holds ~**89.2% of general search market** (94%+ on mobile). Google paid Apple **$26 billion in 2021** alone to remain the default on Safari.

### Internal Documents: The "Code Yellow" Crisis

The trial (September-November 2023) exposed extensive internal communications:

**February 5, 2019**: Google's ads team declared a "code yellow" (internal emergency) due to **"steady weakness in the daily numbers"** — search query growth was behind forecast, threatening quarterly revenue targets.

**Ben Gomes (Head of Search), February 6, 2019**: Expressed alarm that search was **"getting too close to the money."** Wrote that he could **"increase queries quite easily in the short term in user negative ways"** — listing methods like disabling spell correction, removing ranking improvements, and cluttering pages with refinement labels.

**Nick Fox (VP, Search)**: Highlighted a **"pretty big disconnect between what finance and ads want"** versus what the search team was working on.

**Prabhakar Raghavan (VP, Ads), March 22, 2019**: Wrote that revenue targets had been addressed via **"heroic RPM engineering"** (revenue per mille — ad optimization) while **"core query softness continued without mitigation."**

### The Leadership Change

In **May 2020**, Prabhakar Raghavan (who had been running ads) replaced Ben Gomes as head of Google Search. Gomes was moved to SVP of Education — widely interpreted as a demotion. Raghavan previously led Yahoo Search from 2005-2012, during which Yahoo's search share collapsed from 30.4% to 13.4%.

### Ad Label Obfuscation

- **May 2019**: Google redesigned mobile ad labels, replacing bright green "ad" indicators with subtle black text.
- **January 2020**: Same treatment applied to desktop.
- The Verge noted these changes made **"Google's ads look just like search results now."**

### Independent Confirmation

A year-long study (January 2024, Leipzig University/Bauhaus-University Weimar) found **"the majority of high-ranking product reviews in the result pages of commercial search engines use affiliate marketing, and significant amounts are outright SEO product review spam."** (7,392 product-review terms analyzed across Google, Bing, DuckDuckGo.)

Sources:
- [Ed Zitron: "The Man Who Killed Google Search"](https://www.wheresyoured.at/the-men-who-killed-google/) — links directly to DOJ document exhibits
- Judge Mehta ruling: Document 1000, Case 1:20-cv-03010, U.S. District Court for D.C.
- [404 Media: Google Search quality study](https://www.404media.co/google-search-really-has-gotten-worse-researchers-find/)

---

## 2. X/Twitter Algorithm

### Open-Sourcing (March 31, 2023)

Musk released the recommendation algorithm source code on GitHub (`github.com/twitter/the-algorithm`).

**What the code revealed:**

- ~1,500 candidate tweets sourced per refresh: ~50% from accounts you follow, ~50% from accounts you don't.
- Neural network "heavy ranker" scores tweets using both **explicit signals** (likes, retweets, replies) and **implicit signals** (profile visits, clicks, dwell time).
- Visibility filters for "legal compliance, improve product quality, increase user trust, **protect revenue**."
- **Paid subscriber boost**: Twitter Blue/Premium accounts received an algorithmic ranking boost.
- **"Author is Elon" boost**: Developers discovered a code path giving Musk's own account preferential treatment. Widely reported, later acknowledged.

### Musk's Personal Algorithm Manipulation (February 2023)

After a Musk tweet about the Super Bowl received lower engagement than expected, engineers were reportedly directed to boost Musk's tweets in the "For You" timeline. Reported by NYT, Washington Post, and Platformer (~February 14, 2023).

### Twitter's Own Research on Amplification

**October 2021** (pre-Musk): Twitter's internal research, published in PNAS (2022), found that **Twitter's algorithm amplified right-leaning political content more than left-leaning content in 6 out of 7 countries studied** (US, UK, Canada, France, Germany, Spain, Japan). Study: "Algorithmic amplification of politics on Twitter."

### Post-Musk Changes

- "For You" algorithmic timeline made the default (previously users could default to chronological).
- "Time spent" (dwell time) prioritised as ranking signal.
- Most of Trust & Safety team fired or resigned.
- Multiple researchers documented increased hate speech and misinformation post-acquisition.

### Relevant External Research

- **"Out-group animosity drives engagement on social media"** (Barber et al., PNAS, 2021): Posts about political out-groups received significantly more engagement on Twitter.
- **"Political sectarianism in America"** (Finkel et al., Science, 2020): Social media algorithms contribute to polarization through engagement-optimizing design.
