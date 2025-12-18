# DeltaDeFi: Hydra Trading Infrastructure Budget (₳1,500,000)

# Abstract

This Budget Info Action asks DReps and the Cardano community to signal support for a **₳1,500,000, 6-month budget** to harden and scale **DeltaDeFi**, a Hydra-based, low-latency order-book exchange aiming to become core **trading infrastructure for Cardano**, focused on ADA and Cardano native tokens (CNTs).

The requested budget is intended to:

- Bring the current **Hydra spot DEX** from beta to a production-ready venue for both API traders and everyday users;
- Scale the **Hydra and data infrastructure** so Cardano has at least one CEX-grade venue for ADA and key CNT pairs; and
- Deliver a **Vision 2030 KPI Measurement Programme** (baseline report + live dashboard + progress report) that tracks DeFi infrastructure contribution to ecosystem goals.

Within the ₳1,500,000 total:

- 80% is dedicated to engineering, operations and security for the Hydra trading infrastructure; and
- 20% is dedicated to the **Vision 2030 KPI Measurement Programme**:

  - an initial **"State of Cardano DeFi" baseline report**,
  - a public **Vision 2030 KPI dashboard**, and
  - a final **6-month progress report**,

---

# Motivation

## Why this matters for Cardano, ADA and CNT holders

Cardano currently lacks a **low-latency order-book venue** that can:

- Support **API-driven trading, arbitrage and market-making** at scale;
- Offer **tight spreads and low slippage** in key ADA–stable and ADA–CNT markets; and
- Provide a clear, measurable picture of how competitive Cardano is as an L1 for trading compared with other ecosystems and CEXs.

Today, most Cardano trading happens on AMM-style DEXs. They are great for simple swaps, but they are not optimised for:

- **Low-fee, low-slippage execution at size** in core ADA and CNT pairs;
- **Instant, predictable fills** for API and bot-driven strategies; or
- **Professional market-makers and arbitrageurs** who expect CEX-like order-book behaviour.

DeltaDeFi is designed to fill this gap: a **Hydra-based, low-latency order-book** with **tight spreads, fast matching** and **first-class API support**, so that ADA and CNT liquidity can be deployed efficiently and Cardano can compete more directly with order-book venues on other chains and on CEXs.

A performant, observable exchange is therefore not just another dApp, but part of Cardano’s **core infrastructure**. It supports the Constitution’s emphasis on **future development of the ecosystem** by making Cardano a more attractive base layer for capital, traders, and applications built around ADA and CNTs.

## Why Hydra and why DeltaDeFi

Hydra offers the latency and UX profile needed for modern trading but is still under-represented in production-grade, user-facing protocols. DeltaDeFi is:

- A **Hydra-based, low-latency order-book DEX** already live in beta on mainnet;
- Built by a team with an existing track record in:
  - high-frequency trading tooling,
  - Cardano SDKs and infrastructure, and
  - Project Catalyst delivery; and
- Focused on **spot trading and API-driven participants**, where reliable execution and transparent metrics matter most.

Earlier Project Catalyst funding helped bootstrap the current codebase and beta deployment with relatively modest budgets. This proposal is intended to take that work from “working beta” to **robust, measurable infrastructure** for the whole ecosystem.

## Direct relevance to ADA and CNT holders

From the point of view of ADA and CNT holders, the key questions are:

- **How expensive is it to move size on Cardano?**
  Slippage plus fees for 1k / 10k / 100k ADA trades in core pairs such as ADA/USDM.

- **How well aligned are ADA and major CNT prices across DEXs and with CEX prices?**  
  Price gaps between on-chain venues and a simple CEX reference.

- **How fragmented and inconsistent are CNT markets across Cardano DEXs?**  
  Differences in price, depth and execution quality for the same tokens on different venues.

Today, answering these questions requires stitching together multiple tools and APIs. As part of this budget, DeltaDeFi will:

- Deliver **tighter, deeper markets** on at least one Hydra-based venue; and
- Publish a **Vision 2030 KPI dashboard** so ADA and CNT holders can track, in numbers, whether Cardano is progressing toward its DeFi vertical goals.

