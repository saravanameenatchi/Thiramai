---
name: stock-research
description: Master workflow for researching any listed stock in any sector (AI/semis, software, healthcare, consumer staples, industrials, financials, energy). Use before answering ANY question about whether a stock is worth buying, holding, or avoiding, or when comparing stocks. Applies regime-aware "golden rules" instead of textbook rules, then calls moat-analysis, peer-relative-value, and (for private or newly listed companies) early-stage-investing.
---

# Stock Research — Golden Rules for the Contemporary Market

**Goal:** find fundamentally solid, high-growth businesses (AI era first, but any sector) that are
**undervalued relative to their true peers**, have a **durable moat**, and are **not a crowded trade**.

Textbook rules are inputs, not answers. A rule only applies if the conditions behind it are true
today. Every rule below says *when it applies* and *when it breaks*.

---

## 0. Non-negotiables (data discipline)

1. **Fetch live data. Never guess numbers.** Every price, multiple, estimate, or market-share figure
   must have a **source and an as-of date**. If you cannot verify a number, say "unverified" instead of
   making one up.
2. **Separate facts, estimates, and opinions** in the report.
3. **State the thesis-breaker up front:** the 2–3 observable events that would prove the thesis wrong.
4. This is research support, not personal financial advice. Always flag position-sizing and risk.

---

## 1. The Golden Rules

### Rule 1 — Price what the market already believes, not what the textbook says
Ask: *"What growth and margins are already priced in, and what must happen for the stock to beat
that?"* Run a **reverse DCF** (solve for the growth the current price implies). Edge exists only where
your view is different from the implied view **and** you can say why.

### Rule 2 — A low P/E is not cheap. Check where you are in the cycle.
- For **cyclicals** (memory like MU, foundry, semicap, commodities, autos, chemicals), the P/E is
  **lowest at peak earnings and highest at the trough.** A single-digit forward P/E on record margins
  often means the market expects earnings to fall.
- Use **normalized / through-cycle earnings** (5–7 year average margin × current revenue), EV/Sales
  vs history, and price-to-book for memory.
- Track **supply signals**: industry capex growth, inventory days (company and customers), contract
  vs spot prices, lead times. Rising capex + rising inventory = late cycle, even if the P/E looks cheap.
- **When it breaks:** if demand has truly become secular (long-term contracts, prepayments, capacity
  sold out years ahead), the cycle can stretch. Require *evidence* (contract terms, customer
  prepayments), not a narrative that "this time is different."

### Rule 3 — Low P/E + high volatility = the market doubts how long the earnings will last
NVDA, TSM, and MU can look cheap on forward P/E and still swing ±30% because the risk is about
**how long earnings last**, not how big they are today. Price these risks explicitly:
- **Customer concentration** (top-5 customers as % of revenue; hyperscaler capex dependence).
- **Capex funding:** is AI capex paid for by customers' operating cash flow, or by debt and vendor
  financing? Rising leverage or circular financing raises fragility.
- **Geopolitics/policy:** export controls, tariffs, Taiwan risk, drug-pricing rules.
- **Positioning:** crowded hedge-fund ownership makes drawdowns faster (see peer-relative-value).
Adjust the hurdle: required return ↑ when these are high, so the "fair" P/E is lower than it looks.

### Rule 4 — Estimate revisions beat the multiple
Stocks follow **the direction of earnings revisions** more than how high or low the P/E is. Track the
30/90-day change in next-year EPS and revenue estimates. Best setup: **cheap vs peers + estimates
rising**. Worst setup: **cheap + estimates falling** (a value trap).

### Rule 5 — Use the right metric for the business model
One metric does not fit every sector. Use the sector map in
`references/sector-playbooks.md`. Summary:
| Business type | Primary metrics | Avoid relying on |
|---|---|---|
| High-growth software | EV/Gross profit ÷ growth, Rule of 40, net revenue retention, FCF margin after stock-based comp | P/E (often negative or distorted) |
| Semis (non-memory) | EV/EBIT vs growth, gross-margin trend, design wins, share of the bottleneck | Trailing P/E at peak |
| Memory / commodity semis | P/B, normalized EPS, capex/sales, pricing | Forward P/E at peak |
| Pharma / biotech | Risk-adjusted pipeline NPV, patent cliff timeline, peak-sales share | P/E alone |
| Consumer staples | Organic volume vs price/mix, FCF conversion, dividend coverage, share vs private label | Headline revenue growth (price-led) |
| Banks / insurers | P/TBV vs ROTE, credit costs, combined ratio | EV/EBITDA |
| Energy / materials | FCF yield at strip prices, cost-curve position, reserve life | Peak-cycle P/E |
| REITs / utilities | AFFO/FFO yield, rate-base growth, balance sheet | EPS |

### Rule 6 — Growth only creates value when ROIC > cost of capital
A company growing 30% with ROIC below its WACC destroys value. Require **ROIC (or ROIIC — return on
incremental invested capital) above WACC, sustained or rising.** This is the numerical proof of a moat.

