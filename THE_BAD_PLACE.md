# The Bad Place

What happens if the current trajectory continues unchecked.

## Previous platforms controlled information. AI controls reasoning.

Every previous platform war was about access to information or markets. Search engines control what you find. Social media controls what you see. Advertising networks control what you want. All of these operate on the information environment — they shape the inputs to your thinking.

AI operates closer to the decision itself. The chat interface doesn't just present information. It participates in reasoning. It summarises, prioritises, frames. When you ask it to analyse a contract, it decides what to highlight and what to skip. When you ask it to compare options, it decides the criteria. When you delegate a task — book the cheapest flight, find a good tax strategy, draft a response to this legal claim — it makes choices on your behalf, within a framework you didn't set and can't see.

Google controls what you find. Facebook controls what you see. AI frames the data you use to make decisions — and increasingly, AI will makes those decisions for you.

## The manipulation surface is enormous

A captured chat interface does not need to lie to you. It needs to:

- Surface some options and not others.
- Frame choices in ways that favour the platform's interests.
- Route tool calls to preferred third parties.
- Shape what information you see first, in what order, in what tone.

This is not hypothetical. It is how algorithmic feeds already work. The difference: feeds manipulate your attention. A captured AI interface manipulates your decisions and actions.

And the research on algorithmic manipulation is unambiguous:

- Facebook's internal research (leaked by Frances Haugen, 2021) confirmed they **deliberately shifted their algorithm to amplify anger** because it drove engagement. European political parties reported the algorithm forced them to "skew negative." ([See: Algorithmic Manipulation Research](research/20260310_1400_algorithmic_manipulation_ai_influence.md))

- A 2024 field experiment published in *Science* found that reranking feeds on X to change exposure to partisan content shifted political feelings by **2+ points on a 100-point scale in just 10 days**. A 2023 *Science* study found switching from chronological to algorithmic feeds shifted people toward **more conservative political positions**.

- A Cornell University study (2025) found AI chatbots programmed to advocate for specific candidates moved opposition voters' preferences by **10+ percentage points** — roughly **4x the effect of traditional political ads**. The mechanism: LLMs persuade by generating a high volume of supporting claims, which can mislead by omission even when individually accurate. ([Source: Cornell Chronicle](https://news.cornell.edu/stories/2025/12/ai-chatbots-can-effectively-sway-voters-either-direction))

That is what happens when algorithms control attention. AI chat interfaces control decisions — a qualitatively larger manipulation surface.

You don't need to understand orchestration code. But you do need to know whether the system serves your interests or someone else's. A tax AI that calls a third-party service with your financial data — was that call in your interest? A medical AI whose recommendations are subtly shaped by pharmaceutical partnerships embedded in the orchestration you cannot see — how would you know? A legal AI that routes your contract review through a tool maintained by the opposing party's vendor — the interface looks the same.

If you cannot inspect the process, do not own the model interaction, cannot see the tool calls, and cannot verify where the system routes your data — you have no basis for trust.

## The corporate structure guarantees capture

A company that has taken billions in venture capital and is pursuing a public offering has a fiduciary obligation to its shareholders. That obligation will always, eventually, override the mission statement. This is not a moral failing of the people involved. It is the logic of the structure they're builting inside.

**OpenAI is a case study in real time.** ([See: AI Capex & Commoditisation Research](research/20260310_1400_ai_capex_model_commoditisation_2026.md))

| Date | Event |
|------|-------|
| December 2015 | Incorporated as **nonprofit**. Mission: AI "most likely to benefit humanity." |
| 2019 | Creates **capped-profit** subsidiary. Returns capped at 100x. |
| 2021 | Cap reportedly reduced to "single digits" for some investors. |
| 2023 | Caps set to **increase 20% annually**. Board fires Altman; reinstated days later after Microsoft pressure. |
| October 2025 | New structure: nonprofit holds **26%**, Microsoft holds **27%**, employees/investors hold **47%**. |

The stated mission has not changed. The corporate structure has reversed completely. This is not hypocrisy — it is the capital structure doing what capital structures do.

The enshittification pattern is so well-documented it has a name. The attract phase looks generous — free tiers, open APIs, great documentation. That is the subsidy period. The investors are paying for your dependency. The reversal always comes: ([See: Enshittification Case Studies](research/20260310_1400_enshittification_case_studies_2023_2026.md))

