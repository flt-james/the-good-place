# AI Infrastructure Capex & Model Commoditisation (2025-2026)

**Research Date:** 10 March 2026

---

## 1. Aggregate Infrastructure Spending

- **2025**: Top 5 hyperscalers (Amazon, Google/Alphabet, Microsoft, Meta, Oracle) projected ~**$443 billion** in capex, a 73% year-over-year increase.
- **2026**: Collectively committed to **$660-690 billion**, ~36% increase over 2025. Approximately **75% ($450B+)** directly tied to AI infrastructure.

### Per-Company Breakdown

| Company | 2025 Capex | 2026 Projected |
|---------|-----------|----------------|
| Amazon | ~$100B+ | ~$200B |
| Google/Alphabet | ~$85B | $175-185B |
| Microsoft | $80B+ (Azure backlog unfulfilled due to power constraints) | ~$120B+ |
| Meta | $66-72B (double prior year) | $115-135B |

### Sequoia's "$600B Revenue Gap"

- **Original source**: David Cahn at Sequoia Capital, ["AI's $600B Question"](https://sequoiacap.com/article/ais-600b-question/) (mid-2024).
- **Methodology**: NVIDIA annualized GPU revenue (~$150B) → doubled for full data center costs ($300B) → doubled again assuming 50% gross margins = **$600B revenue needed annually**.
- **The gap**: ~$100B in actual AI revenue (OpenAI at ~$3.4B as largest single contributor). Gap ≈ **$500B**.
- **2025 update**: Sequoia's [December 2025 follow-up](https://sequoiacap.com/article/ai-in-2025/) — gap has **widened**, as capex scaled faster than revenue.

Sources:
- [Futurum: AI Capex 2026 - The $690B Infrastructure Sprint](https://futurumgroup.com/insights/ai-capex-2026-the-690b-infrastructure-sprint/)
- [IEEE ComSoc: Hyperscaler capex >$600B in 2026](https://techblog.comsoc.org/2025/12/22/hyperscaler-capex-600-bn-in-2026-a-36-increase-over-2025-while-global-spending-on-cloud-infrastructure-services-skyrockets/)
- [CNBC: Tech AI spending approaches $700B in 2026](https://www.cnbc.com/2026/02/06/google-microsoft-meta-amazon-ai-cash.html)
- [Tom's Hardware: AI industry needs $600B/year](https://www.tomshardware.com/tech-industry/artificial-intelligence/ai-industry-needs-to-earn-dollar600-billion-per-year-to-pay-for-massive-hardware-spend-fears-of-an-ai-bubble-intensify-in-wake-of-sequoia-report)

---

## 2. Inference Cost Collapse

### Rate of Decline

- **Epoch AI** analysis of 36 price observations: **median decline 50x per year**. Post-January 2024 acceleration: **200x per year median**. Range: **9x to 900x per year**.
- **GPT-3.5 equivalent**: inference cost dropped **280x** between November 2022 and October 2024 (Stanford HAI 2025 AI Index).
- **GPT-4 equivalent**: from **$36/million tokens** at launch (March 2023) to ~**$0.40/million tokens** — roughly **90x reduction** in under 2 years.
- **DeepSeek R1**: approximately **32.8x cheaper** than GPT-4 for processing tokens. Sam Altman acknowledged it runs **20-50x cheaper**.

### Current API Pricing (early 2026)

| Model | Input (per 1M tokens) | Output (per 1M tokens) |
|-------|----------------------|------------------------|
| GPT-5.2 | $1.75 | $14.00 |
| Claude Opus 4.5 | $5.00 | $25.00 |
| Claude Sonnet 4 | $3.00 | $15.00 |
| Gemini 2.5 Flash-Lite | $0.10 | $0.40 |
| Llama (hosted) | $0.05-$0.90 | varies |

### Hardware-Level Cost per Query

- Typical AI query (few hundred words): **$0.0003 to $0.036** in compute
- 500-word GPT-4 response: ~**$0.084**; same task on Llama 2: ~**$0.0007** (120x cheaper)

Sources:
- [Epoch AI: LLM Inference Price Trends](https://epoch.ai/data-insights/llm-inference-price-trends)
- [a16z: Welcome to LLMflation](https://a16z.com/llmflation-llm-inference-cost/)
- [Cost of Inference Blog](https://blog.dannycastonguay.com/Cost-of-Inference/)

---

## 3. Open-Source vs. Proprietary Performance Gap

| Benchmark | Gap (Previous) | Gap (Current) | Open-Source Leader |
|-----------|---------------|---------------|-------------------|
| MMLU | 17.5 pp | **0.3 pp** | DeepSeek-V3.2 (94.2%) |
| HumanEval (coding) | significant | **open-source ahead** | Llama 4 Scout (92.7%) vs GPT-4o (90.2%) |

- Open-weight releases lag proprietary by 6-18 months, but window keeps shrinking.
- December 2025 described as first year where multiple frontier-class open LLMs compete directly on capability.

### DeepSeek Specifics

- **Training cost**: ~**$5.6 million** (cloud rental hours only; capital cost of GPUs not counted)
- **Comparison**: OpenAI spent estimated **$100M+** on GPT-4; Google spent **$191M** on Gemini Ultra
- **DeepSeek R1 vs GPT-4**: MMLU 90.8% vs 87.2%; AIME 2024 79.8% vs 9.3%; MATH-500 97.3% vs 74.6%
- **Open-sourced** under MIT licence with six smaller variants

Sources:
- [LLM Stats: AI Trends 2026](https://llm-stats.com/ai-trends)
- [IntuitionLabs: DeepSeek's Low Inference Cost Explained](https://intuitionlabs.ai/articles/deepseek-inference-cost-explained)

---

## 4. Chat Interface as Primary OS

### Company Moves

**Apple**: WWDC 2024 announced "Apple Intelligence" + ChatGPT integration into Siri. Siri architecture being **rebuilt from ground up** using LLM-based architecture. 2026 plans: full AI chatbot (codenamed "Campos") with deep OS integration.

**Microsoft**: Copilot embedded across entire ecosystem (Windows, Office, Teams, Azure). CEO Nadella **assumed direct product management** of Copilot.

**Google**: Unified all AI under **Gemini** brand. I/O 2025: Gemini Code Assist, Jules (autonomous coding agent), deeper device integration.

**OpenAI**: **ChatGPT Agent Mode** (July 2025): unified Operator + deep research + conversational AI into single agentic system. Can navigate websites, fill forms, edit spreadsheets, connect to email/docs.

**Amazon**: Alexa+, Amazon Q (enterprise), Amazon Quick Suite ($20-40/user/month agentic AI platform).

### Market Scale

- Conversational AI market: **$14.89B in 2025**, projected **$35.74B by 2030** (19.14% CAGR)
- Broader AI software market: **$514.5B in 2026**

Sources:
- [DQ India: Apple Siri AI Chatbot Upgrade 2026](https://www.dqindia.com/news/is-apple-turning-siri-into-a-full-ai-chatbot-to-rival-chatgpt-and-gemini-11035933)
- [OpenAI: Introducing ChatGPT Agent](https://openai.com/index/introducing-chatgpt-agent/)

---

## 5. OpenAI Corporate Structure Timeline

| Date | Event |
|------|-------|
| December 2015 | Incorporated as **nonprofit**. $1B commitment from Altman, Musk, others. |
| 2019 | Launches **OpenAI LP** — "capped-profit" subsidiary. Returns capped at **100x**. |
| 2021 | Profit cap reportedly reduced to **"single digits"** for some investor classes. |
| 2023 | Caps set to **increase 20% annually** from 2025. November: board fires Altman; reinstated days later. |
| February 2024 | Musk sues alleging shift from public benefit to profit maximisation. |
| March 2025 | Judge denies Musk's block on for-profit conversion. |
| May 2025 | OpenAI announces nonprofit will **retain control** (bowing to pressure). |
| October 2025 | New structure: **OpenAI Foundation** (nonprofit, 26% stake), **OpenAI Group PBC** (for-profit). Microsoft holds **27%**. Employees/investors hold **47%**. |

Sources:
- [OpenAI: Evolving Our Structure](https://openai.com/index/evolving-our-structure/)
- [TIME: An OpenAI Timeline](https://time.com/7328674/openai-chatgpt-sam-altman-elon-musk-timeline/)
- [CNBC: OpenAI nonprofit retain control](https://www.cnbc.com/2025/05/05/openai-says-nonprofit-retain-control-of-company-bowing-to-pressure.html)
