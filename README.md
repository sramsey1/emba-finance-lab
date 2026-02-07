# EMBA Finance Lab

Interactive financial model database for Ross EMBA coursework. Built with a dark theme, real-time calculations, and zero dependencies (pure HTML/CSS/JS + Chart.js).

**[Live Demo](https://sramsey1.github.io/emba-finance-lab/)**

## Models

### Fundamentals
- **Time Value of Money** — Present value, future value, annuity PV, and loan payment calculators with multiple compounding frequencies
- **Break-even Analysis** — Break-even units, revenue, and target profit calculations with interactive cost/revenue chart
- **WACC Calculator** — Weighted average cost of capital via CAPM cost of equity and after-tax cost of debt

### Valuation
- **DCF Model** — Discounted cash flow with 5-year projections, terminal value, enterprise value, sensitivity table (WACC vs. terminal growth), and Year 1 FCF waterfall chart
- **Comparable Company Analysis** — 3-company trading comps with editable financials, auto-calculated EV/Revenue and EV/EBITDA multiples, and implied target valuation
- **LBO Model** — Leveraged buyout returns calculator with entry/exit assumptions, IRR/MOM outputs, and debt vs. equity stacked chart over the holding period

### Financial Statements
- **3-Statement Model** — Linked income statement with 5-year projections driven by revenue growth, gross margin, and SG&A assumptions
- **Working Capital & Cash Conversion** — Cash conversion cycle calculator with DSO, DIO, and DPO

### Advanced
- **M&A Accretion/Dilution** — Full merger analysis with acquirer/target inputs, deal terms (cash/stock mix, premium), financing costs, synergies, and EPS accretion/dilution verdict

## Features

- Real-time calculations — every input updates all outputs instantly
- Sensitivity analysis tables with highlighted base case
- Interactive Chart.js visualizations (waterfall charts, stacked bars)
- Copy Table to clipboard for easy export to Excel
- Show/hide formula explanations for each model
- Keyboard shortcuts (1–9) to jump between sections
- Dark theme with Michigan maize and blue color scheme
- Mobile-responsive sidebar navigation
- Zero server-side dependencies — runs entirely in the browser

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for visualizations
- Deployed via GitHub Pages

## Getting Started

Clone the repo and open `index.html` in any browser:

```bash
git clone https://github.com/sramsey1/emba-finance-lab.git
cd emba-finance-lab
open index.html
```

Or visit the [live site](https://sramsey1.github.io/emba-finance-lab/).
