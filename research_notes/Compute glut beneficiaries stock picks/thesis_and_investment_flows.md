# Compute Glut Thesis and Investment Flows (as of 2026-11-23)

Thesis tested: "The next market leaders won't sell compute, they'll monetize it. Healthcare, robotics, and defense tech look like the biggest beneficiaries of a compute glut."

Source-quality note: many 2026 figures surfaced only via secondary aggregators and blogs (valueaddvc, shattered.io, tradingkey, etc.). Primary sources used where possible: NVIDIA press release, Menlo Ventures report, Crunchbase News, PitchBook report pages, Rock Health, Epoch AI. Aggregator-only numbers are flagged "[secondary]".

## Q1. Is there evidence of compute oversupply as of late 2026?

### Takeaway
No clear glut as of November 2026. Every hard indicator (NVIDIA revenue, hyperscaler capex guidance, H100 rental prices, data-center vacancy, neocloud backlog) points to demand still meeting or exceeding supply. The stress shows up in financing (neocloud debt costs), not in idle capacity. Per-token prices are collapsing, which is a "glut" in unit cost terms, not in hardware.

### Cited Findings
**Compute sellers: still accelerating**
- NVIDIA Q3 FY2027 (quarter ended Oct 25, 2026; reported Nov 17, 2026): revenue $115.8B, +103% YoY, +20% QoQ. Data Center $107.6B, +110% YoY, +21% QoQ. GAAP gross margin 74.8% — [NVIDIA press release](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-third-quarter-fiscal-2027)
- NVIDIA Q4 FY2027 guidance: $130.0B ±3%, which includes an extra week and assumes no China data-center compute revenue. Gross margin is guided down to 71.0–72.0%. Interim CEO/CFO Colette Kress: "Vera Rubin is off to an explosive start." The release says NVIDIA is working to "scale critical manufacturing capabilities to meet demand." It gives no backlog figure — [NVIDIA press release](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-third-quarter-fiscal-2027)
- Vera Rubin NVL72 racks began shipping to CoreWeave, Google Cloud, Azure, OCI and Nebius. Hopper data-center shipments to China were $2.4B in the quarter — [stocktitan/NVIDIA release summary](https://www.stocktitan.net/news/NVDA/nvidia-announces-financial-results-for-third-quarter-fiscal-fpx9dw5egxqa.html) [secondary]
- The 3–4 point gross-margin step-down guided for Q4 is a possible early sign of pricing or mix pressure. It may also simply reflect the Rubin ramp. Treat it as an inference, not evidence of a glut — [NVIDIA press release](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-third-quarter-fiscal-2027)

**Hyperscaler capex (2026 guidance, Big 4)** [secondary trackers; verify against 10-Qs]
- Combined 2026 guidance is about $720–745B, depending on the Microsoft figure used — [datacentres.com](https://www.datacentres.com/guides/hyperscaler-capex-trends); [yieldtheory](https://www.yieldtheory.app/research/hyperscaler-ai-capex-tracker-2026)
- Amazon: about $220B, raised from about $200B on July 30, 2026 — [datacentres.com](https://www.datacentres.com/guides/hyperscaler-capex-trends)
- Alphabet: $195–205B, raised from $180–190B. The CFO cited "acceleration in the delivery of capacity to meet growing demand" and expects capex to "increase significantly in 2027" — [datacentres.com](https://www.datacentres.com/guides/hyperscaler-capex-trends)
- Meta: $135–145B (narrowed from $130–145B) — [mmarw](https://mmarw.com/intelligence/ai/hyperscaler-capex-q3-2026)
- Microsoft: about $175B for CY2026 including finance leases. Another source says it was trimmed to about $170B after Q3 because of delayed third-party capacity, so this figure is contested. A separate source cites a "$190B" FY plan. Microsoft also changed an accounting estimate, extending data-center useful lives from 15 to 25 years — [valueaddvc](https://valueaddvc.com/blog/big-tech-ai-capex-in-2025-microsoft-google-meta-amazon-and-the-spending-race); [globaldatacenterhub](https://www.globaldatacenterhub.com/p/microsoft-q3-fy2026-the-190b-capex)
- The Microsoft trim was driven by delayed supply (third-party capacity), not weak demand. That counts against a glut — [valueaddvc](https://valueaddvc.com/blog/big-tech-ai-capex-in-2025-microsoft-google-meta-amazon-and-the-spending-race) [secondary]

**GPU rental prices (H100)**
- H100 rents fell from about $8/hr in 2023, bottomed in 2025, then rose about 40% in 2026 — [coloprice](https://coloprice.com/guides/h100-rental-prices/); [shattered.io](https://shattered.io/h100-h200-b200-cloud-gpu-pricing-2026/) [secondary]
- The SemiAnalysis H100 1-year contract index rose from $1.70 to $2.35/GPU-hr between October 2025 and March 2026. The Silicon Data index was about $2.53 in mid-2026 — [akash.network](https://akash.network/the-bid/h100-rental-price-2026-cost-per-hour/); [cloudzero](https://www.cloudzero.com/blog/h100-gpu-cost/) [secondary citation of SemiAnalysis]
- One tracker shows the median on-demand H100 price rising from $2.49 (Jan 2026) to $4.14 (Nov 2026), but it covers only 4 providers. Spot and marketplace floors are about $1.25–2.20/hr, and hyperscaler on-demand is about $10–12/hr — [finitizer](https://tools.finitizer.com/gpu-rental-prices/h100); [emma.ms](https://www.emma.ms/blog/nvidia-h100-cloud-gpu) [secondary, low quality]
- Conflicting forecast: some vendor blogs predicted H100 spot at $1.00–1.50 by late 2026. That has not materialized according to the index data above — [spheron](https://www.spheron.network/blog/nvidia-h100-price-2026/)

**Neoclouds: strong demand, financing stress**
- CoreWeave Q3 2026 (reported Nov 10, 2026): revenue about $3.66B (+168% YoY). 2026 revenue guide raised to $13.0–13.3B. Q3 net loss $709M. Backlog $132.5B as of Sep 30 (up from $104B in June). Of the backlog, 26% is to be recognized within 24 months, 38% in months 25–48 and 36% beyond 48 months — [implicator.ai](https://www.implicator.ai/coreweave-reports-q3-revenue-up-168-yoy-3-66b-vs-3-55b-est/); [llms.blog](https://www.llms.blog/posts/coreweave-q3-results-backlog-guidance) [secondary]
- CoreWeave's debt is about $47B (one source says $47.5B). Q3 net interest expense of $846M exceeded operating income. Some of its bonds yielded above 16%. The CFO said there will be no new parent-level unsecured debt through 2027 at current yields. Q3 capex was $14.5B. The stock had fallen more than 40% in the month before earnings — [tradingkey](https://www.tradingkey.com/analysis/stocks/us-stocks/262299527-coreweave-earnings-report-q3-revenue-growth-backlog-capital-expenditures-net-loss-tradingkey); [insidedeeptech](https://www.insidedeeptech.com/coreweave-ai-neocloud-gpu-fleet-debt-full-guide/) [secondary]
- Nebius closed $5.75B of convertible notes in August 2026. Reported metrics (3.5 GW contracted, a $27B Meta contract, $20–25B 2026 capex) are inconsistent across sources and unverified — [blog.prompt20](https://blog.prompt20.com/posts/neoclouds-complete-guide/); [Wikipedia](https://en.wikipedia.org/wiki/Nebius_Group) [secondary]
- Lambda's IPO slipped from H2 2026 to a planned 2027. It is reportedly raising up to $4B at a $14.5B pre-money valuation, and no public S-1 exists — [forgeglobal](https://forgeglobal.com/insights/lambda-upcoming-ipo-news/); [newmarketpitch](https://newmarketpitch.com/blogs/news/neocloud-funding-news) [secondary]
- Crusoe raised a $3.9B Series F at $30.9B (September 2026), up from $10B at its Series E in October 2025. It was still private as of Nov 14, 2026 — [admiralmarkets](https://admiralmarkets.com/education/articles/shares/crusoe-ipo) [secondary]

**Physical constraints: argue against a near-term glut**
- North American data-center vacancy has been about 1% for a third straight year (JLL, August 2026, cited secondhand) — [cycledesk substack](https://cycledesk.substack.com/p/internet-bubble-vs-todays-ai-buildout) [secondary]
- As many as half of the data-center projects slated for 2026 could face delays from power, equipment shortages and local opposition (Sightline Climate, cited secondhand). Large data centers take 3–7 years to develop — [datadeep.tech](https://datadeep.tech/ai-bubble-or-infrastructure/); [The Register, Jan 14 2026](https://www.theregister.com/2026/01/14/ai_investment/)
- Power access is the "primary headwind" for new development in most markets — [The Register](https://www.theregister.com/2026/01/14/ai_investment/)

**Inference cost per token: this is where a price "glut" already exists**
- Epoch AI (March 2025, older data): the price for a fixed capability level fell 9x–900x per year depending on the task, with a median of 50x/yr. Using post-January 2024 data, the median was 200x/yr — [Epoch AI](https://epoch.ai/data-insights/llm-inference-price-trends)
- "The Price of Progress" (arXiv, 2025): prices fall 5–10x/yr at fixed capability. However, the cost of running *frontier* models rose about 3–18x/yr — [arXiv 2511.23455](https://arxiv.org/html/2511.23455v2)
- Menlo (Nov 2026): average open-source token prices fell 3.3x to $0.13/M tokens, and blended closed-model prices fell 24% to $0.70/M. Open-source models are 19% of tokens but only 4% of spend — [Menlo Ventures](https://menlovc.com/perspective/2026-the-state-of-enterprise-ai/)
- Reasoning and agent models emit far more tokens per task, so per-task bills can rise while per-token prices fall — [safeguard.sh](https://safeguard.sh/resources/blog/is-ai-getting-cheaper-cost-per-token-trends-and-caveats) [secondary]

### Inferences
- The "compute glut" is not visible in hardware as of Nov 2026: the GPU seller is growing more than 100% YoY, H100 rents are *rising*, vacancy is about 1%, and capex guidance keeps being raised. The thesis is a forward bet (2027–2029), not a description of the present.
- The real "glut" today is in *intelligence per dollar*, from token price deflation. That benefits monetizers regardless of whether a hardware glut ever arrives.
- The weak link is neocloud balance sheets. CoreWeave's 16% bond yields, interest above operating income and 74% of backlog beyond 24 months show that duration and counterparty risk are concentrated there. If a glut comes, leveraged neoclouds are the likely first casualties (analogous to the 2001 CLECs and fiber carriers).
- Power limits act as a supply governor, which lowers the odds of a fiber-style 2–5% utilization collapse. It does not eliminate GPU-generation obsolescence risk: H100s can get cheap even while total capacity stays tight.

### Gaps
- No primary SemiAnalysis data was accessed (paywalled). The B200 and GB200 $/hr trend could not be reliably sourced.
- No reliable neocloud utilization percentages were found. Nebius Q3 2026 results were not retrieved from a primary source.
- Hyperscaler Q3 2026 capex figures come from secondary trackers. Microsoft's figure ($170B vs $175B vs $190B FY) remains unresolved.

## Q2. Counter-evidence: is demand still outstripping supply? Bulls vs bears

### Takeaway
Demand-side revenue is growing explosively (frontier-lab run rates of $50–65B+, enterprise AI deployment spend up 5.4x), which supports bulls in the near term. The bear case rests on capex-to-revenue mismatch, circular financing, very long-dated backlog and weak measured ROI at the median enterprise.

### Cited Findings
- Menlo Ventures (Nov 3, 2026): enterprise AI deployment spend was $176.8B as of September 2026, up 5.4x from $33B in 2025. Development (building AI) spend was $102.5B (+5.3x), of which training compute was $87.2B. The method is a survey of about 400 US enterprise decision-makers (Morning Consult, Sep 8–26, 2026) plus a bottom-up model on a run-rate basis — [Menlo Ventures](https://menlovc.com/perspective/2026-the-state-of-enterprise-ai/)
- Menlo estimates that Anthropic and OpenAI account for 25%+ of AWS, Azure and Google Cloud revenue, much of it for training. This concentration risk underlies "circular" demand — [Menlo Ventures](https://menlovc.com/perspective/2026-the-state-of-enterprise-ai/)
- Anthropic's annualized run-rate revenue reached $65B by end of July 2026 (gross accounting). A projection above $100B for 2026 (attributed to the NYT) is unverified — [valueaddvc](https://valueaddvc.com/blog/anthropic-revenue-hits-47b-run-rate-how-it-passed-openai-in-just-five-months) [secondary]
- OpenAI told investors its annualized revenue was near $50B at end of September 2026 (net accounting; FT), versus about $70B on a gross basis. Bloomberg reported a target of ≥$70B annualized by year-end — [beri.net](https://www.beri.net/article/openai-revenue-50-billion-not-70-billion-gross-vs-net-run-rate-vendor-viability-ipo-delay); [sacra](https://sacra.com/c/openai/) [secondary]
- OpenAI compute and infrastructure spending is planned at about $856B through 2030 (FT, July plan, cited secondhand; unverified) — [valueaddvc](https://valueaddvc.com/blog/openai-revenue-2026-20b-arr-4b-month-path-to-profitability) [secondary]
- Bear framing (older, June 2024): Sequoia's David Cahn, "AI's $600B Question", argued AI revenue must reach about $600B a year to justify the capex run rate — [Sequoia](https://www.sequoiacap.com/article/ais-600b-question/). Inference using the figures above: at $720–745B of 2026 Big-4 capex alone, the implied required revenue is now far above $600B, while frontier-lab revenue is roughly $115–135B annualized.
- MIT NANDA study (2025): "95% of organizations got zero return" from gen-AI pilots. The sample for that figure was 52 organizations, and MIT Technology Review notes the study was more nuanced than the headlines — [Yale SOM](https://insights.som.yale.edu/insights/this-is-how-the-ai-bubble-bursts); [MIT Technology Review, Dec 15 2025](https://www.technologyreview.com/2025/12/15/1129183/what-even-is-the-ai-bubble/)
- An academic synthesis (arXiv, June 2026) calls AI "a real technological revolution with localized bubble dynamics" — [arXiv 2606.01575](https://arxiv.org/html/2606.01575v1)
- Risks flagged by skeptics: compute provisioned ahead of proven monetization, circular vendor financing, and valuations that assume today's growth persists — [datadeep.tech](https://datadeep.tech/ai-bubble-or-infrastructure/); [The Register](https://www.theregister.com/2026/01/14/ai_investment/)

### Inferences
- Near-term (through 2027), demand appears to outrun supply because power-gated buildouts lag. A glut is most plausible after power constraints ease and Rubin-generation supply lands (2027–2028), or if one frontier lab's revenue stalls. Menlo's estimate that Anthropic and OpenAI alone are 25%+ of hyperscaler cloud revenue makes that a single point of failure.
- Measured ROI is bimodal. Coding and agents show huge spend growth (see Q4), while the median enterprise pilot shows weak returns. This supports "monetizers win" only for monetizers with proven workflows.

### Gaps
- No primary Sequoia 2025–2026 update was retrieved. No bank (GS, MS) capex-to-revenue gap estimate for 2026 was found.
- Stanford AI Index 2026 data was not retrieved.

## Q3. Historical analogs: fiber/telecom 2000–2002, railroads, electricity

### Takeaway
The fiber analogy fits the *financing* side (leveraged fixed-cost builders went bust while demand was real) but fits poorly on utilization: data-center vacancy is about 1% today versus 2–5% lit-fiber utilization in 2001–2002. The historical lesson is that value flowed to firms that used cheap capacity to build demand-aggregating applications, not to the builders. Those firms were mostly horizontal platforms, not specific verticals.

### Cited Findings
- 2001 fiber glut: the "2.7% lit" figure is a June 2001 Merrill Lynch estimate and was disputed at the time. The FDIC in June 2002 cited about 2–5% utilization — [Dark Fiber archaeology (technostatecraft)](https://www.technostatecraft.com/p/dark-fiberan-archaeology-of-the-dot); [iwpfinance case study](https://iwpfinance.com/case-studies/telecom-fiber-bubble-2000)
- Dense wavelength-division multiplexing (DWDM) multiplied capacity on already-laid fiber, so efficiency gains created supply without new cable. The AI analog is model and inference efficiency (token-price deflation; see Q1) — [iwpfinance](https://iwpfinance.com/case-studies/telecom-fiber-bubble-2000); [coastaljournal "Dark Compute"](https://coastaljournal.substack.com/p/ais-dark-compute-moment-efficiency)
- Lesson: fiber was mostly a fixed cost, so carriers winning a fraction of projected traffic still paid for the whole network. "A real demand exponent does not protect you from a faster supply exponent." — [syncretica (Alex Turnbull)](https://syncretica.substack.com/p/the-second-photonic-shock); [trmcdonald substack](https://trmcdonald.substack.com/p/the-ai-booms-dark-fiber-moment-when)
- Counterpoint: AI data-center vacancy is about 1% (JLL, Aug 2026). A 2026 retrospective argues the 2001 problem was a glut of fiber *providers* rather than of fiber — [cycledesk](https://cycledesk.substack.com/p/internet-bubble-vs-todays-ai-buildout)

### Inferences
- Applying the analog: the 2001-style losers would be leveraged pure-play capacity owners (neoclouds with high-yield debt and long-dated backlog), not NVIDIA directly. NVIDIA is more like Cisco, whose revenue fell sharply but which survived. The winners post-2002 (Google, Amazon, Netflix; later Facebook) were horizontal aggregators of consumer demand. By analogy, the AI equivalents are model labs and horizontal agent and software platforms, which argues *against* narrowing the thesis to healthcare, robotics and defense.
- GPU depreciation is much faster (roughly a 3–6 year useful life) than fiber (decades) or rail. A GPU "glut" would therefore be shorter-lived and generation-specific (cheap H100s), less like a decade of cheap bandwidth. Microsoft extending data-center *building* lives to 25 years (see Q1) applies to shells, not chips.

### Gaps
- No sourced quantification was retrieved for railroad (1840s UK, 1870s–1890s US) or electricity analogs, or for exactly how Google and Amazon bought distressed fiber or data-center assets after 2001. The report writer should treat these as general-knowledge framing, not cited facts.

## Q4. Where is application-layer value capture actually showing up?

### Takeaway
Application revenue is real and growing fast, but it is concentrated in coding and horizontal assistants, and most of it is captured by the model labs themselves. Healthcare is the largest *vertical*, yet tiny in absolute terms ($3.7B vs $34B for coding). Robotics and defense show up as venture capital flows, not yet as AI-software spend. The thesis's claim that these three verticals are the *biggest* beneficiaries is not supported by current revenue data.

### Cited Findings (all from Menlo Ventures, Nov 3, 2026 — [link](https://menlovc.com/perspective/2026-the-state-of-enterprise-ai/))
- Deployment spend of $176.8B splits into infrastructure (inference, inference platforms, agent infrastructure) at $99.5B (56%) and applications at $77.3B (44%, up from $19B in 2025, about 4x).
- Coding: $34.0B (+7.7x), about 44% of app spend. Anthropic Claude Code plus OpenAI Codex take $24.0B (70%), and independent coding companies take $10.1B.
- Enterprise chatbots and assistants: $25.0B (+3.0x). Coding and chatbots together are 76% of app spend.
- Horizontal departmental apps: $8.8B (+3.0x). Customer success is $2.7B, IT $1.6B, sales $1.4B, marketing $1.2B and HR $0.9B.
- Vertical AI: $10.1B (+2.9x from $3.5B). **Healthcare: $3.7B (+2.5x), 37% of vertical spend, the largest vertical.** Legal is $1.8B (+2.8x).
- API share of LLM spend: Anthropic 55% (up from 40%), OpenAI 31%, Google 9% (down from 21%), open-source 4%.

### Inferences
- In the "monetize compute" layer, the largest monetizers today are the frontier labs (selling coding agents and assistants), followed by horizontal software. Vertical AI combined ($10.1B) is about 6% of deployment spend. Robotics and defense do not appear as enterprise AI-software spend categories in Menlo's data.
- Healthcare is the best-evidenced of the three named verticals: it is the largest vertical, growing 2.5x, but from a small base, with regulatory and reimbursement friction.
- Plausible alternative or additional beneficiaries with stronger revenue evidence: software and coding agents, customer support, and legal. Finance, drug discovery, industrial and energy were not separately quantified in the sources retrieved.

### Gaps
- No 2026 revenue data was retrieved for public robotics or defense AI monetizers (e.g., Palantir, Anduril revenue, Tesla Optimus). Defense AI procurement budgets (DoD AI and autonomy lines) were not retrieved.
- Stanford AI Index 2026 adoption data was not retrieved.

## Q5. Venture and private investment flows by sector, 2024–2026

### Takeaway
AI absorbed about two-thirds of global VC in Q3 2026 and about 83% of US deal value year to date, dominated by labs and infrastructure mega-rounds. Robotics and defense tech are at record funding levels in 2026, which validates investor *belief* in physical-world AI. Healthcare/digital-health funding is steady but not booming. Capital flows partly support the thesis for robotics and defense, but those flows are themselves a hype signal (valuations tripling in months).

### Cited Findings
**AI share of venture**
- Crunchbase Q3 2026: global venture about $159B, of which AI took about $102B (64%), down from 80% in Q1 2026. There was a record 27 rounds of $1B+ in Q3. The drop is attributed to OpenAI and Anthropic not raising in Q3 — [techjacksolutions](https://techjacksolutions.com/ai-brief/ai-startup-funding-102b-q3-2026-crunchbase/); [aibacon](https://aibacon.net/posts/crunchbase-q3-2026-venture-funding-159b-record-27-billion-dollar-rounds-ai-share-64-percent-100m-seed-rounds.html) [secondary summaries of Crunchbase]
- PitchBook-NVCA (US): AI was 65.9% of Q3 2026 deal value, versus 84.1% in Q2 and 88.4% in Q1. YTD through September it is 82.7% (a record). AI accounts for about 44.9% of US deal *count* — [aitechmodel](https://aitechmodel.com/ai-venture-funding-share-q3-2026/) [secondary]
- No source split AI venture into "apps vs infrastructure" for 2026. Menlo's spend split (56% infrastructure / 44% apps) is a proxy for spend, not for VC.

**Robotics**
- Crunchbase (June 22, 2026): robotics startups raised $18.8B globally in 2026 YTD, versus $15B for all of 2025 (the prior record) and $14.1B in 2021 — [Crunchbase News](https://news.crunchbase.com/robotics/startup-venture-funding-surges-2026-data/)
- Top 2026 rounds:
  - Saronic (defense autonomous vessels): $1.75B Series D at $9.25B, more than 2x its 2025 valuation.
  - Skild AI: $1.4B (SoftBank, NVentures); valuation above $14B, up from $4.5B about 7 months earlier.
  - Neura Robotics: up to $1.4B.
  - Shihang Intelligent: $1B Series A.
  - Apptronik: $520M extension.
  - Mind Robotics (Rivian spinout): $500M + $400M.
  - Unitree filed for a Shanghai IPO (target valuation $3–7B).
  - [Crunchbase News](https://news.crunchbase.com/robotics/startup-venture-funding-surges-2026-data/)

**Defense tech** (PitchBook; definitions vary, broad dual-use vs narrow defense-specific)
- Q1 2026: record $19.8B across 262 deals (another PitchBook release says $24.4B). Q2 2026: $16.4B across 249 deals. H1 2026: $35.4B across 415 deals (Q2 First Look) — [PitchBook Q1 2026](https://pitchbook.com/news/reports/q1-2026-defense-tech-vc-trends); [PitchBook Q2 2026 report](https://pitchbook.com/news/reports/q2-2026-defense-tech-report-go-big-or-go-early-in-the-sectors-barbell-market); [PitchBook Q2 First Look](https://pitchbook.com/news/reports/q2-2026-defense-tech-vc-first-look)
- Q3 2026 First Look: defense-specific startups hit a quarterly record of $2.5B (more than 4x Q2's $563.4M, narrow definition). Broad-definition YTD is cited at $67.4B across 726 deals (unverified scope) — [PitchBook Q3 2026 First Look](https://pitchbook.com/news/reports/q3-2026-defense-tech-vc-first-look)
- PitchBook headline "The Iron Bubble: Why defense tech might not be overhyped" (bull framing) — [PitchBook](https://pitchbook.com/news/articles/the-iron-bubble-why-defense-tech-might-not-be-overhyped)
- Helsing raised a $1.8B Series E at an $18B valuation (2026, secondary). The last confirmed Anduril round found was a $2.5B Series F at $30.5B (June 2025, older); no 2026 Anduril round was found — [valueaddvc](https://valueaddvc.com/pulse/physical-ai-defense-robotics-record-funding-2026) [secondary]

**Healthcare**
- Rock Health: US digital-health funding was $3.7B across 114 deals in Q3 2026, and $11.1B across 358 deals YTD. In 2025, AI-enabled companies took 54% of $14.2B. Rock Health stopped tracking a separate AI category in 2026 — [Rock Health Q3 2026](https://rockhealth.com/insights/q3-2026-market-update-crystallizing-fifteen-years-of-digital-health/)
- Notable 2026 healthcare-AI rounds: OpenEvidence $250M Series D at $12B; Trase $107M seed; Science (brain-computer interface) $400M (Nov 2026) — [crescendo.ai](https://www.crescendo.ai/news/latest-vc-investment-deals-in-ai-startups) [secondary]; [Crunchbase News](https://news.crunchbase.com/robotics/startup-venture-funding-surges-2026-data/)
- One aggregator: biotech/healthcare AI was $5.4B in Q1 2026, up from $3.2B (unverified) — [nexairi](https://nexairi.com/article/Technology/startup-funding-q1-2026-ai-robotics/) [secondary]

### Inferences
- Rough 2026 scale: robotics VC (≥$18.8B by June) and broad defense tech (≥$35B by H1) are each several times US digital-health VC (about $11B YTD). Capital is flowing hardest into physical and defense AI, and least into healthcare. Yet healthcare has the most measurable AI software *revenue* of the three. This mismatch is worth flagging: robotics and defense valuations are running ahead of revenue (Skild tripled in 7 months; Saronic more than doubled in a year).
- Defense has a structural demand driver (government budgets, European rearmament) that is independent of a compute glut. Its link to cheap compute is indirect: autonomy and edge inference matter more than datacenter $/hr.
- Robotics benefits from cheap compute for training (simulation, foundation models), but deployment economics depend on hardware cost and reliability, not GPU rents.

### Gaps
- No primary Crunchbase or PitchBook 2024 comparison by sector, and no CB Insights 2026 data, was retrieved. 2024 baselines are missing.
- PitchBook defense figures conflict ($19.8B vs $24.4B for Q1; narrow vs broad scope). Cite with scope.
- No 2026 healthcare-AI-specific VC total from a primary source.