---

# Rationale

## 6-Month Roadmap and Scope

Over the 6-month budget period, the work is grouped into three tightly scoped tracks.

### 1. Hardening the Hydra spot DEX

**Goal:** move the existing beta mainnet exchange to a **production-grade trading venue**.

Key activities:

- Improve **matching engine robustness**, latency and failure-mode handling on Hydra;
- Strengthen **risk controls, monitoring and incident response** for production use;
- Complete **security reviews and targeted audits** of critical components (on-chain scripts, Hydra integration, off-chain engine);
- Improve **API stability, documentation and sandbox environments** so professional traders and bots can integrate with confidence; and
- Deliver and maintain a **public status page** for uptime and incident reporting.

**Outcome:** Cardano has a live, hardened Hydra spot DEX that can realistically serve as a primary venue for order-book trading in ADA and key ADA-centric CNT pairs.

### 2. Scaling infrastructure and integrations

**Goal:** ensure DeltaDeFi is **usable and visible as infrastructure**, not only as a stand-alone app.

Key activities:

- Scale **Hydra and indexing infrastructure** to handle growing order and volume loads;
- Improve **wallet and protocol integrations**, making it easy for users and other Cardano dApps to use DeltaDeFi as a liquidity source;
- Extend markets to include **other core USD-centric pairs**, and selected CNT pairs where depth and tight spreads matter; and
- Design the platform so that **AI-driven liquidity agents and automated trading systems** can integrate via APIs in future roadmap phases, without adding complexity to this budget period.

**Outcome:** DeltaDeFi functions as a **reliable, API-friendly trading venue** that Cardano projects, CNT issuers and larger participants can build on.

### 3. Vision 2030 KPI Measurement Programme

**Goal:** make DeltaDeFi's contribution to **Vision 2030 goals** measurable and tie the benefit of this budget to ecosystem-wide KPIs.

This track is detailed below. **20% of the total budget** is explicitly reserved for its delivery and is payable at the end of the 6-month period.

---

## Vision 2030 KPI Measurement Programme

To make the impact of this budget visible against **Cardano Vision 2030 goals**, DeltaDeFi will deliver:

1. An **initial baseline report** measuring current DeFi KPIs;
2. A **public Vision 2030 KPI dashboard**; and
3. A **final 6-month report** assessing progress toward Vision 2030 targets.

### 1. Initial "State of Cardano DeFi" report (baseline)

Early in the budget period, DeltaDeFi will publish a baseline measuring Cardano's current position against **Vision 2030 DeFi vertical goals** ("institutional-grade liquidity and usable Cardano-native DeFi").

**Scope:** ADA/USDM pair across **top 3 Cardano DEXs**, benchmarked against **top 3 ADA CEXs**.

| Vision 2030 KPI Area | Baseline Metrics                                           |
| -------------------- | ---------------------------------------------------------- |
| **DeFi Vertical**    | Slippage, spread, depth for 1k/10k/100k ADA; CEX price gap |
| **Adoption (TVL)**   | Current DeFi TVL across measured venues                    |
| **Adoption (MAU)**   | Active trading addresses                                   |

**CNT Market Quality:** Price discrepancies for major CNTs across DEXs vs CEX benchmarks.

**Suggested Targets:** The report will propose **governance-grade targets** aligned with Vision 2030:

- Target slippage/cost ranges for "institutional-grade" execution;
- Desired spread and depth levels; and
- CNT price alignment expectations.

Where data access is limited, limitations will be documented.

### 2. Public Vision 2030 KPI Dashboard

DeltaDeFi will build and maintain a **public dashboard** structured around the **Cardano Vision 2030 KPIs**, making DeFi infrastructure contribution to ecosystem goals measurable and transparent.

#### Adoption KPIs (Vision 2030: TVL $3B, MAU 1M, Transactions ≥27M/month)