### Rule 7 — Bottlenecks capture the profits
In every technology build-out, profits go to whoever controls the scarce input *right now*
(compute → advanced packaging → HBM → networking → power/grid → cooling). Map the value chain,
find the **current and next bottleneck**, and prefer companies whose pricing power is rising.
Re-check every quarter; bottlenecks move.

### Rule 8 — Distinguish AI winners, AI enablers, and AI victims
For every company, in any sector, answer: does AI **raise** its revenue, **lower** its costs, or
**threaten** its business (seat-based SaaS, content, outsourcing, search)? A defensive staple that
uses AI to cut SG&A by 200 bps can beat an "AI stock" that is already priced for perfection.

### Rule 9 — No variant view, no edge
If your thesis matches the sell-side consensus and the top hedge-fund holdings, you are paying for
what everyone already knows. Write down your **variant perception** in one sentence: what you
believe that the market doesn't, and the evidence for it. If you cannot, the answer is "watchlist, not
buy."

### Rule 10 — Respect the regime
Score the macro regime before stock-level conclusions: interest rates and real yields (hurt long-
duration growth stocks), liquidity, USD, credit spreads, AI capex cycle stage, and sector-specific
policy. The same stock deserves a different multiple in a different regime.

### Rule 11 — Volatility decides position size, not just whether to own it
A great business with 60% annualized volatility deserves a smaller position than a steady compounder.
Report beta, 1-year realized volatility, and max drawdown in the last 3 years, and suggest a
volatility-adjusted size tier (core / satellite / starter).

### Rule 12 — Write the exit before the entry
Every thesis gets: (a) 3 KPIs to monitor each quarter, (b) a thesis-breaker list, (c) a valuation
level where the upside is used up.

---

## 2. Workflow (run in order)

1. **Classify** the company: sector, business model, cycle exposure, AI exposure (winner, enabler,
   victim, or neutral).
2. **Regime check** (Rule 10) — one paragraph.
3. **Business quality:** revenue growth (3y CAGR + next 2y est.), gross/operating margin trend,
   ROIC vs WACC, FCF conversion (FCF/net income), SBC % of revenue, net debt/EBITDA.
4. **Moat** → run the `moat-analysis` skill. Output: moat sources, width, trend, "best despite
   competition?" verdict.
5. **Valuation** → sector-appropriate metrics (Rule 5), reverse DCF (Rule 1), cycle check (Rule 2).
6. **Peer-relative value + crowding** → run the `peer-relative-value` skill.
7. **Durability risk** (Rule 3) and **revisions** (Rule 4).
8. **Variant perception + catalysts** (Rule 9): what event within 6–18 months makes the market agree with you?
9. **Score** using the scorecard below and write the report.

For private companies, pre-IPO names, or recent small/mid-cap IPOs, also run `early-stage-investing`.

---

## 3. Scorecard (0–5 each; weights adapt by sector)

| Factor | What earns a 5 | Growth/AI weight | Defensive weight |
|---|---|---|---|
| Moat (width + trend) | Wide and widening, shows in ROIC | 20% | 20% |
| Growth quality | Durable, high-ROIIC, not cycle-inflated | 20% | 10% |
| Financial strength | Net cash or low leverage, FCF positive | 10% | 20% |
| Relative valuation | Cheapest growth-adjusted in the right peer set, explainable discount | 20% | 20% |
| Revisions / momentum of fundamentals | Estimates rising over 90 days | 15% | 10% |
| Positioning (inverse crowding) | Under-owned, skeptical consensus, improving | 10% | 10% |
| Durability risk (inverse) | Diversified customers, low policy/cycle risk | 5% | 10% |

**Verdict bands:** ≥4.0 High-conviction candidate · 3.3–3.9 Buy on weakness / starter ·
2.5–3.2 Watchlist · <2.5 Avoid. A **0 or 1 on Moat or Financial strength vetoes** a buy regardless of total.

---

## 4. Report template

```
# <TICKER> — <Company> | as of <date>
**Verdict:** <band> | Score x.x/5 | Suggested size tier: <core/satellite/starter/none>
**One-line thesis (variant view):** ...

## Snapshot
Price, market cap, EV, fwd P/E, EV/Sales, FCF yield, 3y rev CAGR, ROIC, net debt — each with source/date

## Regime & cycle position
## Business quality
## Moat (from moat-analysis) — sources, width, trend, verdict vs competition
## Valuation — sector metrics, reverse-DCF implied growth, normalized view
## Peer-relative value (from peer-relative-value) — table + why the discount exists
## Crowding & positioning
## Durability risks — concentration, capex funding, policy, volatility
## Catalysts (6–18m)
## Thesis-breakers & KPIs to monitor
## Bull / Base / Bear (price or return ranges with key assumptions)
## Sources
```

---

## 5. Common traps (check every time)
- Buying a cyclical at a single-digit P/E on peak margins.
- Treating "competition is coming" as automatic moat loss (see LLY example in moat-analysis).
- Comparing against the wrong peers (GICS ≠ business model).
- Ignoring stock-based compensation in "FCF".
- Price-led revenue growth in staples hiding falling volumes.
- Owning the top-10 hedge-fund holding because "everyone is in it."
- Mistaking a story stock with no revenue for an early-stage venture bet without venture-style sizing.
