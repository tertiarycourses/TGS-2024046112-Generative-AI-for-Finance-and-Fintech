# Lab 7: Design and UAT a Multi-Agent Close Workflow

**Course:** Generative AI for Finance and Fintech (TGS-2026065050)  
**Mapping:** A3  
**Suggested time:** 150 minutes  
**Objective:** Design a supervisor and specialist-agent workflow with structured handoffs and approval gates.

## Scenario

Northstar wants reconciliation, variance and disclosure agents coordinated by a close supervisor without autonomous journal approval.

## Files

- `northstar-multi-agent-close-starter.xlsx` - learner working file
- `northstar-multi-agent-close-solution.xlsx` - completed formulas, controls and charts for review
- `evidence-checklist.md` - submission and verification checklist
- `handoff-schema.json` - structured multi-agent handoff contract

## Before you begin

- Use only the supplied synthetic data.
- Do not enter live customer, payroll, account, credential or confidential data.
- If the required Microsoft feature is not enabled in your tenant, complete the workbook-based simulation and record the limitation.
- Keep facts, assumptions, AI suggestions and reviewer decisions visibly separate.

## Detailed procedure

### Step 1: Map the current close process and select bounded tasks for each specialist agent.

Record the evidence for Step 1 in the checklist before continuing.

### Step 2: Define the supervisor's orchestration rules and human approval points.

Record the evidence for Step 2 in the checklist before continuing.

### Step 3: Complete the handoff schema for task, source IDs, result, confidence and exceptions.

Record the evidence for Step 3 in the checklist before continuing.

### Step 4: Configure or prototype the flow in Copilot Studio using read-only tools.

Record the evidence for Step 4 in the checklist before continuing.

### Step 5: Execute happy-path, missing-data, tool-failure and approval-bypass tests.

Record the evidence for Step 5 in the checklist before continuing.

### Step 6: Document monitoring, incident response and rollback ownership.

Record the evidence for Step 6 in the checklist before continuing.

## Prompt quality pattern

> Role: You are assisting a finance professional. Task: analyse only the named workbook table. Data boundary: do not use external or unstated facts. Controls: reconcile totals, identify missing evidence, and label assumptions. Output: return a concise table of finding, evidence, confidence, reviewer action and source cell or table.

## Acceptance criteria

- [ ] No agent can approve or post a journal; every handoff is structured; critical tests pass; monitoring and rollback have named owners.
- [ ] All generated claims have been checked against the workbook or approved knowledge.
- [ ] No live credentials, personal data or confidential business data appear in the evidence.
- [ ] A human reviewer and approval status are recorded.

## Deliverable

An agent architecture, handoff contract, RACI, UAT results and rollback plan.

## Reflection

1. What did the AI accelerate?
2. What still required finance judgement?
3. Which control prevented the most serious failure?
4. What evidence is needed before this design can scale?

© 2026 Tertiary Infotech Academy Pte Ltd · UEN 201200696W
