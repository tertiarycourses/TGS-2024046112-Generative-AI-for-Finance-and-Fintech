# Lab 2: Prepare Finance Data for Copilot in Excel

**Course:** Generative AI for Finance and Fintech (TGS-2026065050)  
**Mapping:** K1 · A2  
**Suggested time:** 90 minutes  
**Objective:** Convert messy finance transactions into an analysis-ready Excel Table with control totals.

## Scenario

The FP&A team receives a mixed-quality export from the billing system and must prepare it for Copilot analysis.

## Files

- `northstar-finance-data-readiness-starter.xlsx` - learner working file
- `northstar-finance-data-readiness-solution.xlsx` - completed formulas, controls and charts for review
- `evidence-checklist.md` - submission and verification checklist

## Before you begin

- Use only the supplied synthetic data.
- Do not enter live customer, payroll, account, credential or confidential data.
- If the required Microsoft feature is not enabled in your tenant, complete the workbook-based simulation and record the limitation.
- Keep facts, assumptions, AI suggestions and reviewer decisions visibly separate.

## Detailed procedure

### Step 1: Open the starter workbook and review the Data Dictionary and expected control total.

Record the evidence for Step 1 in the checklist before continuing.

### Step 2: Convert the source range to an Excel Table and standardise headers.

Record the evidence for Step 2 in the checklist before continuing.

### Step 3: Correct date, currency, account and department fields without changing transaction IDs.

Record the evidence for Step 3 in the checklist before continuing.

### Step 4: Use validation formulas to detect missing keys, duplicates and invalid signs.

Record the evidence for Step 4 in the checklist before continuing.

### Step 5: Reconcile clean revenue and expense totals to the control sheet.

Record the evidence for Step 5 in the checklist before continuing.

### Step 6: Ask Copilot in chat mode to identify trends and outliers, then verify each claim against the table.

Record the evidence for Step 6 in the checklist before continuing.

## Prompt quality pattern

> Role: You are assisting a finance professional. Task: analyse only the named workbook table. Data boundary: do not use external or unstated facts. Controls: reconcile totals, identify missing evidence, and label assumptions. Output: return a concise table of finding, evidence, confidence, reviewer action and source cell or table.

## Acceptance criteria

- [ ] Duplicate count is zero, required-field errors are zero, and clean totals reconcile to the supplied control figures.
- [ ] All generated claims have been checked against the workbook or approved knowledge.
- [ ] No live credentials, personal data or confidential business data appear in the evidence.
- [ ] A human reviewer and approval status are recorded.

## Deliverable

A clean transactions table, quality log and reconciled control totals.

## Reflection

1. What did the AI accelerate?
2. What still required finance judgement?
3. Which control prevented the most serious failure?
4. What evidence is needed before this design can scale?

© 2026 Tertiary Infotech Academy Pte Ltd · UEN 201200696W
