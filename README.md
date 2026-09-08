# DIKWP IntentEconomy OS

Created by Yucong Duan (段玉聪).

Open-source, offline-first intent sovereignty and ethical intent exchange toolkit.

Positioning: DIKWP IntentEconomy OS turns the emerging "intention economy" from a covert market for predicting and manipulating users into a user-controlled, evidence-backed, consent-based intent ledger and matching layer.

It helps users, teams, brands, educators, healthcare navigators, public-service teams and AI agents describe intentions as DIKWP semantic objects, publish safe demand briefs, evaluate offers, detect manipulation pressure, record consent and generate governance-ready intent market artifacts.

## Core idea

AI systems increasingly infer what a person or organization will do next. That creates a market opportunity, but also a sovereignty risk: intent can be captured before the user has reflected on it. This system reverses the direction:

```text
platform-inferred intent -> user-owned IntentContract -> consented matching -> audit ledger -> revocable value exchange
```

## What it does

- Builds DIKWP Intent Contracts from user or organization profiles.
- Creates a consent ledger for permitted use, retention, sharing and revocation.
- Evaluates vendor / platform offers against the user's goal, values, constraints, time window and feedback plan.
- Detects manipulation risks such as urgency pressure, scarcity pressure, hidden tracking, indefinite retention, dark-pattern framing and excessive data requests.
- Produces a Demand Brief that can be shared without exposing unnecessary personal data.
- Generates an Intent Sovereignty Scorecard and an Ethical Intent Exchange report.
- Supports a local Streamlit dashboard and CLI.
- Includes NOTICE and CITATION files to preserve DIKWP / Yucong Duan attribution.

## Quick start

```bash
pip install -e .
intenteconomy analyze examples/sample_intent_marketplace.json --out outputs/demo
intenteconomy static-audit src --out outputs/demo/static_boundary_audit_report.json
```

Optional local dashboard:

```bash
pip install -e .[app]
streamlit run src/dikwp_intenteconomy/app.py
```

## Boundary

This project does not provide surveillance, hidden profiling, political microtargeting, dark-pattern generation, credential collection, tracking bypass or covert manipulation tooling. It is a governance and sovereignty layer for explicit, consented, reversible intent exchange.
