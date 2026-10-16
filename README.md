# What-Moves-Broad-Money-Evidence-from-Five-Asian-Economies
<!-- Repo settings
About: Interactive dashboard for a thesis on how FDI, interest rates and trade openness relate to broad money in five Asian economies (2011-2023).
Topics: economics, thesis, panel-data, monetary-economics, broad-money, fdi, asia, data-visualization, dashboard, javascript
Tip: rename Thesis_BroadMoney_Dashboard.html to index.html and enable GitHub Pages to get a live demo link.
-->

# Broad Money in Five Asian Economies

Interactive companion to a thesis on **FDI, interest rates and trade openness** versus **broad money (% of GDP)** in Indonesia, Malaysia, the Philippines, Thailand and Vietnam, **2011-2023**.

**Live demo:** `https://aryautra.github.io/What-Moves-Broad-Money-Evidence-from-Five-Asian-Economies/`

## What it does
- **Step-by-step hypotheses:** each relationship shown as a numbered chain from cause to effect, with its expected direction (FDI positive, interest rate negative, trade openness positive).
- **Two lenses on the evidence:** correlations across all country-years and within each country over time.
- **Plain-language summary:** how often broad money moved as theory expects in year-to-year changes, plus r with an explanation.
- **Country vs country** comparison against the five-country average, with animated year-range zoom and a highlight-year marker that shows exact values.

## What the data shows
- **Interest rate:** negative link across countries (r = -0.46) and within countries (r = -0.62), and broad money moved the opposite way in 33 of 45 year-to-year changes.
- **FDI:** no clear link across countries (r = -0.17), but a positive link within countries over time (r = +0.41).
- **Trade openness:** strong in levels (r = +0.90 across, +0.54 within), yet year-to-year changes agreed with theory in only 26 of 60 cases.
- **Why it matters:** the answer depends on the lens, so levels and changes, and between-country and within-country variation, should be read separately. Correlation is not causation.

## Presentation
`BroadMoney_Thesis_Deck.pptx` summarizes the dashboard, the problems it reveals and the relationships between variables.

## Data
65 observations (5 countries x 13 years): broad money (% of GDP), FDI net inflows (log of US$), policy interest rate (%), trade openness (% of GDP). Sources: World Bank and central banks.

## Run it
Open `Thesis_BroadMoney_Dashboard.html` in any browser. No install, no dependencies, works offline.

## Skills demonstrated
Turning theory into testable hypotheses, separating between-country from within-country variation, communicating statistics in plain language, interactive dashboard design. Next step: panel regression with fixed effects.
