# Consolidated Reporting & Group Budgeting Model
**Status:** Completed (2026)  
**Tech Stack:** Advanced Excel (formulas, PivotTables, named ranges), financial analysis, IFRS-like consolidation, factor analysis, top-down planning.  
**Type:** Pet project / capstone case demonstrating FP&A skills.

## Business Problem
In multi-entity groups, unadjusted intercompany transactions (IC) distort financial results: revenue and expenses are double-counted, and net profit variances cannot be reliably decomposed into drivers. This undermines management decision-making and budget defense.

## Solution
An end-to-end Excel-based model that:
- Produces clean consolidated financials free from IC distortions.
- Quantifies each subsidiary’s contribution to net profit variance.
- Enables dynamic 5-year budget recalculation based on updated assumptions.
- Delivers ready-to-present management insights and a slide deck.
## Key Deliverables

- **Consolidation for 4 entities with mixed ownership:** full consolidation for subsidiaries B and C; equity method for subsidiary D.
- **Intercompany eliminations:** transparent logic on a dedicated sheet to remove double counting.
- **Non-controlling interest (NCI):** correctly calculated and reflected in P&L and balance sheet.
- **Plan-vs-actual and factor analysis for 2025:** variance decomposition by margin, volume, structure, and intercompany effects.
- **Top-down 5-year budget (2026–2030):** for the parent and consolidated group, including planned intercompany flows and strategic targets.
- **Management presentation:** 5–7 slides with key metrics, assumptions, and actionable takeaways.

## Measurable Value

- **Clean consolidated reporting:** eliminated IC distortions provide management with a true view of group performance.
- **Quantified driver attribution:** enables targeted risk management by identifying which entity drives negative/positive variance.
- **Dynamic budgeting tool:** changing assumptions (growth rates, inflation, FX rates) automatically updates budgets and analyses.
- **Time efficiency:** pre-built presentation with metrics and next steps accelerates reporting cycles and executive reviews.

## Repository Structure

- `data/` — source inputs (strategic targets, actuals, plan data).
- `calculations/` — `Graduation project.xlsx`:
  - Sheets: “2025 Actual Consolidated”, “2025 Plan Consolidated”, “IC Eliminations”.
  - “2025 Financial Analysis” (trends, margins, target comparison).
  - “2025 Factor Analysis” (drivers of net profit variance).
  - “Parent Top-Down Budget” and “Group Consolidated Budget 2026–2030”.
  - “Assumptions” sheet with key planning inputs.
- `presentation/` — `Diplom_Presentation.pdf` with management slides.
- `docs/` — supplementary materials (if any).
- `README.md` — this file.

## How to Use the Model (Reproducibility)

The model is designed as a reusable tool, not a static report:

1. Open `Graduation project.xlsx` in `calculations/`.
2. Update inputs on the “Assumptions” sheet (growth rates, inflation, FX rates, etc.) — the model auto-recalculates budgets and consolidated outputs.
3. Review “IC Eliminations” sheet for transparent logic — easy to audit or adapt to other groups.
4. Check “2025 Factor Analysis” for variance drivers and formula logic.
5. Use the slide deck in `presentation/` (`Diplom_Presentation.pdf`) for executive presentations.

## Why This Is a Strong FP&A Pet Project

- **Real-world complexity:** consolidation with mixed ownership, IC eliminations, and NCI are common FP&A/controlling tasks.
- **Transparent logic:** all formulas and rules are on dedicated sheets with cell comments — easy to audit and extend.
- **Dynamic design:** the model recalculates with new inputs, demonstrating a tool-building mindset.
- **Management-ready outputs:** the presentation shows the ability to translate numbers into actionable insights.
- **Skill demonstration:** advanced Excel, financial modeling, consolidation logic, variance analysis, and strategic planning.

## Key Takeaways

- **Profit growth trajectory:** the model shows accelerating net profit growth driven by revenue expansion and operational efficiency improvements.
- **Risk focus:** one subsidiary remains a high-risk area requiring close monitoring of cost and revenue variances.
- **Next steps:** budget defense, implementation of quarterly plan-vs-actual reviews, and enhanced monitoring for the risk entity.
