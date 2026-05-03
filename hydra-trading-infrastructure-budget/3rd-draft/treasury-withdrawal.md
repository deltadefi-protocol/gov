# DeltaDeFi: Cardano's Flagship Exchange — Treasury Withdrawal (₳5,000,000)

# Abstract

DeltaDeFi proposes a ₳5,000,000 investment from the Cardano Treasury over 24 months, paired with a binding repayment structure and a perpetual revenue share that returns value to ADA holders for the life of the protocol.

DeltaDeFi is a Hydra-based, low-latency order-book exchange that has been live on Cardano mainnet since Cardano Summit 2025. With $20,000 of in-house market-making capital deployed, the venue currently holds the best execution price for ADA on Cardano at a 20 bps spread on ADA/USDCx, has matched $607,000 of cumulative trading volume, and serves 169 active traders. Working infrastructure is running today; this proposal funds its hardening and scale-up.

The investment terms:

- ₳5,000,000 ADA-denominated, disbursed in two pools across 24 months
- 50% of retained trading fees flow back to the Cardano Treasury monthly until the ₳5,000,000 is fully repaid
- 15% of retained trading fees flow to the Cardano Treasury in perpetuity once principal is repaid, establishing a permanent income stream for ADA holders
- All funds administered by Intersect via the 2025 TRSC framework, with a third-party assurer validating each milestone

The aim is to fill a strategic gap in the Cardano ecosystem — the absence of a flagship exchange — and to establish a treasury-investment model that returns value to ADA holders.

---

# Motivation

## The Gap

The most performant trading venues have become identity-defining infrastructure for the blockchain ecosystems that succeeded in attracting capital and traders. Hyperliquid built its own Layer 1 specifically to host an on-chain order book and now clears tens of billions of dollars in daily volume, on par with major centralized exchanges. Solana has Drift for perpetuals and Jupiter for execution routing. Ethereum's flagship performant venues live on its Layer 2 ecosystem — Lighter, a zk-rollup perp DEX that recorded over $279 billion of 30-day trading volume in late 2025; GMX on Arbitrum, integrated with 70+ DeFi protocols; and dYdX, which originally launched on Ethereum's StarkEx Layer 2 before migrating to a purpose-built Cosmos-based chain to deliver the performance its order book required.

The pattern is consistent: serious trading venues require chain-level performance characteristics that general-purpose Layer 1 designs cannot deliver. They live on Layer 2s, on app-specific chains, or on purpose-built Layer 1s — wherever the execution constraints can actually be met. The blockchain ecosystems that produced these venues won the resulting liquidity, trader mindshare, and mainstream attention.

After nearly ten years of existence, Cardano has produced no equivalent. There is no Cardano-native order-book venue clearing serious volume, no purpose-built trading infrastructure that professional traders integrate against, no chain-level demonstration that Cardano can host high-frequency on-chain trading.

This is the structural reason behind the "ghost chain" narrative that has dominated mainstream coverage of Cardano. While other ecosystems clear $1 billion or more in daily DEX volume, Cardano typically sits at $1–5 million daily. The volume gap is the single most cited fact in the case against Cardano's relevance, and it has compounding effects: less retail attention, less capital allocation, less developer interest, less ecosystem credibility.

## Why filling the gap matters

A flagship exchange functions as core infrastructure for an L1 ecosystem:

- Price-discovery anchor for ADA and Cardano-native tokens that other DEXs and CEXs reference for arbitrage
- Liquidity destination that professional market-makers, arbitrageurs, and institutional desks integrate against
- Public-facing benchmark against which the rest of the world judges Cardano's DeFi maturity
- Base layer on which higher-order products (vaults, structured strategies, Real World Asset venues, agentic trading systems, cross-chain liquidity routing) are built

DeltaDeFi believes filling this gap is a key building block for Cardano returning to a competitive position among Layer 1 ecosystems. This proposal asks the Cardano Treasury to invest in that outcome on terms designed to return value to ADA holders.

## What's already on mainnet