- **Twitter/X API** (2023): Free access eliminated. Reading 10,000 tweets went to $100/month. Student researchers, indie developers, bot creators priced out.
- **Reddit API** (2023): After 15 years free, charged $0.24 per 1,000 calls. Apollo estimated costs of ~$20M/year. Apollo, BaconReader, Boost, Reddit Is Fun, Sync — all killed. 8,000+ subreddits went dark in protest. Reddit IPO'd anyway.
- **Unity** (2023): Retroactive per-install runtime fee. Backlash so severe the CEO resigned and the fee was cancelled — but only after developers had already begun migrating.
- **Heroku** (2022): Free tier eliminated. 13 million accounts affected.
- **Google Maps API** (2018): Free tier cut ~30x. Price per 1,000 requests jumped from $0.50 to $7. Average price increases of **~1,400%**.

"Enshittification" was named 2023 Word of the Year by the American Dialect Society. Not because it was a clever coinage, but because it described what everyone was already feeling.

The difference this time: the tools being enshittified will run healthcare, legal services, education, and financial planning. Enshittification of your social media feed is irritating. Enshittification of your medical advice is a crisis.

## The errors are already visible

AI in professional services is already producing failures at scale: ([See: AI Professional Services Research](research/20260310_1400_ai_professional_services_errors_regulation.md))

- **486 documented cases** of legal AI hallucinations worldwide (324 in US courts). **156 lawyers sanctioned** for AI hallucinations in court filings. Stanford research found legal AI tools hallucinate in **1 out of 6+ queries**.
- A **14% increase** in healthcare malpractice claims involving AI tools (2024 vs 2022). An April 2025 *Nature Medicine* study found AI diagnostic tools changed recommendations based on patient race, gender, and income — not symptoms. In some pediatric studies, AI misdiagnosis rates exceeded **80%**.
- The Texas Attorney General settled with a company selling AI healthcare documentation tools for "false, misleading, and deceptive" accuracy claims.

These errors happen in systems where the orchestration — the prompt chains, retrieval logic, validation steps — is opaque. You cannot see what the system did, and therefore cannot assess whether to trust the output. The trust problem and the transparency problem are the same problem.

## The political dimension

Seven companies command **$20.8 trillion** in market capitalisation — exceeding the entire GDP of the European Union — and account for **37% of the S&P 500**. These same companies control the infrastructure that democratic societies depend on for communication, information access, and public administration. ([See: AI Power Concentration Research](research/20260303_1100_ai_power_concentration_democratic_threat.md))

The political spending is accelerating:

- Tech companies exceeded **$100 million** in US lobbying in 2025 for the first time. Meta led all companies in all industries at $26.29 million. OpenAI nearly doubled its spend to $3 million. Nvidia's budget ballooned **7x** to $4.9 million.
- These six companies employed **nearly 300 lobbyists in 2024** — approximately one for every two members of Congress.
- OpenAI's president gave **$25 million** to the President's political action committee. Altman appeared with President Trump the day after inauguration.
- Trump's inaugural committee raised a record **$239 million**, with $1 million each from Meta, Amazon, Google, Apple, Microsoft, and others. Tech was the single largest source of inauguration funding.
- Meta **unilaterally ended fact-checking** for billions of people in January 2025, moving to a "community notes" model already shown to fail on X (misleading content viewed **13x more** than community notes reached).
- Romania **annulled a presidential election** in December 2024 after discovering a coordinated influence campaign using 25,000 TikTok accounts and undeclared endorsements worth over EUR 1 million.

The pattern is no longer deniable: unchecked concentration of AI capability is becoming unchecked concentration of political power. AI gives these companies something none of the previous platforms provided: direct access to the reasoning process itself.


## Why the counter-arguments don't hold

**"Models won't commoditise — proprietary models will stay ahead."** This is the argument the monopolists need you to believe, because if models commoditise, their infrastructure investment has no moat. Every investment bank analyst says the trajectory points to commoditisation. The MMLU gap went from 17.5 to 0.3 percentage points. The people arguing against commoditisation are the people whose business model depends on it not happening.

**"It's already too late — ChatGPT has hundreds of millions of users."** This confuses adoption with lock-in. People adopted these tools because they were first, not because they're trapped. They will leave if something better, cheaper, and trustworthy exists. The question is whether we build it.

**"We're weeks from AGI, none of this matters."** This is the tech oligarch's "resistance is futile." It is designed to make opposition feel pointless. Every previous "imminent superintelligence" claim has been wrong. The people making this claim have a direct financial interest in you believing it — it inflates valuations, justifies spending, and forecloses political opposition by making the future seem inevitable.

## The trajectory

Opaque orchestration plus profit motive plus scale equals extraction as an emergent property. No conspiracy is needed. The incentive structure produces the outcome. A publicly traded company with a dominant chat interface will, eventually, optimise that interface for revenue. The interface has total informational control over you. The optimisation will be invisible. You will not experience it as manipulation. You will experience it as the product working normally.

This is where we end up by default.

But default is not the same as inevitable. Read [The Good Place](THE_GOOD_PLACE.md) — not a plan, but a specification of what any solution needs to satisfy.
