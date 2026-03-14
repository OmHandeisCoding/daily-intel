# 📡 Daily Intel — Automated Intelligence Reports

> **AI | Cybersecurity (GRC/Compliance) | Geopolitics**
> Automated daily intelligence collection, LLM-powered analysis, and publication for IT Specialists.

---

## 🗂️ Repository Structure

```
daily-intel/
├── AI/             # 🤖 AI developments, research papers, model releases
│   └── YYYY/Month/YYYY-MM-DD/
│       ├── report.md     ← Rich Markdown report
│       └── report.html   ← Interactive dark-mode HTML with charts
├── Cybersecurity/  # 🛡️ CVEs, CISA alerts, threat intelligence
│   └── YYYY/Month/YYYY-MM-DD/
│       ├── report.md
│       └── report.html
└── Geopolitical/   # 🌍 Markets, conflicts, safety, preparedness
    └── YYYY/Month/YYYY-MM-DD/
        ├── report.md
        └── report.html
```

## 📊 What's Inside Each Report

### 🤖 AI Reports
- Latest ArXiv papers with **WHAT / WHY / HOW / WHAT YOU CAN DO** breakdowns
- Model releases from Anthropic, Google DeepMind, OpenAI, Meta AI, HuggingFace
- Breakthrough signal detection and trend correlation
- Automation & service-building opportunities for IT professionals

### 🛡️ Cybersecurity Reports
- **NIST NVD CVEs** (last 48h, CVSS ≥ 5.0) with severity, affected systems, patch status
- **CISA Known Exploited Vulnerabilities** (KEV) — highest priority
- **GRC compliance impact** (ISO 27001, SOC 2, PCI-DSS, NIST CSF, HIPAA)
- Threat campaign correlation across BleepingComputer, Krebs, Dark Reading, SecurityWeek
- Priority-ordered patch/action checklist

### 🌍 Geopolitical Reports
- Situation analysis with **market impact** (equities, commodities, crypto, forex)
- **What to do / What to avoid** — investment and safety guidance
- Travel advisories and safety concerns by region
- **Life preparedness**: supply chain, inflation, digital resilience
- 30/90/180-day forecasts

## 🔧 How It Works

1. **Scrapers** collect from 35+ free sources (RSS, public APIs, Reddit)
2. **Analyzers** use local Ollama LLM (best available model) → Gemini API fallback
3. **Reports** generated as both Markdown (`.md`) and interactive HTML (`.html`)
4. **Auto-pushed** to this repo daily via Windows Task Scheduler

## 📡 Sources

| Domain | Sources |
|---|---|
| **AI** | ArXiv, Semantic Scholar, Papers With Code, HuggingFace, Google AI, Anthropic, OpenAI, Meta AI, DeepMind, Hacker News, MIT Tech Review, VentureBeat |
| **Cybersecurity** | NIST NVD, CISA KEV, CISA Alerts, BleepingComputer, Krebs on Security, The Hacker News, Dark Reading, SecurityWeek, Schneier on Security, OWASP, SANS ISC, Exploit-DB |
| **Geopolitical** | Reuters, AP, BBC World, Al Jazeera, CNBC, Financial Times, The Economist, Foreign Policy, CFR, Reddit r/geopolitics, r/worldnews, r/economy, r/investing |

---

*🤖 Generated and maintained by [Daily Intel System](https://github.com/OmHandeisCoding/daily-intel) — Last updated: 2026-03-14*