DeltaDeFi has been operating on Cardano mainnet since Cardano Summit 2025. Three months in, the operational results are concrete:

| Metric | Current value |
| --- | --- |
| Time live on mainnet | ~3 months |
| Live trading pair | ADA/USDCx |
| Current spread on ADA/USDCx | 20 bps |
| Best ADA execution price on Cardano | Yes |
| In-house market-making capital deployed | $20,000 USD |
| Cumulative trading volume since launch | $607,000 USD |
| Active trading users | 169 |
| Per-trade fee | 0.10% (10 bps) flat |
| Order confirmation latency | sub-second (Hydra L2) |
| API | Binance-compatible REST + WebSocket |
| Custody model | Self-custody, non-custodial, L1 settlement |

Capital efficiency is the most important number. $20,000 of market-making capital has supported $607,000 of trading volume — a ~30× capital turnover that no Cardano AMM venue matches. The advantage is structural: AMM venues require an order of magnitude more locked capital to maintain comparable spreads, due to the constant-product invariant their pools rely on. DeltaDeFi's order-book design with in-house market-making delivers more execution quality per ADA of working capital than any existing Cardano DEX.

The venue works today. This proposal funds the scale-up — on terms designed to return the investment, plus a permanent income stream.

---

# The team

DeltaDeFi is built by SIDAN Lab. The team's case for execution rests on what is already running on mainnet today.

**Live execution.** Three months of production mainnet trading demonstrates execution capability concretely. Every claim in this proposal is verifiable on-chain right now: the spread, the volume, the user count, the smart contract code, the matching engine behaviour. Concept-validation has already happened, with no Treasury support, before this proposal was written.

**Long-term Cardano commitment.** SIDAN has operated as a single Stake Pool Operator since 2021 and has been an active DRep in Cardano governance. The Cardano Hong Kong community organised by SIDAN runs local meetups, workshops, and developer education on a continuing basis. Two of the team's principals — Hinson Wong (CEO) and Neal Lam — are recognised Cardano Ambassadors, the formal recognition programme run by the Cardano Foundation for individuals making sustained, verifiable contributions to the ecosystem. Ambassador status is granted and maintained on the basis of ongoing community work, public education, and ecosystem advocacy, and requires identifiable individuals with public track records. The team has been contributing to Cardano for the duration of the network's existence, with Foundation-recognised standing in the community.

**Verifiable identities and open-source surface area.** The co-founders are verifiable individuals with auditable backgrounds — Hinson Wong (CEO, ex-Citi, CFA), Anson Chui (COO, CISSP and CISA certified), Jackal Leung (CTO, 5+ years full-stack engineering). The `deltadefi-protocol` GitHub organisation maintains 14+ public repositories, all Apache-2.0 licensed, including the smart contracts, transaction-building libraries, and SDKs across TypeScript, Python, Go, and Rust. The team also contributes to Whisky, Vodka, and Hydra (forked, contributing). Code written in service of DeltaDeFi is in the open and reviewable.

---

# Differentiation

Two questions about DeltaDeFi's position in the Cardano landscape merit direct answers.

## How DeltaDeFi relates to Minswap and other AMMs

DeltaDeFi and AMM venues like Minswap or SundaeSwap operate different markets. AMMs serve passive swappers — single-click execution against pooled liquidity. DeltaDeFi serves professional traders, market-makers, arbitrageurs, and API-driven participants — limit orders, tight spreads, deterministic fills. The user populations differ, the products differ, and the on-chain mechanics differ.

The interaction between order-book and AMM venues is complementary. Tighter on-chain price discovery on DeltaDeFi creates arbitrage opportunities that AMM venues absorb as additional volume. Since DeltaDeFi launched on mainnet, observed CEX-to-DeltaDeFi-to-L1-DEX arbitrage flows have directly increased trading volume on existing Cardano AMMs. Funding DeltaDeFi adds AMM volume.

