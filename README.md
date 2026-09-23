# homelab-soc

> 🚧 Started 2026-09-23 — building this alongside my cybersecurity learning roadmap

`homelab-soc` documents the architecture, telemetry ingestion, and detection engineering use-cases for my home Security Operations Center (SOC) lab environment.

## Purpose

To gain practical, end-to-end experience configuring log forwarders, building SIEM dashboards, and developing high-fidelity detection rules against simulated adversarial activity.

## Architecture & Ingestion

- **Log Ingestion Status**: In development / setup phase.
- **Components**:
  - `setup/`: Infrastructure configs (ELK / Docker Compose definitions) and endpoint log source documentation.
  - `detections/`: Custom detection rule definitions, logic explanations, and triage criteria.
  - `incident-walkthrough.md`: End-to-end walkthrough of simulated attacks and analyst investigation steps.
  - `screenshots/`: Visual evidence of alerts, dashboards, and event correlations.
