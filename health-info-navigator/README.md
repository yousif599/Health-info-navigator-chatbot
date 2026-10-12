# Health Information Navigator

HAI Term Project 2026 | Track 9 | Principle: Safety and Ethics

A web chatbot that gives **general** health information from trusted public sources.
It never diagnoses, never gives medication doses, and shows clear steps to reach a real person when a user may be at risk.

> Status: project skeleton. Sections marked TODO are filled in as the code is written.

## Team

| Member | Role | GitHub |
|---|---|---|
| TODO | TODO | TODO |

## What it does (design summary)

- The user asks a general health question by typing, or taps a topic suggestion.
- A safety filter checks every question before retrieval (red flags, diagnosis requests, dose requests).
- Relevant passages are retrieved from the knowledge source. If evidence is weak, the bot says it is not sure.
- The language model writes the answer from the retrieved passages only, with a citation to the exact passage.

Design documents and workflow diagrams: `docs/milestone1/`.

## Safety principle in the pipeline

TODO: describe the red-flag filter, refusal rules, similarity threshold, and escalation banner as implemented.

## Knowledge source and licence

- Source: MedlinePlus health topic summaries (U.S. National Library of Medicine).
- These summaries are public domain. Attribution: "Courtesy of MedlinePlus from the National Library of Medicine".
- Copyrighted MedlinePlus content (A.D.A.M. articles, drug monographs) is NOT used.
- Details and download date: `data/README.md`.

## Setup

TODO: Python version, `pip install -r requirements.txt`, copy `.env.example` to `.env`, run `python scripts/ingest.py`, start the server.

## Evaluation

TODO: how to run `python scripts/run_eval.py` and where results are saved (`eval/results/`).

## Limitations and accountability

TODO: what the system cannot do, known failure cases, who is accountable when the AI is wrong.

## Data and privacy

Public data only. No personal data is collected. User-test notes use anonymous codes (T1, T2, ...).

## AI use

Every AI prompt we used is recorded in `docs/prompt_log.md` (at least two different AI tools).