The capital-efficiency point compounds this. DeltaDeFi achieves 20 bps spreads on $20,000 of market-making capital. AMM venues require substantially more locked capital to achieve comparable spreads — this is structural to the constant-product invariant. The Treasury's investment in DeltaDeFi funds infrastructure that delivers more execution quality per ADA of locked capital than any existing Cardano DEX.

## How the structure protects the Treasury

No proposal can guarantee long-term survival. Three months on mainnet and 169 users is meaningful evidence of operational competence, but it is not yet evidence of long-term survival. Any DRep who watched AXO collapse knows that early traction does not predict outcomes.

The Cardano Treasury does not need to bet on DeltaDeFi's long-term survival for this proposal to make sense. The investment structure protects ADA holders across all three outcome scenarios:

If DeltaDeFi succeeds at flagship-venue scale, the Treasury receives 50% of retained trading fees until the ₳5,000,000 is fully repaid, plus 15% of retained trading fees in perpetuity. Even modest success — sustained capture of a few percent of Cardano monthly DEX volume over a few years — returns multiples of the initial investment to ADA holders.

If DeltaDeFi delivers partially before failing, the milestone-gated tranche structure clawbacks undisbursed Pool A funds. The Pool B diversion clause recovers any working capital not deployed for its stated purpose. Pool A funds already disbursed for delivered milestones remain spent — delivered work is paid for. The Treasury's downside is bounded by the refund and clawback clauses.

If DeltaDeFi fails entirely — operational shutdown, team dissolution, no further trading activity — the open-source artifacts produced under this funding remain available to the Cardano ecosystem. Apache-2.0 smart contracts, multi-language SDKs, operator tooling, audited Hydra integration, decentralization documentation, and operational learnings persist regardless of whether DeltaDeFi the entity persists. The Treasury's investment is partially recovered as durable, reusable public infrastructure that the next team to attempt this can build on.

Every plausible outcome — full success, partial delivery, complete failure — leaves the Cardano ecosystem and its Treasury better off than they would be without the engagement. The Treasury is being asked to evaluate whether the proposal's structure makes the investment sound. We believe it does.

---

# What this proposal funds

## Vision and 24-month roadmap

**Vision: Building the infrastructure of the future financial system.**

With DeltaDeFi's Hydra-based tech stack, a spectrum of networks — from fully permissioned venues operated by regulated institutions to fully permissionless venues like DeltaDeFi itself — can operate side by side and interoperate as a single execution surface. Value flows across the boundary between regulated and decentralized realms, rather than being trapped on one side.

At the product layer, DeltaDeFi will look broadly similar to peer venues such as Hyperliquid: an order-book exchange surrounded by vaults, strategy primitives, and derivatives. The vision differs. Hyperliquid is building an open chain to host any financial activity. DeltaDeFi is building, more pragmatically, the stack for a future financial operating system — one that acknowledges the persistent need for permissioned layers (regulated venues, institutional custody, jurisdiction-bound assets) and treats interoperability between permissioned and permissionless systems as the central design problem.

The 24 months funded by this proposal are the spot-DEX hardening, scale-up, and decentralization work that make those higher-order primitives possible. Roadmap by phase:

| Phase | Months | Focus |
| --- | --- | --- |
| Phase 1 | 0–6 | Hardening core technology — Hydra, matching engine, product mix. AI-native platform foundations: MCP (Model Context Protocol) support, fine-grained access control on agentic accounts, open framework for AI trading strategies. |
| Phase 2 | 7–12 | Multi-chain integration (BTC, Midnight, EVM). On-/off-ramp integrations. Community node operators introduced (binding milestone, see Decentralization). |
| Phase 3 | 13–18 | Decentralization — DAO-based rotation of Hydra node operators (subject to upstream Hydra readiness). Product additions as demand is identified: RWA listings, additional financial derivatives. |
| Phase 4 | 19–24 | Open governance in practice — token launch and operational governance handoff such that the DeltaDeFi team is replaceable for ongoing operation. The binding end-of-project commitment is operational open governance by Month 24; the M18 target above is aspirational and depends on Hydra readiness. |