| Metric                   | Scope                 | Description                                     |
| ------------------------ | --------------------- | ----------------------------------------------- |
| **Total Value Locked**   | DeltaDeFi             | Locked value in DeltaDeFi contracts             |
| **Monthly Active Users** | DeltaDeFi + Cross-DEX | Unique trading addresses with historical trends |
| **Trading Volume**       | DeltaDeFi + Cross-DEX | Daily/monthly matched order volume              |
| **Transaction Count**    | DeltaDeFi             | Contribution to Cardano transaction throughput  |

#### DeFi Vertical KPIs (Vision 2030: "Institutional-grade liquidity and usable DeFi")

| Metric                         | Scope                   | Description                            |
| ------------------------------ | ----------------------- | -------------------------------------- |
| **Slippage (1k/10k/100k ADA)** | Top 3 DEXs + DeltaDeFi  | Execution cost at standard trade sizes |
| **Bid-Ask Spread**             | Top 3 DEXs + DeltaDeFi  | Average spread for ADA/USDM            |
| **Depth within ±1%**           | Top 3 DEXs + DeltaDeFi  | Available liquidity near mid-price     |
| **CEX Price Gap**              | Cross-DEX vs Top 3 CEXs | Deviation from CEX reference mid       |

#### Scalability KPIs (Vision 2030: L2 Integration, 3x Throughput)

| Metric                         | Scope     | Description                                      |
| ------------------------------ | --------- | ------------------------------------------------ |
| **L1 Settlement Transactions** | DeltaDeFi | L1 txs attributable to DeltaDeFi Hydra activity  |
| **L1 Fees Generated**          | DeltaDeFi | Protocol revenue contribution from settlements   |
| **L2 Transaction Ratio**       | DeltaDeFi | Hydra txs vs L1 settlements (scaling efficiency) |

#### Dashboard Features

- **Baseline comparison toggle**: Compare current metrics against initial report
- **Historical trends**: Track KPI progress over the 6-month period
- **Open methodology**: Documented queries and methods published under open licence

### 3. Final 6-month Vision 2030 Progress Report

At the end of the 6-month period, DeltaDeFi will publish a **Vision 2030 progress report** assessing DeFi infrastructure advancement:

| Assessment Area        | Comparison                                           |
| ---------------------- | ---------------------------------------------------- |
| **DeFi Vertical KPIs** | Baseline vs current slippage, spread, depth, CEX gap |
| **Adoption KPIs**      | TVL and MAU growth over period                       |
| **Scalability KPIs**   | L1 footprint and L2 transaction efficiency           |
| **Suggested Targets**  | Actual vs proposed targets from baseline             |

The report will comment on:

- Progress toward Vision 2030 DeFi vertical goals;
- Remaining gaps and recommended next steps; and
- Lessons for future Treasury-funded DeFi infrastructure.

The budget reserved for this programme (baseline report, dashboard and final report) is **payable at the end of the 6-month period** upon delivery and DAC sign-off.

---

## Fund Release Schedule

Funds will be released in three phases over the 6-month project duration:

| Phase   | Amount   | % of Total | Release Date   | Cumulative |
| ------- | -------- | ---------- | -------------- | ---------- |
| Phase 1 | ₳560,000 | 37.3%      | Project Start  | ₳560,000   |
| Phase 2 | ₳560,000 | 37.3%      | End of Month 3 | ₳1,120,000 |
| Phase 3 | ₳380,000 | 25.3%      | End of Month 6 | ₳1,500,000 |

### Release Approval Mechanism

Fund releases are governed by the **DeltaDeFi Administration Committee (DAC)** as defined in the Administration section below.

### Safeguard: Fund Return Policy

If the DAC multisig (4-of-6) votes to stop the project:

1. The project will be immediately suspended.
2. All remaining funds will be returned to the Cardano Treasury.
3. A public report detailing the reason for suspension will be published within 14 days.

Any unused funds from completed phases will also be returned to the Treasury at project conclusion.

### Summary

| Safeguard            | Description                                                    |
| -------------------- | -------------------------------------------------------------- |
| Phased Release       | 3 tranches tied to project timeline                            |
| Independent Approval | Per Administration Committee multisig for Phase 2 & 3          |
| Founder Recusal      | DeltaDeFi representatives excluded from release votes          |
| Fund Return          | DAC multisig vote to stop = remaining funds return to Treasury |
| Transparency         | Public report required if project suspended                    |

