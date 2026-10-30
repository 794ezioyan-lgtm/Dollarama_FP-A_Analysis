# Dollarama Inc. | Financial Planning & Analysis & Valuation

**Integrated financial modelling • Driver-based forecasting • Budget vs. reforecast • Scenario analysis • DCF valuation • Power BI**

> **Independent educational portfolio project.** Not affiliated with or endorsed by Dollarama Inc. Financial projections and valuation assumptions are illustrative, not company guidance or investment advice. All figures in CAD millions unless otherwise indicated.

![Executive analytics dashboard](Screenshots/01_Executive_Dashboard.png)

## Executive overview

This project develops an integrated FP&A and valuation case study for Dollarama, using historical financial information for FY2023–FY2026 and modelled projections for FY2027–FY2030. The Excel workbook connects store growth, comparable-store sales, regional revenue, operating costs, capital expenditure, working capital and financial statements. A two-page Power BI report presents operating trends, retail footprint, product mix, working capital and valuation sensitivities.

**Project scope:** 15 Excel worksheets; two Power BI report pages; Canada and Australia revenue drivers; integrated income statement, balance sheet and cash flow; budget-to-reforecast analysis; price-volume-mix (PVM) bridge; three operating scenarios; discounted cash flow (DCF) valuation.

## Modelled highlights

| Metric | Model output | Context |
|---|---:|---|
| FY2026 revenue | CAD 7,255.8M | Historical baseline used in workbook |
| FY2030 revenue | CAD 9,672.3M | Operating-model forecast |
| FY2030 EBITDA | CAD 2,901.7M | Operating-model forecast |
| FY2027 budget revenue | CAD 8,030.0M | Budget case |
| FY2027 reforecast revenue | CAD 7,957.4M | Reforecast case; CAD 72.6M below budget |
| FY2027 reforecast EBITDA | CAD 2,252.0M | CAD 84.8M below budget |
| DCF enterprise value | CAD 25,433.7M | Modelled at 9.0% WACC and 2.5% terminal growth |

**Interpretation:** The reforecast projects lower revenue and profitability than budget, with pressure from sales volume, cost of goods sold and SG&A. DCF results are highly sensitive to discount rate and terminal growth. These are outputs of the author's modelling assumptions, not independently verified market estimates.

## 1. Operating drivers and revenue forecast

![Operating drivers](Screenshots/03_Operating_Drivers.png)

The model projects Canada's store network from 1,691 in FY2026 to 1,966 in FY2030 and incorporates comparable-store sales, new-store contributions and non-comparable growth. Australia is modelled separately and consolidated into group revenue.

![Revenue build](Screenshots/04_Revenue_Build.png)

## 2. Three-statement financial model

The financial model links operating revenue and expenses to the income statement, forecasts balance-sheet balances and reconciles cash movement through the cash flow statement. PP&E and working-capital schedules provide supporting drivers.

![Income statement](Screenshots/05_Income_Statement.png)

![Balance sheet](Screenshots/06_Balance_Sheet.png)

![Cash flow statement](Screenshots/07_Cash_Flow.png)

## 3. Budget vs. reforecast and PVM analysis

The FY2027 reforecast reduces revenue from CAD 8,030.0M to CAD 7,957.4M (-0.90%) and EBITDA from CAD 2,336.7M to CAD 2,252.0M (-3.63%). The model attributes the sales movement to illustrative price, volume and mix components, and separately bridges EBITDA through revenue and cost-rate effects.

![Budget and reforecast](Screenshots/08_Budget_Reforecast.png)

![PVM and EBITDA bridges](Screenshots/09_Price_Volume_Mix.png)

**Management implication:** Monitor unit-volume softness and gross-margin pressure; assess cost efficiency rather than relying on pricing alone. The product-category PVM decomposition is an illustrative modelling exercise, not disclosed company-level unit economics.

## 4. Scenario planning and sensitivity

Best, base and worst cases vary revenue growth and COGS/SG&A rates. The workbook includes FY2027–FY2030 scenario outputs plus two-way sensitivity matrices for EBITDA and net income.

![Scenario comparison](Screenshots/10_Scenario_Analysis.png)

![Sensitivity matrices](Screenshots/11_Sensitivity_Tables.png)

## 5. DCF valuation

The DCF estimates unlevered free cash flow from operating profit after tax, depreciation and amortization, capital expenditure and changes in working capital. Cash flows and terminal value are discounted at a modelled 9.0% WACC with 2.5% perpetual growth. The workbook also provides a WACC/terminal-growth valuation sensitivity matrix.

![DCF model](Screenshots/12_DCF_Valuation.png)

![DCF sensitivity](Screenshots/13_DCF_Sensitivity.png)

**Valuation caution:** The terminal value represents approximately 79.6% of modelled enterprise value, making the estimate especially dependent on long-run assumptions. See [model review notes](Documentation/Model_Review_Notes.md) before relying on the result.

## 6. Power BI interactive report

The Power BI report contains an executive analytics page and a planning/valuation page with revenue, EBITDA, EBIT, cash flows, Canadian store distribution, product category mix, working-capital efficiency, KPI cards and valuation sensitivity. Fiscal year, location and category selectors are included in the report design.

![Planning and valuation report](Screenshots/02_Planning_Valuation_Dashboard.png)

The `.pbix` file can be opened in Power BI Desktop; GitHub does not render an interactive `.pbix` report directly.

## Repository files

| File | Purpose |
|---|---|
| [Excel FP&A model](Financial-Model/Dollarama_FP%26A_Model.xlsx) | Source financial model, forecasts, scenarios and DCF |
| [Power BI report](Power-BI/Dollarama_PowerBI_Dashboard.pbix) | Two-page interactive dashboard source |
| [Screenshots](Screenshots/) | Selected visual evidence of work |
| [Methodology and assumptions](Documentation/Methodology_and_Assumptions.md) | Model architecture and approach |
| [Model review notes](Documentation/Model_Review_Notes.md) | Transparency on limitations and items to resolve |

## Tools and skills demonstrated

**Excel:** integrated three-statement modelling, driver-based forecasting, working-capital analysis, PP&E roll-forward, budget variance, PVM bridges, scenario/sensitivity tables, DCF valuation and reconciliation checks.  
**Power BI:** data modelling, KPI reporting, interactive slicers, financial trend charts, map visualizations and valuation sensitivity reporting.

## Data provenance and limitations

Historical data was assembled for this case study using company reporting materials; see the workbook for the exact figures used. Forecasts, scenario inputs, PVM units/prices and valuation assumptions are authored estimates. This repository is intended to demonstrate analytical workflow and is not an audited representation of Dollarama's financial position. See [model review notes](Documentation/Model_Review_Notes.md) for known modelling and presentation concerns.
