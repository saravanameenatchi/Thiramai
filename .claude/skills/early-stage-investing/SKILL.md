---
name: early-stage-investing
description: Think like a top venture capitalist or crossover institutional investor evaluating a company early (seed through pre-IPO), as investors did with Anthropic and Anduril. Use for private companies, recent IPOs, small/mid-caps with venture-like profiles, public proxies for private winners, or when the user asks "how would a VC evaluate this", "what makes a future category leader", or "find the next Anthropic/Anduril".
---

# Early-Stage / Venture-Style Investing

Public-market analysis asks "is it cheap vs what it earns?" Venture analysis asks
**"if this works, how big can it get, and why will THIS team win?"** Returns follow a **power law**:
one winner returns the whole portfolio, so the question is the size of the upside if it succeeds, not
how likely a modest outcome is.

---

## Step 1 — The VC decision framework

| Lens | Key questions | Strong signal |
|---|---|---|
| **Founders & team** | Founder–market fit? Have they done the hard thing before? Can they recruit the best people? | Team with unique insight from building the core technology; top talent leaving big companies to join |
| **Why now** | What changed (technology, cost curve, regulation, geopolitics) that makes this possible now and not 5 years ago? | A clear inflection, e.g., scaling laws making large models valuable; geopolitical urgency + cheap autonomy/sensors |
| **Market size (end-state)** | If it wins, could it be a $100B+ company? Is the market new or taken from incumbents? | Huge spend pool being re-platformed |
| **Secret / insight** | What does the team believe that most people don't? (Thiel's "secret") | Contrarian but evidence-backed view |
| **Counter-positioning** | Why can't incumbents copy it without hurting themselves? | Incumbent business model punishes copying |
| **Moat path** | Which of the 7 Powers will it own at scale? | Data/talent/compute cornered resource, network effects, switching costs |
| **Capital & unit economics** | How much capital to reach escape velocity? Gross margin path? | Capital intensity justified by the winner-take-most structure |
| **Traction proof** | Revenue run-rate growth, design partners, pilots converting to contracts, retention | Multiple-x annual revenue growth with enterprise logos |
| **Syndicate & follow-on** | Who is investing, and do insiders keep buying in later rounds? | Tier-1 investors leading/follow-on each round; strategic investors |

## Step 2 — Case patterns (verify specifics with current sources)

**Anthropic (founded 2021, AI foundation models)**
- *Team:* founders came from the group that built leading large language models and published
  scaling-law research — founder–market fit at the frontier.
- *Thesis used by early investors (e.g., Menlo Ventures, investing pre-product/pre-revenue):* there was
  room for **another independent foundation-model company**, and this was the team to build it.
- *Differentiation:* safety and reliability as a product feature → enterprise trust; strength in
  enterprise and developer/coding use cases.
- *Cornered resources:* elite research talent; strategic compute partnerships with hyperscalers
  (Amazon, Google) that also act as distribution.
- *Why it works for a VC:* oligopoly market structure at the frontier (few can afford the compute) +
  enormous end-market (every software workflow) = power-law outcome.
- *Risks VCs accepted:* extreme capital intensity, compute cost, commoditization of models.

**Anduril (founded 2017, defense technology)**
- *Team:* a founder who had built and sold a hardware company, plus a partner from a leading venture firm and
  experienced engineers — technical + capital-markets + government-procurement fluency.
- *Counter-positioning:* traditional defense primes earn on **cost-plus contracts**; Anduril builds
  products **with its own money** and sells finished products — incumbents can't copy without
  cannibalizing their model.
- *Software core:* a common autonomy/command platform (Lattice) across many hardware products →
  software-like margins and switching costs over time.
- *Why now:* geopolitical competition, cheap sensors/compute/autonomy, procurement reform pushing for
  new entrants.
- *Syndicate:* early backers (Founders Fund; General Catalyst from the 2017 seed) kept following on.

**Common pattern:** exceptional, insider-level team + clear why-now + structurally huge market +
counter-positioning vs incumbents + a path to a cornered resource. Price paid mattered far less than
picking the category winner.

## Step 3 — Apply it to public markets
1. **Recent IPOs / small-mid caps:** score them on the framework above *and* run stock-research
   (dilution, lock-up expiries, cash runway, SBC).
2. **Public proxies for private winners:** listed companies that own stakes in, supply, or are the
   main distribution partner of a private leader. Check how material the exposure is to *their* value.
3. **Pre-IPO access caveats:** secondary-market prices, SPVs and tokenized exposure often carry high fees,
   information gaps, and transfer restrictions — flag these clearly.
4. **Sizing:** venture-style bets get venture-style sizing — small positions, portfolio of several,
   accept that most may fail.

## Step 4 — Red flags
- Founder can't explain the "secret" or why-now in one sentence
- Growth driven by subsidized pricing with negative gross margin and no path to fixing it
- Down-round or insiders not participating in follow-on rounds
- Customer concentration in pilots that never convert
- Valuation that assumes the best outcome with no plan for capital intensity
- Category with no winner-take-most dynamics (a commodity in disguise)

## Output
```
Company / stage / last valuation (source, date)
Founders & team (score 0–5) | Why now (0–5) | Market end-state (0–5) | Insight/secret (0–5)
Counter-positioning & moat path (0–5) | Traction (0–5) | Capital efficiency (0–5) | Syndicate quality (0–5)
Power-law case: what does the company look like in 10 years if it wins?
Key risks and what would kill it
Public-market way to get exposure (if any) and how material it is
Verdict: Category-leader candidate / Interesting, needs proof / Pass
```