---

## Budget and Administration

**Total budget:** ₳1,500,000 over 6 months. Breakdown:

- **₳1,120,000 – Hydra trading infrastructure**

  - Core engineering for the matching engine, API, Hydra integration and indexers;
  - Operations, infra and security (hosting, monitoring, incident response);
  - Wallet and protocol integrations and production support.

- **₳280,000 – Vision 2030 KPI Measurement Programme**

  - Initial "State of Cardano DeFi" baseline report;
  - Public Vision 2030 KPI dashboard implementation and maintenance;
  - Final 6-month Vision 2030 progress report.

- **₳100,000 – Administration and independent audit**
  - Administration multisig operations (transaction fees, bookkeeping, reporting);
  - **Independent financial and technical audits** of funded work and spending;
  - Preparation and publication of audit summaries for the community.

### Administration committee and multisig

A future **Treasury Withdrawal GA** based on this Info Action will specify a **DeltaDeFi Administration Committee (DAC)** as the administrator for the budget. The intended DAC composition is as below:

DeltaDeFi representatives:

- **Hinson Wong** (Co-founder of DeltaDeFi)
- **Anson Chui** (Co-founder of DeltaDeFi)

Ecosystem representatives:

- **Mike Hornan** (Cardano Ambassador / Governance Educator)
- **James Meidinger** (CEO, Freeblocks LLC / BizDev, USDM Moneta non-representative capacity)
- **Hosky** (ecosystem representative)
- **One additional community / ecosystem representative (TBC)**

All Treasury-related funds and assets for this budget will be held under a **4-out-of-6 multisig** controlled by the DAC. Any movement of ADA from the administration addresses (for example, milestone disbursements, payment of audit costs) will require at least **four affirmative signatures out of six**.

The Withdrawal GA will also specify that:

- Funds are held in **segregated, publicly auditable addresses**, separate from other project funds or personal wallets;
- These addresses are **delegated to the auto-abstain option and never to SPOs**, in line with the Constitution; and
- Funds will be released according to the **Fund Release Schedule** above:
  - **Phase 1 (₳560,000)** and **Phase 2 (₳560,000)** cover the ₳1,120,000 infrastructure development budget;
  - **Phase 3 (₳380,000)** covers the ₳280,000 Vision 2030 KPI Measurement Programme and ₳100,000 administration/audit costs, payable upon end-of-period delivery and DAC multisig sign-off.

### Independent audit and review

- Part of the **₳100,000 administration and audit budget** will fund an **independent auditor**, in line with the Cardano Constitution’s auditor requirement for Treasury-funded work.
- The Treasury Withdrawal GA will specify the auditor’s role, scope and reporting cadence, and audit results will be summarised publicly so the community can verify how funds were used.

---

# Alignment with Cardano Vision 2030

This proposal supports multiple pillars of the **Cardano Vision 2030** strategic framework.

## Strategic Alignment

| Vision 2030 Priority                                                                         | DeltaDeFi Contribution                                               |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| **Pillar 1: L2 Integration** – "High-frequency, low-latency transactions with L1 security"   | Production-grade Hydra trading venue proving L2 works for DeFi       |
| **Pillar 2: DeFi Vertical** – "Institutional-grade liquidity and usable Cardano-native DeFi" | Order-book infrastructure for professional traders and market makers |
| **L2 → L1 Value Retention** – "Layer 2 solutions contribute value back to the L1 protocol"   | Settlement fees from Hydra activity flow back to L1                  |
| **Scalability** – "3x current throughput capacity"                                           | Validates L2 scaling approach for high-volume use cases              |

## Contribution to Vision 2030 KPIs

| Vision 2030 KPI             | 2030 Target | DeltaDeFi Impact                                 |
| --------------------------- | ----------- | ------------------------------------------------ |
| **Total Value Locked**      | $3B         | Attracts liquidity via competitive trading       |
| **Monthly Active Users**    | 1M          | Professional and retail traders                  |
| **Annual Protocol Revenue** | ≥16M ADA    | L1 settlement fees from Hydra activity           |
| **Throughput Capacity**     | 3x current  | Proves L2 can handle high-volume activity off L1 |