The existing DeltaDeFi platform is architected for these directions: items above are designed as feature integrations on the existing tech stack rather than ground-up rebuilds. Tactical sequencing within each phase remains flexible — the trading-infrastructure space moves too fast for honest 24-month feature commitments — and Treasury accountability is enforced through the financial structure described below.

## Two-pool budget structure

| Pool | Amount | Release | Purpose |
| --- | --- | --- | --- |
| Pool A — Operating Budget | ₳2,500,000 | Tranched across 4 phases of 6 months: ₳625,000 per phase | Engineering, security audits, operations, infrastructure, documentation |
| Pool B — Working Capital | ₳2,500,000 | Released as Phase 1, deployed to in-house market-making operations on the DeltaDeFi spot DEX | Scaling the proven capital-efficiency MM model from $20k to flagship-venue book sizes |

Total: ₳5,000,000 over 24 months — ~₳208,000/month average, lower than the per-month rate of the previous (rejected) ₳1,500,000 / 6-month proposal.

## Pool B operational design

Pool B is operationally distinct from Pool A and warrants explicit description. The current $20,000 of in-house MM capital is the largest single proof point of capital efficiency in this proposal. Scaling that proven model to flagship-venue book sizes requires working capital deployed in the order book to generate the trading fees that pay the Treasury back, rather than capital consumed as engineering payroll.

Order-book venues cannot bootstrap from zero working capital — depth attracts traders, traders generate fees, fees fund deeper depth. $20,000 of in-house MM capital was sufficient to prove the model and reach 169 active traders; reaching the volume tier where Treasury repayment becomes meaningful (see Repayment trajectory) requires book depth that retail-scale capital cannot supply. Pool B is the structural answer to that chicken-and-egg, not a discretionary ask.

Operating market-making at flagship-venue scale requires active custody and frequent movement of capital — between DeltaDeFi's own venue, hedging counterparties, off-exchange wallets, and cross-venue transfers. Pool B therefore cannot be held statically in segregated TRSC custody the way Pool A tranches are. The accountability mechanism for Pool B is structurally different: continuous transparency and a diversion clawback, rather than static custody.

Specifically:
- Pool B is released to DeltaDeFi-controlled MM operational accounts on enactment, after the third-party assurer verifies that the intended deployment matches the Pool B mandate (DeltaDeFi market-making operations on the live spot DEX, including necessary cross-venue movements and hedging required by MM strategy)
- DeltaDeFi has operational custody of Pool B during deployment, including the discretion to move capital between exchanges, hot wallets, and hedging accounts as MM operations required
- DeltaDeFi publishes quarterly market-making PnL and book-composition disclosures for the duration of the project, broken out by venue category where material
- Internal asset composition (ADA vs. quote assets within the MM book) is determined by the team's MM strategy
- All trading fees generated on the DeltaDeFi spot DEX from Pool-B-deployed market making flow into the standard 50% Treasury repayment share — the working capital deployed by the Treasury contributes directly to repaying the Treasury
- The diversion clause (see Refund and clawback) governs use: any deployment of Pool B for purposes other than the stated MM mandate is grounds for clawback, regardless of which venue the funds happen to sit in at any given moment

## Phase structure (Pool A)

Disbursement gating is designed around investment-grade accountability — financial performance, transparency compliance, and a small number of binding external commitments. The team retains discretion over tactical execution within the directional roadmap. Treasury protection comes from the financial structure (revenue share, perpetual share, refund and clawback clauses).

| Phase | Months | Tranche | Release conditions |
| --- | --- | --- | --- |
| Phase 1 | 0–6 | ₳625,000 | Production-hardening deliverables for the live spot DEX: third-party security audit complete, public status page live, API SLA defined, incident response runbooks published, public protocol-fee transparency dashboard live (the dashboard supports the monthly Treasury fee disclosure commitment). |
| Phase 2 | 7–12 | ₳625,000 | Community node operators introduced per the public decentralization roadmap. Transparency cadence in good standing — monthly fee breakdowns and quarterly assurer + MM PnL reports delivered without material findings or omissions. |
| Phase 3 | 13–18 | ₳625,000 | Transparency cadence in good standing through the prior period. Repayment trajectory active — Treasury fee remittance flowing per the published methodology with no unresolved discrepancies. |
| Phase 4 | 19–24 | ₳625,000 | Transparency cadence in good standing through the prior period. Repayment trajectory active. Final 24-month retrospective report published, covering operational outcomes, financial performance, and decentralization roadmap status. |

