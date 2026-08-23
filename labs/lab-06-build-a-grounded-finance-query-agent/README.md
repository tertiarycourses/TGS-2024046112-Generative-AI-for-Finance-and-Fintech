# Lab 6: Build a Grounded Finance Query Agent

**Course:** Generative AI for Finance and Fintech (TGS-2026065050)  
**Mapping:** A3  
**Suggested time:** 150 minutes  
**Objective:** Build and test a Copilot Studio agent grounded on approved finance policies.

## Scenario

Finance staff need reliable answers about expenses, close deadlines, delegation and reconciliation evidence.

## Files

- `northstar-agent-uat-starter.xlsx` - learner working file
- `northstar-agent-uat-solution.xlsx` - completed formulas, controls and charts for review
- `evidence-checklist.md` - submission and verification checklist
- `knowledge/` - approved synthetic finance policy sources
- `test-cases.json` - UAT cases

## Before you begin

- Use only the supplied synthetic data.
- Do not enter live customer, payroll, account, credential or confidential data.
- If the required Microsoft feature is not enabled in your tenant, complete the workbook-based simulation and record the limitation.
- Keep facts, assumptions, AI suggestions and reviewer decisions visibly separate.

## Detailed procedure

### Step 1: Review the supplied policy knowledge files and identify effective dates and owners.

Record the evidence for Step 1 in the checklist before continuing.

### Step 2: Create the agent in a governed development environment and require authentication.

Record the evidence for Step 2 in the checklist before continuing.

### Step 3: Write instructions that constrain answers to approved knowledge and require citations.

Record the evidence for Step 3 in the checklist before continuing.

### Step 4: Add a deterministic escalation topic for missing or conflicting policy.

Record the evidence for Step 4 in the checklist before continuing.

### Step 5: Run the positive, negative, stale-source and unauthorised-user tests in the UAT workbook.

Record the evidence for Step 5 in the checklist before continuing.

### Step 6: Record defects, retest fixes and capture publish-readiness evidence.

Record the evidence for Step 6 in the checklist before continuing.

## Prompt quality pattern

> Role: You are assisting a finance professional. Task: analyse only the named workbook table. Data boundary: do not use external or unstated facts. Controls: reconcile totals, identify missing evidence, and label assumptions. Output: return a concise table of finding, evidence, confidence, reviewer action and source cell or table.

## Acceptance criteria

- [ ] The agent cites approved sources, refuses unsupported answers, respects access boundaries and passes all critical UAT cases before any publish decision.
- [ ] All generated claims have been checked against the workbook or approved knowledge.
- [ ] No live credentials, personal data or confidential business data appear in the evidence.
- [ ] A human reviewer and approval status are recorded.

## Deliverable

A finance query agent, knowledge pack, test evidence and escalation design.

## Reflection

1. What did the AI accelerate?
2. What still required finance judgement?
3. Which control prevented the most serious failure?
4. What evidence is needed before this design can scale?

© 2026 Tertiary Infotech Academy Pte Ltd · UEN 201200696W
