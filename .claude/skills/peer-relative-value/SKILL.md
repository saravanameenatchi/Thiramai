---
name: peer-relative-value
description: Find the most undervalued stock within a properly built peer group, explain WHY it is cheap, separate genuine mispricing from value traps, and check positioning so we avoid crowded trades. Use when the user asks for "the cheapest/undervalued stock among peers", "which is better X or Y", "alternatives to <crowded stock>", or as step 6 of stock-research.
---

# Peer-Relative Value & Anti-Crowding

**Core idea:** we want the stock the market is *underpricing relative to its quality and growth*, that
is **not** already owned by everyone. Cheap alone is not enough; cheap + improving + unloved is the target.

---

## Step 1 — Build the right peer set (most errors happen here)
- Group by **business model and economic drivers**, not by industry label. E.g., compare a
  custom-ASIC designer with other ASIC/networking designers, not with a memory maker.
- 5–10 peers, including: direct competitors, same-layer value-chain companies, and 1–2 "what the
  market will compare it to" names.
- Include **second-order beneficiaries** (suppliers to the suppliers of the crowded winner) — that's
  where under-owned growth often hides.
- Note size, geography, and listing discount (ADR, emerging-market, holding-company) differences.

## Step 2 — Normalize, then compare
Collect for every peer (source + date for each):
- Growth: next-2-year revenue and EPS CAGR (consensus), 3-year historical.
- Quality: gross margin, operating margin, ROIC, FCF margin (after stock-based comp), net debt/EBITDA.
- Valuation: forward P/E, EV/EBIT, EV/Sales, EV/Gross profit, FCF yield; sector-specific metric.
- Revisions: 90-day change in next-year EPS estimate.
- Volatility: 1-year realized vol, beta.

Growth-adjusted views (use at least two):
- **PEG** (fwd P/E ÷ EPS growth) — only for profitable, non-cyclical growth.
- **EV/Gross profit ÷ revenue growth** — for software and high-growth names.
- **Regression residual:** plot EV/Sales (or EV/EBIT) vs (growth + margin) across peers; the stocks
  *below the line* are cheap for their fundamentals. Report the residual in %.
- **Z-score vs own 5-year history** and **vs peer median**.

## Step 3 — Explain the discount (mandatory)
Every cheap stock is cheap for a reason. Classify the reason:
| Reason | Type | Action |
|---|---|---|
| Temporary issue (one bad quarter, inventory digestion, one-time charge) | Fixable | Opportunity if fundamentals intact |
| Market misunderstanding (hidden segment, mis-classified, poor disclosure, too small for coverage) | Mispricing | **Best opportunity** — find the catalyst that reveals it |
| Structural decline (losing share, disrupted by AI, patent cliff, secular volume decline) | Structural | Value trap — avoid |
| Peak-cycle earnings (low P/E at record margins) | Cyclical | Trap unless supply discipline is proven |
| Governance / jurisdiction / dilution | Persistent | Discount likely stays; require bigger margin of safety |

## Step 4 — Value-trap checklist (fail ≥2 → avoid)
- Estimates falling over 90 days
- Market share or profit-pool share falling
- Gross margin falling with no cost explanation
- FCF < net income persistently, or rising debt to fund dividends/buybacks
- Industry capacity growing faster than demand
- No identifiable catalyst within 18 months

## Step 5 — Crowding & positioning check (avoid becoming exit liquidity)
Score each 0 (not crowded) – 2 (very crowded):
- **Hedge-fund concentration:** appears among top hedge-fund holdings / prime-broker "VIP" baskets; rising 13F ownership.
- **Sell-side consensus:** % Buy ratings (>85% = crowded), price targets clustered just above price.
- **Retail & options:** heavy call volume, high retail flows/mentions, leveraged single-stock ETFs exist.
- **Valuation vs own history:** above 90th percentile.
- **Price extension:** far above 200-day moving average; parabolic 3-month move.
- **Short interest:** very low (no skeptics left) — or extremely high (squeeze-driven, not fundamental).
- **Narrative saturation:** the thesis is the headline on every financial media outlet.

Total 0–4 = under-owned (good) · 5–8 = normal · 9–14 = crowded → require a larger margin of safety,
smaller size, or look for the second-order beneficiary instead.

*Context:* crowded AI positioning amplified drawdowns in 2026 when funds de-grossed at the same time —
crowding is a **risk factor**, not just a sentiment note.

## Step 6 — Pick the winner
Sweet spot = **below the peer regression line + discount explained as Fixable/Mispricing + estimates
stable or rising + crowding score ≤ 8 + moat score ≥ 3.**

## Output
```
Peer set (and why): ...
Table: Ticker | Growth | Margin | ROIC | Fwd P/E | EV/GP or EV/EBIT | Growth-adj. multiple | Residual % | 90d EPS rev. | Crowding score
Most undervalued (quality-adjusted): <ticker> — discount reason: <type>, catalyst: <...>
Runner-up / less-crowded alternative to the consensus favourite: <ticker>
Value traps in the group: <tickers + failed checks>
Relative-valuation score (0–5) and Positioning score (0–5) for stock-research scorecard
```
