# Bayline Retail Dashboard — Power BI

My second Power BI project: a retail operations dashboard for Bayline Value Outlet, a fictional value retail chain with 40 stores and 7 departments. Weekly data, January 2025 to August 2026.

No real company information is included. This dataset is fictional, made up for portfolio practice.

## What this project answers

- How are sales, margin, and markdowns trending — overall and by department?
- Which stores are performing, and which are falling behind?
- Where is inventory piling up, and what is it costing in margin?
- Are stores staffed efficiently, and where does overtime spike?
- Where are returns and shrink concentrated?

## The 4 pages

1. **Sales** — net sales, markdown %, gross margin %, and year-over-year, by department and store
2. **Inventory** — weeks of supply and sell-through by department, margin vs target
3. **Labor** — sales per labor hour and overtime % by store and region
4. **Returns and Shrink** — return rates by department and shrink as % of COGS

## What I found

- **Headline growth flatters the chain:** Net sales are up 6.2% year over year for 2026, but comparable stores grew only 1.5% — most of the growth came from new stores.
- **Home is the margin problem:** Home's gross margin is 19.8% against a 22% target, the biggest miss of any department. Home sells fine — the problem is overstock. Weeks of supply climbed from 9.7 to 16.9 weeks, markdowns rose to clear the pile, and the discounting ate the margin.
- **Two stores lag:** Watsonville has the weakest sales per square foot ($158.50 — it is also a new store with a short history), and Modesto has the weakest sales per labor hour ($105 vs a chain average of about $123).
- **Holiday overtime is a Central Valley story:** Overtime ran about 1.9% most of the year, then spiked to nearly 7% in November–December 2025 in Central Valley while the other regions stayed flat.
- **Shrink lives in small, pocketable goods:** Beauty & Fragrance (about 2.7% of COGS) and Accessories (about 2.2%) lead the chain.
- **Shoes are the returns problem:** An 11.3% return unit rate, the highest of any department. Returns spike every January to about 10% after the holidays.

## Skills used

Power BI Desktop, Power Query data cleaning (duplicates, negative values, inconsistent department names), star-schema modeling with a marked date table, 31 DAX measures including year-over-year and like-for-like comparisons, conditional formatting, and synced slicers across pages.

## Files in this project

- Bayline_Retail_Dashboard_FINISHED.pbix — the Power BI file
- bayline-one-page-findings-summary.docx — one-page summary of the findings
