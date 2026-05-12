# Redmai

**AI-powered API security testing. Upload your OpenAPI spec — get a vulnerability report in minutes.**

---

## What we do

Redmai scans your API for OWASP API Top 10 vulnerabilities automatically.
No security expertise required. No sales call. No waiting weeks for a pentest.

**How it works:**
1. Upload your OpenAPI / Swagger spec
2. AI runs attack scenarios — BOLA, auth bypass, injection, SSRF, and more
3. Get a report with every vulnerability, a working PoC, and exact fix steps

---

## Why Redmai

**Air-gapped inference.** We run AI on our own DGX hardware.
Your API spec never reaches OpenAI, Anthropic, or any external cloud.

**Proven on real benchmarks.**
Found a critical SSTI vulnerability on OWASP's crAPI benchmark —
autonomously, in 44 minutes, with zero human involvement.

**Self-serve from $79/mo.**
No enterprise contract. No 6-month sales cycle. Start in minutes.

---

## Status

🔴 Currently in private beta.

---

## Tech

- AI inference: NVIDIA DGX (air-gapped, on-prem)
- Backend: Python / FastAPI
- Scanner: custom OWASP API Top 10 engine
- Infra: multi-tenant, isolated per scan

---

*Building secure APIs shouldn't require a security team.*
