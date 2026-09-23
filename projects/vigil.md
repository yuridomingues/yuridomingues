# VIGIL

**OSINT investigation workbench focused on provenance, evidence and explainable correlation.**

VIGIL is a personal engineering project for organizing public-source investigations without collapsing raw observations, analyst assessments and attribution into the same layer.

## Problem

OSINT workflows often become a collection of unrelated tools, exports and notes. The harder problem is preserving provenance, reviewing relationships and keeping conclusions traceable to evidence.

## What I built

- investigation cases with graph, evidence, findings and timeline;
- provenance ledger with source, collector, timestamp and hash;
- entity-link analysis with confidence and rationale;
- adapters for public-source tooling and structured imports;
- review states for relationships instead of automatic identity verdicts;
- reporting and curated evidence export;
- explicit separation between indicators and attribution.

## Engineering focus

**Python · FastAPI · React · graph analysis · OSINT · provenance · defensive research**

The project is intentionally conservative about correlation. Similar usernames or biographies are treated as weak indicators, not identity proof.

## Demo

Test environment: https://vigil-osint.vercel.app

## Repository

Public source: https://github.com/yuridomingues/vigil
