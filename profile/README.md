# Corporate AI Platform (CAIP)

**Sovereign AI for the European Mittelstand — running on your own infrastructure.**

CAIP is a self-hostable, air-gap-capable AI platform built entirely on open source.
It gives organizations the productivity of modern LLMs while keeping **models, data,
and control fully in-house** — no third-party inference, no telemetry, no vendor lock-in.

## What it is

A complete, sovereign stack on Kubernetes / OpenShift:

- 🧠 **Bring Your Own Model (BYOM)** — open-weight models served locally (vLLM / Ollama),
  swappable via one config value behind a stable API.
- 🔌 **OpenAI- & Anthropic-compatible gateway** — point existing tools, IDEs, and agents
  at your private endpoint; self-service API keys, teams, and usage metering.
- 💬 **Chat UI + RAG** — a ready chat experience with retrieval over your own documents.
- 🔒 **Sovereign by design** — weights and data stay on-site, egress lockdown,
  internal registry, NetworkPolicies, SSO (Keycloak/OIDC). Air-gap deployment supported.
- 📦 **Two sizes** — lightweight single-node (S/M) up to HA multi-node (L/XL), packaged
  as a Helm chart and an optional operator.

## Principles

- **Control over hype** — a sovereignty and data-protection promise, not a benchmark race.
- **Open source all the way down** — no proprietary lock-in in the platform itself.
- **Honest engineering** — documented decisions (ADRs), reproducible manifests, auditable.

## Repositories

- [`caip`](https://github.com/CorporateAIPlatform/caip) — platform: docs, Helm chart,
  operator, infrastructure (OpenShift/OKD, MicroShift, vanilla Kubernetes).

---

> Built for organizations that need modern AI **without** sending their data anywhere.
