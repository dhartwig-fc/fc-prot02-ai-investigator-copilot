# 🕵️ AI Investigator Copilot

Architecture, Workflow Patterns and an Early Prototype for AI-Enabled Financial Crime Investigations

---

## Status (12 November 2026)

A June 2026 prototype and design, kept as it was written. **It has been superseded by the NEXUS copilot case flow**: inside the NEXUS investigator console, three showcase cases each carry a recommendation, an EDD memo, the report draft their regime requires and the nominated officer's decision, every sentence with numbered sources. That flow is live on the public [NEXUS investigator console](https://dhartwig-fc.github.io/dan-hartwig-portfolio/projects/nexus/runtime-demo/console.html). Its wording is template-based today; AI wording awaits the owner's approval.

What this repository actually holds, measured on 12 November 2026:

- `archive/prototype-v1/ai_investigator_copilot.py`: a static Streamlit page whose alert, risk drivers and actions are written into the code.
- `AI_Investigator_Enrichment_Protoype.ipynb`: an enrichment notebook using pandas only.
- `architecture/reference-architecture/README.md`: the reference architecture.
- Every other folder in the structure below (`prompts/`, `outputs/`, `sample-data/`, `python/workflows/`, `notebooks/prototypes/`) holds only a placeholder file.

Nothing in the repository calls a language model.

---

## Executive Summary

The AI Investigator Copilot was designed as an AI-enabled investigation support capability to transform financial crime analytics and intelligence into investigator-ready decision support.

The repository demonstrates how Financial Crime Analytics, Network Intelligence, Threat Intelligence and Large Language Models can be integrated into a unified investigation workflow.

The capability sits above traditional detection systems and provides explainable intelligence generation, evidence assembly, investigator guidance and conversational investigation support.

This repository serves as the implementation companion to the Financial Crime Analytics Showcase.

---

## Relationship To The Financial Crime Analytics Showcase

The Financial Crime Analytics Showcase defines the business architecture, intelligence architecture and operational workflows underpinning the AI Investigator Copilot capability.

This repository demonstrates how those concepts can be implemented using Python, AI workflows, prompt engineering and prototype investigation services.

```text
Financial Crime Analytics Showcase
                ↓
AI Investigator Copilot Architecture
                ↓
Investigation Workflows
                ↓
Prototype Implementation
                ↓
Future Production Platform
```

Showcase Repository:

https://github.com/dhartwig-fc/fc-01-financial-crime-analytics-showcase

---

## Repository Purpose

The repository is intended to demonstrate:

- AI-assisted investigation workflows
- Alert rationale generation
- Investigator summary generation
- Evidence pack generation
- Intelligence report generation
- Case package generation
- Conversational investigator support
- Agent orchestration concepts
- Prompt engineering patterns
- Explainable intelligence generation

---

## Architecture Overview

```text
Threat Intelligence
        ↓
Financial Crime Analytics
        ↓
Network Intelligence
        ↓
Case Intelligence
        ↓
Orchestration Layer
        ↓
AI Investigator Copilot
        ↓
Investigator Decision Support
```

---

## Repository Structure

The planned structure. Apart from `architecture/` and `archive/`, these folders hold only placeholder files.

```text
fc-prot02-ai-investigator-copilot
│
├── architecture
│   └── reference-architecture
│
├── prompts
│   ├── alert-rationale
│   ├── investigator-summary
│   ├── evidence-pack
│   ├── intelligence-report
│   ├── case-package
│   └── conversational-copilot
│
├── outputs
│   ├── alert-rationale
│   ├── investigator-summary
│   ├── evidence-pack
│   ├── intelligence-report
│   └── case-package
│
├── sample-data
│   ├── alerts
│   ├── entities
│   └── cases
│
├── python
│   └── workflows
│
├── notebooks
│   └── prototypes
│
└── archive
    └── prototype-v1
```

---

## Investigation Workflow

```text
Alert Generated
        ↓
Alert Rationale
        ↓
Investigator Summary
        ↓
Evidence Pack
        ↓
Intelligence Report
        ↓
Case Package
        ↓
Conversational Copilot
```

---

## Prototype Components

| Component | Status (measured 12 November 2026) |
|------------|---------|
| Alert Intelligence Generation | Static example text in the v1 Streamlit page |
| Narrative Generation | Not built here; delivered in the NEXUS copilot case flow (template-worded) |
| Risk Explanation | Static example text in the v1 Streamlit page |
| Evidence Enrichment | Enrichment notebook (pandas) |
| Conversational Investigation Support | Not built |
| Dashboard Prototype | v1 Streamlit page and screenshot in `archive/prototype-v1/` |

---

## Future Enhancements

- Retrieval-Augmented Generation (RAG)
- Multi-Agent Investigation Workflows
- Case Management Integration
- SAR Narrative Automation
- Enterprise LLM Governance
- Dynamic Investigation Planning
- Threat Intelligence Enrichment
- Real-Time Investigator Guidance

---

## Archived Prototype Baseline

The original proof-of-concept implementation has been preserved within:

```text
archive/prototype-v1
```

This archive represents the first working implementation used to validate AI-assisted investigator enrichment concepts.

---

## Strategic Vision

The long-term objective is to create an intelligence-led investigation platform capable of connecting:

- Threat Intelligence
- Financial Crime Analytics
- Network Intelligence
- AI Agents
- Investigation Workflows
- Human Investigators

into a single operational ecosystem.

The AI Investigator Copilot represents the operational intelligence layer that transforms analytical findings into actionable investigator decision support.

---

## Related Repositories

### Financial Crime Analytics Showcase

Business architecture, intelligence architecture and operating model.

https://github.com/dhartwig-fc/fc-01-financial-crime-analytics-showcase

### Transformation AI Lab

AI experimentation, orchestration patterns, MCP, RAG and Agentic AI research.

https://github.com/dhartwig-fc/fc-rm02-transformation-ai-lab

### Emerging Threat Intelligence

Threat monitoring, horizon scanning and intelligence-led capability development.

https://github.com/dhartwig-fc/fc-08-emerging-threat-intelligence

---

## Key Message

This repository records the June 2026 design and first prototype of the AI Investigator Copilot. The capability itself has moved on: it is now built inside NEXUS as the copilot case flow, and this repository is not being developed further.