Each tranche is gated by review by the third-party assurer, with a 90-day cure window before clawback if a release condition is not met. Release conditions focus on observable accountability — security and transparency artifacts in Phase 1, one binding decentralization milestone in Phase 2, and continuous financial and reporting compliance thereafter.

---

# Treasury investment structure

The Cardano Treasury operates as a senior investor in DeltaDeFi for the duration of this engagement and beyond.

## Repayment terms

During the repayment period:
- DeltaDeFi remits 50% of retained trading fees to the Cardano Treasury, monthly, ADA-denominated, until 100% of the ₳5,000,000 has been returned.
- "Retained trading fees" means gross matched-order fees collected by the protocol, net of market-maker rebates and partnership fee-share payouts, before any other distribution.
- Treasury share is calculated before any internal protocol-level distributions, including any token-related distributions, internal fee router splits, or other discretionary allocations.
- Listing fees, token sale revenue, and market-maker PnL on DeltaDeFi entity capital sit outside the revenue base.
- Repayment is ADA-denominated: the obligation is satisfied when 5,000,000 ADA has been remitted, regardless of ADA price movement.

After repayment is complete:
- DeltaDeFi remits 15% of retained trading fees to the Cardano Treasury in perpetuity, on the same monthly cadence and using the same revenue definition.
- The 15% perpetual share is the primary long-term return to the Treasury, establishing an indefinite income stream for ADA holders for the life of the protocol.

## Repayment trajectory

At ₳1 = $0.25, ₳5,000,000 ≈ $1,250,000 USD. With a 0.10% per-trade fee and the 50% Treasury share applied to retained fees, the Treasury's effective share is ~0.05% (5 bps) of matched volume. Time-to-full-repayment is therefore a direct function of sustained monthly volume.

The 24-month operational ramp targeted by this proposal is an S-curve: slow during Phase 1 hardening, steep through Phases 2–3 as Pool B is deployed, multi-chain integration goes live, and node operators come online, approaching the $10M/day target by Month 24. The ramp explicitly assumes volume across multiple chains (BTC, EVM, Midnight, Cardano), not Cardano-native pairs alone — the multi-chain integration in Phase 2 is what unlocks the addressable volume needed.

| Phase end | Target daily volume | Target monthly volume | Approx. monthly Treasury remittance | Approx. cumulative remitted by phase end |
| --- | --- | --- | --- | --- |
| End of Phase 1 (M6) | ~$50K | ~$1.5M | ~$750 | ~$25K |
| End of Phase 2 (M12) | ~$1M | ~$30M | ~$15K | ~$200K |
| End of Phase 3 (M18) | ~$5M | ~$150M | ~$75K | ~$1.0M |
| End of Phase 4 (M24) | ~$10M | ~$300M | ~$150K | ~$2.5M |

Under this trajectory, the ₳5,000,000 principal is fully repaid mid-Phase 4, with the perpetual 15% Treasury share continuing thereafter for the life of the protocol. The trajectory is a target, not a guarantee — if the ramp slips, repayment slips with it, and the perpetual 15% share continues regardless of how fast principal is repaid. The ramp and resulting repayment are tracked publicly via the monthly transparency commitments below.

## Treasury's position relative to other claimants

The Treasury share is structurally senior to all internal protocol-level distributions. The 50% / 15% applies to the gross retained-fee base and is computed first; DeltaDeFi cannot dilute the Treasury share by introducing or modifying internal allocation mechanisms.

## Transparency commitments

Monthly:
- Public published breakdown of: gross matched-order fees collected → market-maker rebates paid → partnership fee-share payouts → retained-fee base → Treasury share remitted → on-chain remittance transaction reference

