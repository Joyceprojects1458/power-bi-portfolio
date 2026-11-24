# Bayline Retail Dashboard — Part C findings draft
Started Nov 22, 2026 — Joyce's own findings, in her words where she gave them. All four Part B pages are now built (Nov 23) — this draft feeds the Part C write-up.

## Sales page (finished Nov 22)
- Net Sales last 12 months total: $408,427,108 (matches the $408M verified in Part A5).
- Women's Apparel is the #1 department in sales; Home is #2 (about $105M).
- Weakest store per square foot: Watsonville, at $158.50 per sq ft (store table sorted low → high).
- Gross Margin % overall: 25.6%. Markdown % overall: 14.6%.
- Target GM % vs Gross Margin % by department: pairs are close everywhere; Home's actual sat visibly below its target — and the Inventory summary table later confirmed this chart was RIGHT (Home −2.2%).

## Inventory page (finished Nov 22)
Joyce's finding, sharpened in discussion Nov 22:
> "Home sells well but is overstocked — buying outpaced sales. Accessories and Beauty carry lean stock that turns over fast."

Supporting numbers:
- Weeks of Supply: all departments ran 8–12 weeks through 2025, with a synchronized dip at Christmas 2025. From about March 2026, Home broke away and climbed to about 17 weeks (9.7 → 16.9 in the verified A5 checks) while the others stayed flat.
- Sell-Through %: Home slid 33.9% (Aug 2025) → 22.9% (Aug 2026).
- Markdown %: chain-wide, every department sat at about 14–17% through 2025 (the lines overlap — one chain-wide habit). In early 2026 Home broke away and climbed to about 27%. Cause and effect: backed-up inventory is cleared by discounting, so the markdown rise is the cost of the overstock.
- Gross Margin % — Home only, with 22% target line (CORRECTED Nov 22 evening): Home ran just UNDER its 22% target through 2025 (about 20–22%), then slid steadily through 2026 to roughly 8–9% by August 2026 as markdowns climbed. Home's all-weeks Gross Margin % is 19.8% vs the 22% target = −2.2%, the biggest miss of any department.
  - How the wrong reading happened: the chart's first visual-level filter used Department from the wrong table, so it drew the whole CHAIN's monthly margin (23–27.5%) instead of Home's. Same Departments-table lesson as A5 — a filter must come from the Departments dimension table, including a chart's visual-level filter. The small Sales-page chart (Home below target) was right all along.
  - Corrected sentence for the write-up: "Home ran just below its 22% margin target through 2025, then slid all through 2026 as markdowns climbed to clear the overstock."
  - Plain meaning of the target: of every $100 of Home goods sold, the company wants at least $22 left after paying for the goods themselves.
- Accessories and Beauty: leanest stock, about 8 weeks of supply — turns over fastest. Note: Beauty is the smallest department in dollars, so it is "lean and quick," not a top seller.
- Summary table (all weeks, unfiltered), GM % vs Target with green/pink rules: Accessories +0.2% and Beauty & Fragrance +0.1% beat their targets; Shoes exactly at target (0.0%); Women's Apparel −0.3%, Men's Apparel −0.5%, Kids −0.6% miss narrowly; Home −2.2% is the one big miss. Implied targets are round numbers (Accessories/Beauty 30%, Women's 28%, Men's 27%, Kids 26%, Shoes 23%, Home 22%). Home's full row: 17.9 weeks of supply (highest), 16.4% markdowns (highest — everyone else ~14.2%), 19.8% gross margin (lowest). One department, one story: overstock → discounting → margin below target.

## Labor page (finished Nov 23)
- Cards verified: Average Basket $37.14; Sales per Labor Hour $122.9968 (workbook key $123.02 — same ~0.02% loaded-data difference as the Average Basket cent; accepted); Overtime % 1.7%.
- Overtime % by month and region: four regions hug ~1.5% flat for all 20 months, holidays included. Central Valley rides a little high all year (~2%) and spikes to nearly 7% in Nov–Dec 2025 — the only region that handled the holidays on overtime. Reads as: Central Valley went into the season understaffed, or its seasonal hiring lagged.
- Sales per Labor Hour by store: the whole chain is tightly bunched, roughly $105–$135. Southern California (slicer check): Riverside highest, Long Beach lowest in the region; every SoCal store clears $100.
- Store table sorted low → high: Modesto is the chain's lowest at $105.06 per labor hour — and Modesto was also near the bottom for sales per square foot ($246.39 in the A5 checks). Two different yardsticks, same store: a pattern, not a blip.

## Returns and Shrink page (finished Nov 23)
- Cards verified: Return Rate % 7.6%; Shrink % of COGS 1.4% (about $6.8M of merchandise at cost over the 20 months).
- Return Rate % by month: a metronome — 7.6% flat for 20 months, except both Januaries spiking to ~10%: the post-Christmas returns wave, right on schedule two years running. Returns are a stable cost of business, not a worsening quality problem.
- Shrink % of COGS by department: Beauty & Fragrance highest at ~2.7% (nearly double the chain average), Accessories ~2.2% — the small, pocketable, high-value goods. Shoes ~1.65%; Women's / Men's / Kids apparel ~1.2%. Shrink is a small-goods problem.
- Return Unit Rate by department: Shoes #1 at 11.3% (matches the A5 check) — fit returns; apparel follows; Home near the bottom. (Unit rate counts items; the 7.6% card is the dollar rate.)
- Shrink $ by month, Bay Area stores: Antioch rides highest — the fictional data agreeing with Joyce's real-world rule about Antioch.

## Still to do (resume point)
1. Part C write-up (use this draft): C1 checks, C2 findings, C3 data-quality log, C4 one-page summary Word doc, C5 finish checklist.
2. Part D (RLS + PL-300 practice pages).
3. At the very end: hide (don't delete) scratch Page 1 / Page 2, stretch the small clustered column chart, number-format polish, and the separate plain-English formulas Word document.
