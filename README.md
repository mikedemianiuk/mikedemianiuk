# Mike Demianiuk

Payments PM. Building tools to make fintech genuinely learnable — not just memorizable.

---

## What I Build

**[Finality](https://finality-ten.vercel.app) — Payment Rails Learning Lab**
Interactive simulation of 11 payment rails (ACH, Wire, RTP, FedNow, cards, USDC, BTC, ETH, SOL). You route payments, watch lifecycle events unfold, reconcile your internal ledger against the network, and get coached by an AI interviewer on 25+ company-specific PM case studies. Built because reading spec sheets doesn't teach you what an ACH return actually costs you.

**Briefings — Personalized Fintech Intelligence**
Automated pipeline that turns 50+ RSS feeds into a personalized weekly digest. Cloudflare Workers → Gemini Flash for daily summaries → Gemini Pro for weekly synthesis → Claude for monthly trend analysis. Tracks OCC charter races, stablecoin infrastructure, BaaS risk, and ISO 20022 migration deadlines so I don't have to.

**Hermes — AI PM Interview Coach**
Claude-powered interviewer that runs Capital One "Power Day" cases with cross-session memory. Grades on four pillars: Correctness (30%), Ops (25%), Economics (30%), Risk (15%). Remembers what you got wrong last session and coaches that specifically.

---

## Focus Areas

- Payment rail mechanics: settlement finality, reconciliation, chargeback/return flows
- Card infrastructure: interchange economics, BIN sponsorship, card-as-a-service
- Fintech regulation: OCC charter strategy, BaaS model risk, ISO 20022 migration
- Agentic commerce: machine-initiated payments, Stripe metered billing, ACP protocol

---

## Stack

TypeScript everywhere. Next.js, NestJS, Cloudflare Workers. Claude (Anthropic) for AI coaching. Gemini for digest generation. Turborepo monorepo. PostgreSQL + D1.

---

[LinkedIn](https://linkedin.com/in/mikedemianiuk) · [finality-ten.vercel.app](https://finality-ten.vercel.app)