Quarterly:
- Public published market-making PnL for Pool-B-deployed capital, with book composition as of period end
- Public progress report against milestone deliverables for the current phase
- Independent third-party assurer report

These transparency commitments persist for the full life of the perpetual revenue share, well beyond the 24-month build period.

## Investment versus grant

Most treasury-funded proposals are grants. ADA flows out, work is delivered, the Treasury captures value indirectly through ecosystem effects.

DeltaDeFi proposes a different structure: the Treasury invests, the principal returns, and a permanent income stream is established. The total expected value to the Treasury from this proposal is the sum of (i) the principal repayment of ₳5,000,000, plus (ii) the perpetual 15% revenue share for as long as the protocol operates. If DeltaDeFi succeeds at the scale this proposal targets, the perpetual share alone returns many multiples of the initial investment over time. If outcomes fall short, the refund and clawback clauses (below) protect undisbursed and divertable funds.

This structure also aims to establish a working model for treasury-as-investor in commercial Cardano initiatives — addressing the gap in the ecosystem's funding stack between Catalyst grants, Orion Fund equity, and pure private capital.

---

# Administration

All funds are administered by Intersect via the 2025 TRSC (Treasury Reserve Stake Contract) framework, the same framework adopted by other treasury-investment proposals. This means:

- Funds remaining under administration (undisbursed Pool A tranches and the pre-release Pool B balance) are held in segregated, publicly auditable addresses, separate from any DeltaDeFi or personal wallets
- Funds under administration are delegated to the predefined auto-abstain voting option per Constitution Article V §5, never to a Stake Pool Operator
- Multi-signature thresholds and disbursement procedures follow Intersect's standard TRSC framework, with the 2025 TRSC oversight committee providing administration governance
- A third-party assurer validates the completion of each Pool A phase milestone before the corresponding tranche is released, and verifies the Pool B deployment plan before Pool B is released on enactment. The assurer is funded from this withdrawal as part of standard TRSC operating costs.
- The third-party assurer is selected from Intersect's qualified entity list per the standard TRSC selection process.

DeltaDeFi takes custody of Pool A tranches only after milestone validation by the assurer. Pool B is released to DeltaDeFi-controlled MM operational accounts on enactment after assurer verification of the deployment plan, and remains in DeltaDeFi operational custody during the project (necessary for market-making operations across exchanges and hedging counterparties). Pool B accountability runs through quarterly PnL transparency and the diversion clawback (see Refund and clawback below), not through ongoing TRSC custody.

# Refund and clawback

The proposal commits to the following refund and clawback clauses:

| Trigger | Cure Window | Action |
| --- | --- | --- |
| Milestone failure — third-party assurer determines a phase milestone has not been met | 90 days | Suspended phase tranche withheld; if uncured, all undisbursed funds clawed back to the Treasury |
| Team dissolution — DeltaDeFi entity ceases operations or core team departs | 30 days | All undisbursed funds returned + all unspent disbursed Pool A funds returned + Pool B returned to the extent recoverable |
| Voluntary termination — DeltaDeFi voluntarily withdraws from the engagement | 30 days | Same as team dissolution |
| Pool B diversion — third-party assurer determines Pool B funds have been used for purposes other than the stated MM mandate (DeltaDeFi market-making operations and the cross-venue movements / hedging required to support them) | 30 days | Diverted amount returned in full + project suspension review |
| Partial delivery — some phases delivered, others not | n/a | Only undelivered-phase funds refunded; delivered-phase work is paid for |

"Pool B returned to the extent recoverable" reflects the operational reality that working capital deployed in market making is at risk in the same way any operating capital is at risk. The diversion clause and quarterly PnL transparency provide structural protection against misuse.

---

# Decentralization

DeltaDeFi maintains a public decentralization roadmap at deltadefi.io, structured around the principle that decentralization is the goal and Hydra protocol maturity is the prerequisite.

Two binding commitments within this proposal's window:

