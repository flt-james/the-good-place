# The Earth Today

AI is restructuring white-collar work. Not AGI — the AI that exists right now. It writes legal briefs, analyses financial data, generates code, processes medical records. This is an industrial revolution for knowledge work.

A small number of entities have spent hundreds of billions of dollars to make this happen. That money needs a return.

## The model layer is becoming cable

Hyperscalers are projected to spend **$660-690 billion in 2026** — roughly 75% on AI infrastructure and models. The per-company numbers are staggering: Amazon ~$200B, Google ~$180B, Microsoft ~$120B+, Meta ~$125B. This is the largest private infrastructure buildout in history. ([See: AI Capex & Commoditisation Research](research/20260310_1400_ai_capex_model_commoditisation_2026.md))

But the models are commoditising faster than any previous technology wave:

- **Inference costs falling ~10x per year.** GPT-3.5-equivalent inference dropped **280x** between November 2022 and October 2024. GPT-4-equivalent fell from $36/million tokens to ~$0.40 — a **90x reduction** in under two years. Post-January 2024, the Epoch AI median decline rate accelerated to **200x per year**. ([Source: Epoch AI](https://epoch.ai/data-insights/llm-inference-price-trends))

- **The open-source gap has collapsed.** On MMLU, the gap between proprietary and open-source models narrowed from **17.5 to 0.3 percentage points**. On HumanEval (coding), open-source is now ahead: Llama 4 Scout achieves 92.7% vs GPT-4o's 90.2%. December 2025 was described as the first year where multiple frontier-class open LLMs compete directly on capability.

- **DeepSeek replicated frontier capability for $5.6 million, then open-sourced it** under MIT licence. DeepSeek R1 is approximately **32.8x cheaper** than GPT-4 for processing tokens. Sam Altman acknowledged it runs **20-50x cheaper** than OpenAI's comparable model. On MATH-500, DeepSeek R1 scored 97.3% vs GPT-4's 74.6%.

This follows the exact pattern of every previous infrastructure buildout. ([See: Infrastructure Commoditisation Historical Patterns](research/20260303_1200_infrastructure_commoditisation_historical_patterns.md))

### The telecom parallel

In the late 1990s, telecoms poured **$500 billion** into fibre optic cable, mostly financed with debt. By 2002, only **2.7% of installed fibre** was actually being used. Between 2000 and 2002, global telecom stocks lost more than **$2 trillion** in market value. **30 publicly traded telecom companies** filed for bankruptcy in 2001 alone. WorldCom collapsed with $103.9 billion in assets — the largest bankruptcy in US history at that time. **250,000+ jobs** were eliminated at equipment suppliers.

The fibre became commodity. The companies that laid the cable did not capture the value of the internet. Google, Netflix, and Facebook did — by building at the layer above. Google, Meta, Microsoft, and Amazon now use **66% of the world's undersea fibre-optic capacity**.

**Sequoia Capital has identified a $600 billion revenue gap** between what the AI industry needs to justify its infrastructure spending and what it actually earns. The original analysis (David Cahn, mid-2024) estimated ~$100B in actual AI revenue, with OpenAI at ~$3.4B as the largest contributor. Sequoia's December 2025 follow-up confirmed the gap has **widened**, as capex scaled faster than revenue. Goldman Sachs, Morgan Stanley, and Howard Marks have all drawn explicit parallels to the telecom bust. ([Source: Sequoia](https://sequoiacap.com/article/ais-600b-question/))

The AI infrastructure companies know this. Having likely lost the model bet, the play shifts upward.

## The orchestration layer is where the value sits

Between a raw language model and a useful product sits a layer of decisions. What context does the model see? What tools can it call? In what sequence? What gets filtered? What gets prioritised? What system prompt shapes its behaviour before you say a word?

This is the orchestration layer. It is where a general-purpose model becomes a specific product. It is also where value is created and captured.

A trillion-dollar company does not build a five-million-dollar product for independent solicitors. The domain knowledge doesn't exist in their organisation. That product gets built by a small team: two or three domain experts and a handful of engineers. The model is a commodity input. The orchestration — the decisions about how the model is configured, constrained, sequenced, and connected to domain-specific tools and data — is the valuable thing.

The AI application layer is already being built this way. Harvey (legal AI, $8B valuation by December 2025), Abridge (healthcare, $5.3B valuation), and dozens of others combine domain experts with AI engineers to embed AI into specific workflows. These are not chatbots that professionals talk to. They are systems that ingest documents, extract clauses, flag risks, draft outputs, and route edge cases to humans. ([See: AI in Professional Services Research](research/20260310_1400_ai_professional_services_errors_regulation.md))

ChatGPT, Copilot, Claude, Gemini — these are not neutral tools. They are bids to become the default interface through which all AI-mediated work flows. The model is the commodity. The interface is the product. The orchestration behind the interface is where the power sits.

## The chat interface is becoming the OS

Here is a claim: the primary interface to computers will be conversational. You will talk or type to your computer. When you need a diagram, that interface will generate one. When you need a form, a spreadsheet, a code editor — the chat layer will summon it. The chat layer becomes the surface through which you interact with all digital capability.

This is not speculative. Every major technology company is building toward it:

- **Apple** is rebuilding Siri from the ground up using LLM-based architecture (codenamed "Campos") for 2026 — a full AI chatbot with deep OS integration, advanced reasoning, web search, image generation, and file analysis.
- **Microsoft** has embedded Copilot across the entire ecosystem (Windows, Office, Teams, Azure). CEO Nadella assumed direct product management.
- **Google** unified all AI under the Gemini brand and launched autonomous coding agents.
- **OpenAI** launched ChatGPT Agent Mode (July 2025) — a unified agentic system that navigates websites, fills forms, edits spreadsheets, connects to email and docs, and executes multi-step tasks.
- **Amazon** launched Quick Suite ($20-40/user/month) — an agentic AI platform connecting to internal documents, databases, and third-party apps.

The conversational AI market is at **$14.89 billion in 2025**, projected to reach **$35.74 billion by 2030**.

This makes the chat interface something categorically different from a tool. A tool is something you pick up, use, and put down. The chat interface, if it becomes the primary interaction layer, is the mediator between you and everything else. It decides what you see. It decides what options are presented to you. It decides what tools get called on your behalf.

Whoever controls that interface controls your entire digital experience. We already know what this looks like. X's own research (published in PNAS, 2022) found its algorithm amplified right-leaning political content in 6 out of 7 countries studied — and when Musk open-sourced the algorithm in 2023, developers found a code path boosting his own account's reach. You didn't experience any of this as manipulation. You experienced it as "the app is really engaging today." When Google's head of search warned internally that the company was "getting too close to the money" and that he could "increase queries quite easily in the short term in user negative ways," you didn't experience the subsequent leadership change — replacing the search chief with the ads chief — as extraction. You experienced it as "search isn't as good as it used to be." In August 2024, a federal judge ruled Google is a monopolist who "acted as one to maintain its monopoly." The platform's interests were encoded into the experience itself, invisible precisely because they shaped everything you could see. ([See: Google Antitrust & X Algorithm Research](research/20260310_1500_google_antitrust_x_algorithm.md))

Now scale that from a feed you scroll to an interface you *think through*.

## What orchestration engineering actually is

When you use a chatbot and accept its output, you are inside someone else's orchestration. Their system prompt. Their retrieval pipeline. Their tool-call routing. Their filtering decisions. Their business model, encoded into the interaction you cannot see.

There's an old story about two fish swimming along who meet an older fish going the other way. The older fish nods at them and says, "Morning, boys. How's the water?" The two young fish swim on for a bit, and then one looks over at the other and says, "What the hell is water?"

The orchestration is the water. You don't notice it because it's the medium you're thinking inside. Using a chatbot feels empowering — you're directing the tool. But the tool is also directing you, and unlike a feed algorithm that shapes what you see, an AI orchestration layer shapes what you *do*.

This is the inversion that matters. The word "tool" implies you have control. But if you cannot see what the tool is doing — what context it was given, what instructions shape its responses, where it sends your data, which third-party services it consults — you have no basis for evaluating whether it serves your interests or someone else's.

These systems are not just software. They are hybrid processes: conventional code, AI agents, and humans, all collaborating within the same workflow. Sometimes the AI directs the human. Sometimes the human directs the AI. Sometimes a workflow involves ten steps — three automated, two requiring human judgement, five handled by different AI models with different capabilities and costs.

The productivity impact is already measurable. GitHub Copilot users complete tasks **55.8% faster**. In 2026, **84% of developers** use AI tools that now write **41% of all code**. AI tutoring achieves **double the learning outcomes at 40% less cost**. Contract review that took 10 hours takes 2. ([See: AI in Professional Services](research/20260310_1400_ai_professional_services_errors_regulation.md))

The $600 billion revenue gap needs to be filled. The orchestration layer is where they plan to collect it. The corporate structures that built it — venture-funded, IPO-bound, fiduciary duty to shareholders — are contractually obligated to find a way.

The question is what they do with that obligation. See [The Bad Place](THE_BAD_PLACE.md).