Note: The **Monthly Transactions** KPI (≥27M) measures L1 on-chain activity. As a Hydra-based L2 solution, DeltaDeFi contributes indirectly through L1 settlement transactions rather than direct transaction count. This aligns with Vision 2030's L2 integration strategy where "high-volume activity can move off L1 and settle back."

## Suggested KPIs for This Proposal

### Ecosystem Impact

| KPI                            | 6-Month Target       | Measurement              |
| ------------------------------ | -------------------- | ------------------------ |
| **DeltaDeFi TVL**              | Measurable growth    | On-chain locked value    |
| **Monthly Trading Volume**     | Production-scale     | Matched order volume     |
| **Active Traders (MAU)**       | Growth from beta     | Unique trading addresses |
| **L1 Settlement Transactions** | Documented footprint | L1 txs from DeltaDeFi    |

### Market Quality (per dashboard and reports)

| KPI                             | Target                  | Measurement              |
| ------------------------------- | ----------------------- | ------------------------ |
| **ADA/USDM Slippage (10k ADA)** | Improvement vs baseline | Simulated execution cost |
| **Bid-Ask Spread**              | Tighter than baseline   | Average spread           |
| **Price Gap vs CEX**            | Reduced gap             | Deviation from CEX mid   |
| **Depth within ±1%**            | Increased               | Near-mid liquidity       |

### Operational

| KPI                  | Target                                     |
| -------------------- | ------------------------------------------ |
| **Platform Uptime**  | Public status page with incident reporting |
| **API Availability** | Documented uptime metrics and post-mortems |
| **Baseline Report**  | Month 1-2                                  |
| **Dashboard Live**   | Month 2-3                                  |
| **Final Report**     | Month 6                                    |

---

# Constitutionality Checklist (Info Action scope)

- **Purpose**

  - This proposal is for work intended to enhance the **liquidity, usability and long-term sustainability** of Cardano by providing Hydra-based trading infrastructure and transparent trading-quality metrics. It fits within **Article IV.1** as a budget for the future development of the ecosystem.

- **Article III.5 – On-chain governance process**

  - The proposal will be submitted in a clear, standard format with:
    - Title, abstract, motivation and rationale; and
    - A URL and content hash for this off-chain document.

- **Info Action nature**

  - This is a **Budget Info Action**, not a Treasury Withdrawal:
    - It **does not move any ADA** from the Treasury; and
    - It records DRep and community sentiment on whether a **₳1,500,000, 6-month budget** for DeltaDeFi Hydra trading infrastructure and market-quality metrics is desirable in principle.

- **Article IV – Budgets and Treasury Withdrawals (future work)**
  - Any subsequent Treasury Withdrawal GA based on this Info Action will:
    - Respect the **Net Change Limit (NCL)** in effect at the time (amount and timing);
    - Specify an administrator and administration model in line with **Article IV.2**;
    - Make explicit provision for **an independent auditor and audit process** in line with Article IV.4 (including dedicated budget and reporting expectations).
    - Ensure funds are held in **segregated, auto-abstain-delegated addresses** while under administration.

---

# Conclusion

This Budget Info Action asks whether the Cardano community supports dedicating **₳1,500,000 over 6 months** to:

- Harden and scale **DeltaDeFi** into a production-grade Hydra trading venue for ADA and key CNT pairs; and
- Deliver a **Vision 2030 KPI Measurement Programme** with baseline report, public dashboard, and progress report tracking DeFi infrastructure contribution to ecosystem goals.

The intent is not to fund a niche application, but to strengthen **Cardano's core trading infrastructure** in alignment with **Vision 2030's DeFi vertical** ("institutional-grade liquidity and usable Cardano-native DeFi") and provide measurable data on progress toward ecosystem KPIs.

Voters are not yet asked to approve any withdrawals. They are asked to signal whether this direction — **supporting Hydra-based trading infrastructure and Vision 2030-aligned KPI measurement** — is a good use of Treasury budgeting for the next 6 months.