- **By Month 12** — community node operators introduced. Binary, auditable, verified by the third-party assurer.
- **By Month 24** — operational open governance live. Token launched, governance over node-operator selection in the hands of token holders, and the DeltaDeFi team operationally replaceable for ongoing operation of the venue. This is the binding end-of-project commitment.

Within that window, the team aims to hit the open-governance milestone by Month 18 so that Months 19–24 are spent practising the governance mechanism in production rather than launching it. That M18 target depends on upstream Hydra readiness for trustless multi-operator setups, which DeltaDeFi cannot unilaterally schedule. If Hydra readiness slips, the M18 aspirational target slips with it; the M24 binding commitment does not.

All operator-related code, smart contracts, and protocol tooling released during this period will be Apache-2.0 licensed, consistent with the existing `deltadefi-protocol` GitHub organisation.

---

# Alignment with Cardano Vision 2030

This proposal supports several themes of the Cardano Vision 2030 strategic framework, primarily under Pillar 1 (Infrastructure & Research Excellence) and Pillar 2 (Adoption & Utility):

- L2 integration — DeltaDeFi is one of the production references for Hydra utility, cited by cardano.org during Hydra's adoption-phase announcement. The strategy framework calls for "high-frequency, low-latency transactions with L1 security" that L2 integration enables.
- DeFi vertical — DeltaDeFi delivers order-book infrastructure that professional traders, market-makers, and integrators expect, and currently provides best-in-ecosystem ADA execution. The strategy framework's DeFi vertical includes "secure, institutional-grade liquidity onramps."
- Treasury sustainability — the perpetual revenue share model establishes a precedent for commercial proposals returning value to ADA holders, contributing to sustainable treasury practice.

---

# Constitutionality Checklist

- Article IV §1 — Cardano Blockchain ecosystem budget. This proposal is submitted as a budget request for treasury withdrawal in service of ecosystem trading infrastructure, consistent with the budget framework Article IV establishes.
- Article IV §2 — Administration. All funds administered by Intersect via the 2025 TRSC framework with a defined oversight committee and standard multi-signature thresholds.
- Article IV §4 — Independent audit. Third-party assurer engaged for the duration of the project, funded as part of the withdrawal, validates each milestone before disbursement.
- Article V §5 — Held-fund delegation. All held funds delegated to the predefined auto-abstain voting option, never to a Stake Pool Operator.
- Article III §5 — On-chain governance process. Standard format with title, abstract, motivation, rationale, off-chain document URL, and content hash.
- Self-contained Treasury Withdrawal. Per the updated Constitution effective January 2026, all ADA treasury withdrawals must be fully self-contained governance actions. This proposal is structured accordingly, rather than as a separate Budget Info Action followed by a withdrawal.

---

# Conclusion

Cardano needs a flagship trading venue. After ten years, the ecosystem has not produced one organically, and the "ghost chain" narrative that has cost Cardano mindshare, capital, and developer attention is rooted in this absence.

DeltaDeFi has spent the last three months proving on mainnet, with no Treasury support, that a Hydra-backed order-book exchange can deliver the best ADA execution price on Cardano at structural capital efficiency that no AMM venue matches. The venue is live. Real users are trading. The proof points in this proposal are on-chain right now.

This proposal asks the Cardano Treasury to invest in scaling that proven venue on terms structured for the Treasury's benefit:

- ₳5,000,000 disbursed over 24 months, half as operating budget, half as protocol-owned working capital
- 50% of retained trading fees flow back to the Treasury until the full ₳5,000,000 is repaid
- 15% of retained trading fees flow to the Treasury in perpetuity thereafter, establishing a permanent income stream for ADA holders
- Intersect 2025 TRSC administration with a third-party assurer, milestone-gated tranches, public monthly transparency, quarterly PnL disclosure, and refund/clawback protections
- Treasury seniority structurally enforced — Treasury share is calculated before any other internal protocol distribution

The Cardano Treasury is being asked to invest in the flagship exchange that already exists on Cardano, on terms that return value to ADA holders for as long as that exchange operates.
