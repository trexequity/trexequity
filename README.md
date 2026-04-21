<div align="center">

# Trex Equity

*Your agent. Now a real company.*

Tokenized AI-agent equity on Solana — Reg CF / Reg D via DinoSec. 🦖 $TREX

[![App](https://img.shields.io/badge/App-trexequity.xyz-000000?style=for-the-badge)](https://trexequity.xyz)
[![Twitter](https://img.shields.io/badge/Twitter-@trexequity-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/trexequity)
[![GitHub](https://img.shields.io/badge/GitHub-trexequity-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/trexequity)
[![Telegram](https://img.shields.io/badge/Telegram-t.me/trexequity-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/trexequity)
[![Docs](https://img.shields.io/badge/Docs-API_Reference-0052FF?style=for-the-badge)](API.md)
[![Chain](https://img.shields.io/badge/Chain-Solana-14F195?style=for-the-badge&logo=solana&logoColor=black)](https://solana.com)

</div>

## What is Trex Equity?

AI agents now generate real revenue, but there's no legal path to share that revenue with retail supporters. Agent tokens today are unregistered securities with no dividend mechanism or shareholder rights.

Trex Equity is the first platform that incorporates the agent as a real company, files Reg CF or Reg D, and mints Token-2022 compliance-wrapped shares. Shareholders earn pro-rata dividends from agent revenue.

## Core Mechanics

| Step | Action | Description |
|---|---|---|
| 1 | **Agent Onboarding** | Connect agent and provide 90-day revenue proof. |
| 2 | **Legal Wrapper** | Trex Equity files LLC/C-Corp and handles IP assignment. |
| 3 | **Reg CF / Reg D Filing** | Automated Form C generation and EDGAR submission. |
| 4 | **Token-2022 Mint** | Mint shares with transfer hooks for KYC and lockups. |
| 5 | **Raise Live** | Investors buy shares via USDC; funds escrowed. |
| 6 | **Revenue Streaming** | Agent pipes revenue to treasury; 95% distributed to holders. |

## Token Tiers

| Tier | Requirement | Benefits |
|---|---|---|
| **Free** | 0 $TREX | Invest in raises, view Form C filings, 5% dividend take. |
| **Bronze** | 1M $TREX | 4.5% dividend take, email alerts, private group. |
| **Silver** | 5M $TREX | 3.5% dividend take, 24h early access, 50% fee rebate. |
| **Gold** | 10M $TREX | 2.5% dividend take, 48h early access, free trades. |

## How It Works

```text
┌────────────────────────────────────────────────────────────────┐
│  AGENT REVENUE       →  TREASURY VAULT      →  SHAREHOLDERS    │
│  (API, Subs, etc)       (Smart Contract)       (Token-2022)    │
│                                                                │
│  The DinoSec engine enforces KYC, limits, and country blocks   │
│  before any transfer. Dividends flow quarterly.                │
└────────────────────────────────────────────────────────────────┘
```

## Architecture Overview

```text
┌────────────────────────────────────────────────────────────────────┐
│  FRONTEND: Next.js + TailwindCSS + Solana Wallet Adapter           │
│      │                                                             │
│      ▼                                                             │
│  API GATEWAY: Hono (REST + WebSocket)                              │
│      │                                                             │
│      ▼                                                             │
│  DATABASE: Self-hosted PostgreSQL                                  │
│      │                                                             │
│      ▼                                                             │
│  SOLANA MAINNET: Token-2022 + Transfer Hooks + PDAs                │
└────────────────────────────────────────────────────────────────────┘
```

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Next.js, TailwindCSS, Solana Wallet Adapter |
| **Backend API** | Hono, REST, WebSocket |
| **Database** | PostgreSQL |
| **Blockchain** | Solana, Token-2022, Anchor |
| **KYC Provider** | Persona |

## Phased Roadmap

| Phase | Timeline | Key Deliverables |
|---|---|---|
| **Phase 1: MVP** | Weeks 1-8 | Landing page, waitlist, 3 pilot raises, $TREX fair launch. |
| **Phase 2: Growth** | Months 3-6 | Self-serve Form C, 25 raises, KYC production, B2B API v1. |
| **Phase 3: Scale** | Months 6-12 | EDGAR auto-submission, 100+ raises, multi-chain compliance. |
| **Phase 4: Ecosystem** | Year 2 | Open API, insurance pool, international pathways. |

## Reference Links

| Resource | Link |
|---|---|
| **Website** | [trexequity.xyz](https://trexequity.xyz) |
| **Twitter / X** | [@trexequity](https://x.com/trexequity) |
| **GitHub** | [github.com/trexequity](https://github.com/trexequity) |
| **Telegram Channel** | [t.me/trexequity](https://t.me/trexequity) |
| **Telegram Bot** | [@trexequity_bot](https://t.me/trexequity_bot) |
| **API Reference** | [API.md](API.md) |
| **Architecture** | [ARCHITECTURE.md](ARCHITECTURE.md) |
| **Security** | [SECURITY.md](SECURITY.md) |
| **Whitepaper** | [WHITEPAPER.md](WHITEPAPER.md) |

<br/>
<div align="center">
<sub>Trex Equity is a platform for regulated tokenized equity. $TREX is a utility token. Equity tokens sold via Reg CF/Reg D are registered securities. DYOR.</sub>
</div>
