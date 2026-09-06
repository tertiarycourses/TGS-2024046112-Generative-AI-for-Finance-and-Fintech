# Generative AI for Finance and Fintech

WSQ courseware for **TGS-2026065050**, delivered by Tertiary Infotech Academy Pte Ltd.

A four-day, hands-on programme built entirely around Microsoft Copilot: Copilot in
Word, PowerPoint and Excel, Microsoft 365 Copilot agents, SharePoint as a governed
finance source, and Copilot Studio workflows, agents and multi-agent orchestration —
with PDPA, security and human oversight running through all of it.

## The package

- a 287-slide trainer deck (PPTX + PDF), generated from a single course content module;
- an aligned Learner Guide and Lesson Plan (DOCX + PDF);
- 12 self-contained lab folders with starter and solution workbooks, step-by-step
  procedures and evidence checklists;
- a shared synthetic finance dataset that every artefact reconciles to;
- confidential WA and Case Study papers, kept outside the public release.

## The six topics

| # | Topic | Focus |
|---|---|---|
| 1 | Generative AI, Agentic AI and AI Agents in Finance | How the three differ, finance and fintech use cases for each, Copilot in Word and PowerPoint, and a no-code Microsoft 365 agent |
| 2 | Excel Copilot for Financial Analysis and Dashboards | Data readiness, generated formulas and their audit, variance analysis, visualisation and forecasting |
| 3 | SharePoint for Finance and Grounded Finance Agents | Finance sites, typed lists, approved libraries, permissions, and agents grounded on approved content |
| 4 | Copilot Studio Workflows and Agents for Finance Automation | A dedicated environment, agent flows, skills and tools, and a blocking human approval gate |
| 5 | Multi-Agent Orchestration of Financial Work Processes | Supervisor and specialist agents, connected agents, handoff contracts and where orchestration fails |
| 6 | AI Security, PDPA and Human Oversight in Finance | PDPA obligations, data classification, Copilot Studio security settings and real human oversight |

## Live tenant

The labs run against real infrastructure provisioned on the Tertiary Infotech tenant,
not a simulation. See [labs/TENANT-RESOURCES.md](labs/TENANT-RESOURCES.md) for the
site, the environment and the agent links. All finance data is synthetic.

- **SharePoint:** a Northstar Finance team site with two document libraries and seven
  typed lists holding 920 rows.
- **Power Platform:** a dedicated sandbox environment with Dataverse, on the
  pay-as-you-go billing plan.
- **Agents:** five published Copilot Studio agents, including a Month End Close
  Supervisor that routes to four connected specialists, plus a Microsoft 365 Copilot
  agent built with the SharePoint agent builder.

Every artefact — the SharePoint lists, the Excel labs and the agent-facing reports —
derives from one generator and reconciles to a net profit of **SGD 4,767,259.38** for
H1 FY2026.

## Tool focus

- Microsoft Copilot in Word, PowerPoint and Excel
- Microsoft 365 Copilot agents
- SharePoint as a governed knowledge source
- Microsoft Copilot Studio: agent flows, tools, connected agents and approval gates
- PDPA, data classification, DLP and human oversight for finance AI

## Deck preview

![Copilot Studio build surface with finance-specific configuration callouts](screenshot.png)

## Building

```bash
export PYTHONPATH="$PWD/build"
python3 build/gen_finance_data.py      # the shared synthetic dataset
python3 build/gen_agent_reports.py     # agent-readable finance reports
python3 build/build_assets.py          # 12 lab folders
python3 build/build_slides.py          # trainer deck
python3 build/build_documents.py       # Learner Guide and Lesson Plan
python3 build/build_assessments.py     # WA and Case Study, papers and keys
python3 build/qa_courseware.py         # gate check
```

`build/course_data.py` is the single source of truth. The deck, the documents, the
labs and the assessments are all generated from it, so a change there propagates
everywhere.

---

© 2026 Tertiary Infotech Academy Pte Ltd · UEN 201200696W
