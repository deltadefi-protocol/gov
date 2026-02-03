# DeltaDeFi Budget Info Action: Community Feedback Analysis

This document synthesizes DRep feedback on the 1st draft proposal to inform improvements for a potential 2nd submission. We thank all DReps who took the time to provide detailed rationales—this input is invaluable for strengthening the proposal.

> **Methodology**: To prioritize by voting weight, this analysis focuses on DReps with >2M ADA delegation. All community feedback is valued; this filtering helps identify concerns most likely to influence future voting outcomes.

## Vote Statistics

| Vote    | DRep Count | DRep Voting Power | With Rationale |
| ------- | ---------- | ----------------- | -------------- |
| YES     | 40         | 656.5B            | 16             |
| NO      | 116        | 3,144.8B          | 49             |
| ABSTAIN | 18         | 289.8B            | 11             |

**Outcome**: The proposal did not reach threshold. NO votes represented ~82.6% of voting power among DReps who voted YES/NO.

---

## DReps Providing Substantive Feedback (>2M ADA, NO vote)

| DRep                    | Delegation |
| ----------------------- | ---------- |
| Yoroi                   | 673M       |
| YUTA                    | 463M       |
| EMURGO                  | 297M       |
| CardanoYoda             | 102M       |
| Army of Spies           | 93M        |
| SASA_nagamaru           | 61M        |
| Dave                    | 59M        |
| Aichi/Tokai_DRep        | 38M        |
| Patrick_Tobler          | 38M        |
| Kyle Solomon            | 36M        |
| Cerkoryn                | 24M        |
| Ha-Nguyen               | 21M        |
| Chris [STR8]            | 18M        |
| RCADA                   | 16M        |
| Wada DRep               | 13M        |
| Cardanians              | 8M         |
| InputEndorsers          | 7M         |
| STORM Partners          | 5M         |
| Porto Cripto DRep       | 4M         |
| Varavas, Yepple, others | 2M each    |

---

## Key Feedback Themes

### 1. Public Goods vs Private Benefit (Most Cited)

**Concern**: The proposal is perceived as funding a private commercial DEX rather than neutral, ecosystem-wide infrastructure.

**Specific Feedback**:

- "Projects funded by the Treasury should demonstrate clear and durable ecosystem-wide benefits... the proposal remains structured as a privately operated product and does not clearly articulate how value would flow back to the Treasury or ADA holders" — **EMURGO (297M)**
- "The Treasury should fund shared infrastructure, not individual commercial DEXs. ₳1.5M is an excessive subsidy for a single product that should seek venture capital or Catalyst funding" — **Dave (59M)**
- "This proposal remains predominantly focused on the productionization, operation, and competitiveness of a single branded trading venue, with ecosystem benefits that are indirect" — **RCADA (16M)**
- "Providing a non-dilutive grant of ₳1.5M to a single commercial exchange creates a risk of competitive distortion, effectively asking the Treasury to 'pick winners'" — **STORM Partners (5M)**

**Potential Improvements**:

- Clearly articulate reusable, open-source components that benefit the entire ecosystem
- Specify licensing (Apache/MIT) and API access for third parties
- Define what components can be operated/replicated by other teams
- Consider restructuring request to separate neutral infrastructure from commercial product development

---

### 2. Liquidity & Adoption Strategy

**Concern**: No concrete plan for attracting liquidity, market makers, or users.

**Specific Feedback**:

- "I couldn't figure out their liquidity strategy. In the end, all DEXes except Minswap are struggling to get liquidity" — **YUTA (463M)**
- "The proposal does not explain how liquidity and users will actually be attracted. Delivering software alone does not bring liquidity or users... The proposal relies on the assumption that market makers and users will arrive once APIs and infrastructure exist, which is not a reliable strategy" — **CardanoYoda (102M)**
- "The strategy relies on an assumption that infrastructure alone will drive adoption, yet it lacks a concrete plan for bootstrapping liquidity or incentivizing market makers, which are the primary drivers of any DEX's success" — **STORM Partners (5M)**
- "A credible plan for market quality (market makers, initial pairs, incentive/distribution design) rather than KPI targets alone" — **Cardanians (8M)**

**Potential Improvements**:

- Include concrete liquidity bootstrapping plan with specific strategies
- Detail market maker outreach results (even if preliminary)
- Specify incentive mechanisms for liquidity providers
- Provide evidence of demand (LOIs, pilot commitments, user research)
- Address competitive landscape and differentiation from existing DEXs

---

### 3. Hydra Trust Model & User Risk (Technical Clarity)

**Concern**: Unclear who operates Hydra heads, custody assumptions, and failure scenarios.

**Specific Feedback**:

- "Key aspects of the Hydra setup remain unclear from a user perspective, including custody assumptions, failure scenarios, and protections if operators are unavailable. This makes it difficult for users to assess risks and trade-offs" — **Yoroi (673M)**
- "I couldn't figure out who runs the Hydra head. Are users required to join the Hydra head? If not, who do they need to trust?" — **YUTA (463M)**
- "What are the exact failure modes (operator down, partial signer collusion, network partition)? Can a user unilaterally exit to L1 if the operator is offline?... Hydra gives L1-equivalent security only to those who are running a node as a participant in that Hydra head" — **InputEndorsers (7M)**
- "Clearly state who operates Hydra heads and production services, what users must trust, failure scenarios (downtime, dispute handling, fund safety), incident response, and runbooks" — **Cardanians (8M)**

**Potential Improvements**:

- Explicitly document current Hydra topology (who runs nodes today)
- Detail trust assumptions users must accept
- Define failure modes and recovery procedures
- Outline decentralization roadmap with auditable milestones
- Clarify fund custody during trading vs settlement

---

### 4. Budget Justification & Transparency

**Concern**: DReps requested more detailed budget breakdown and raised questions about allocation proportions.

**Specific Feedback**:

- "The proposal does not clearly explain how the requested ₳1.5 million budget over six months was benchmarked or justified" — **EMURGO (297M)**
- "Allocating nearly 20% of the total budget to a 'KPI Measurement Program' is, in my view, unjustified. Cardano has recently partnered with Dune, which enables low-cost, public, and reusable dashboards for most of the proposed metrics" — **CardanoYoda (102M)**
- "The requested 1.5M ADA budget does not appear proportionate to the current stage of the project. The justification provided is not sufficient" — **Aichi/Tokai_DRep (38M)**
- "Provide an itemized budget with roles + headcount, expected hours/man-days per workstream, rate per man-day, and major non-labor costs (audit quotes/estimates, infra, legal, tooling)" — **Cardanians (8M)**
- "We view the allocation of 20% of the budget to a proprietary KPI measurement program as an inefficient use of capital, given that neutral ecosystem reporting tools are already sufficient" — **STORM Partners (5M)**

**Potential Improvements**:

- Provide detailed budget breakdown:
  - Headcount by role (engineers, security, SRE, etc.)
  - Time allocation per workstream
  - Rate per man-day with benchmarking
  - Infrastructure costs (cloud, indexers, storage)
  - Audit scope and estimated cost
- Reduce or justify KPI dashboard allocation
- Consider using existing ecosystem tools (Dune) for analytics

---

### 5. ROI & Treasury Return Mechanism

**Concern**: No equity, revenue share, or repayment structure for Treasury investment.

**Specific Feedback**:

- "The proposal does not clearly articulate how value would flow back to the Treasury or ADA holders if the project succeeds, whether through repayment terms, revenue sharing, or other mechanisms" — **EMURGO (297M)**
- "Cardano governance has previously required the SNEK project to convert its proposal into a loan. Applying a similar standard here would support fairness" — **CardanoYoda (102M)**
- "I want to encourage teams to figure out a way for treasury withdrawals like this to give some allocation of Tokens, Tokenized Equity or Revenue Share of the project to the Treasury. By approving this proposal, we'd set a bad precedent" — **Patrick_Tobler (38M)**
- "I don't believe the Cardano Treasury should be used to subsidize individual dApps via grant-style funding... I'd rather see capital deployed through structures that create accountability and potential return to the Treasury (e.g., loans, revenue-share, or equity-like instruments)" — **Cerkoryn (24M)**
- "Any treasury funding given to a private, for-profit entity should be denied unless there is a clear and risk-adjusted repayment schedule" — **Yepple (2M)**

**Potential Improvements**:

- Propose revenue sharing mechanism once profitable
- Consider loan structure with defined repayment terms
- Offer token allocation or equity-like instruments to Treasury
- Define sustainability path to reduce Treasury dependence

---

### 6. Timing & Alternative Funding Sources

**Concern**: Better suited for Project Catalyst or private funding at current stage.

**Specific Feedback**:

- "Hydra adoption across the ecosystem remains nascent. While the technology is live and stable, real economic demand is still emerging and uneven... Funding complex trading infrastructure ahead of demonstrated demand introduces a material risk" — **Wada DRep (13M)**
- "At this stage, I would prefer the team to focus on attracting users and liquidity with what already exists (MVP), rather than requesting a large new budget to continue building" — **CardanoYoda (102M)**
- "I largely view direct treasury withdrawals as being most appropriate for infrastructure that will benefit the entire ecosystem and Catalyst as being more appropriate for individual dApps" — **Army of Spies (93M)**
- "I consider it to be premature given the current market size and liquidity conditions of Cardano DeFi" — **SASA_nagamaru (61M)**
- "Please pursue funds from Builder DAO as they SHOULD be funding you guys" — **Kyle Solomon (36M)**
- "This team would be a better fit for alternative funding and incubation paths like Cardano Builders DAO" — **Cerkoryn (24M)**
- "This proposal should be split up... one or both are probably a better fit for Catalyst and not for a direct treasury withdrawal" — **Chris [STR8] (18M)**

**Potential Improvements**:

- Consider phased approach: smaller Treasury ask + Catalyst funding
- Demonstrate organic traction before large Treasury request
- Explore Builder DAO, VC funding, or ecosystem grants first
- Consider waiting for Pentad/budget framework alignment

---

### 7. Benefit to ADA Holders Unclear

**Concern**: The link between this DEX and broader ecosystem/holder value is not clearly articulated.

**Specific Feedback**:

- "While positioned as infrastructure, the proposal does not clearly explain how this directly benefits ADA holders in practice. Improved infrastructure alone does not guarantee better user outcomes" — **Yoroi (673M)**
- "Treasury withdrawal leads to ADA inflation for ADA holders, so the benefits to ADA holders need to be explained. Adoption of Hydra products does not increase the number of L1 transactions... it does not increase staking rewards or ADA inflows to the treasury" — **YUTA (463M)**
- "This is cool, but I'm not seeing how it's generally beneficial" — **wolf31o2 (23M, ABSTAIN)**

**Potential Improvements**:

- Articulate clear value proposition for ADA holders
- Explain how the project contributes to ecosystem growth metrics
- Address the L2 vs L1 transaction dynamic explicitly

---

### 8. Technical Specification & "CEX-Grade" Definition

**Concern**: Insufficient technical detail and no defined operational standards.

**Specific Feedback**:

- "Each phase should have objective 'done' checks (benchmarks, uptime/SLOs, latency targets, load profiles, rollout gates, go/no-go criteria), not just general outputs" — **Cardanians (8M)**
- "Security reviews/targeted audits needs scope, auditor selection plan, timelines, threat model, and explicit in-scope components" — **Cardanians (8M)**
- "Are there any in-depth decentralization milestones that are auditable (not just 'over time')?" — **InputEndorsers (7M)**
- "The current 'managed' Hydra topology introduces custodial trust assumptions that, without a clear and binding roadmap to decentralization, present a governance risk" — **STORM Partners (5M)**

**Potential Improvements**:

- Define "CEX-grade" with measurable criteria:
  - Latency SLOs (p50, p95, p99)
  - Uptime targets (e.g., 99.9%)
  - Error budgets
  - Incident response playbooks
  - Failover procedures
- Provide technical architecture appendix
- Detail component responsibilities and interfaces
- Include auditable decentralization milestones

---

## Aspects Noted Positively by Supporters

Several DReps who voted YES or provided nuanced feedback highlighted these strengths:

1. **Team Track Record**: Strong delivery history with MeshJS, Catalyst projects
2. **Hydra Validation**: Important stress test for Cardano L2 strategy
3. **Governance Structure**: Multisig, phased releases, return clause appreciated
4. **Open Source Commitment**: Apache license, public repositories
5. **KPI Measurement Program**: Direction valued (if cost-optimized)
6. **Addresses Structural Gap**: Order-book venue needed for Cardano DeFi maturation

---

## DRep Feedback Summary (by delegation)

| DRep           | Delegation | Key Concern                                                    |
| -------------- | ---------- | -------------------------------------------------------------- |
| Yoroi          | 673M       | User benefit clarity, trust model, timeframe                   |
| YUTA           | 463M       | Hydra operator unclear, liquidity strategy, ADA holder benefit |
| EMURGO         | 297M       | Public vs private benefit, ROI mechanism, budget justification |
| CardanoYoda    | 102M       | Budget (KPI 20%), liquidity strategy, loan structure, traction |
| Army of Spies  | 93M        | Better fit for Catalyst, infrastructure vs dApp                |
| SASA_nagamaru  | 61M        | Timing/market maturity, premature                              |
| Dave           | 59M        | Public goods vs commercial DEX, Catalyst/VC funding            |
| Patrick_Tobler | 38M        | ROI mechanism (tokens, equity, revenue share)                  |
| Kyle Solomon   | 36M        | Builder DAO funding, KPIs need refinement                      |
| Cerkoryn       | 24M        | Loan/revenue-share structure, Builder DAO                      |
| RCADA          | 16M        | Funding lane misaligned, restructure for neutral infra         |
| Wada DRep      | 13M        | Timing, demand validation, milestone-gated pilot               |
| Cardanians     | 8M         | Detailed technical specs, budget itemization                   |
| InputEndorsers | 7M         | Hydra topology, decentralization roadmap                       |
| STORM Partners | 5M         | Financial structure, KPI budget, liquidity plan                |

---

## Summary: Top 5 Areas for 2nd Draft Consideration

1. **Clarify public infrastructure vs commercial product distinction** — Consider how to better articulate reusable, neutral components (EMURGO, Dave, RCADA, STORM Partners)
2. **Develop concrete liquidity strategy** — Document market maker outreach, incentive mechanisms, evidence of demand (YUTA, CardanoYoda, STORM Partners)
3. **Detail Hydra trust model** — Explain operator roles, user risks, failure scenarios, decentralization roadmap (Yoroi, YUTA, InputEndorsers, Cardanians)
4. **Provide detailed budget breakdown** — Role-based itemization, benchmark against comparable projects, justify allocations (EMURGO, CardanoYoda, Cardanians, STORM Partners)
5. **Consider ROI mechanism** — Explore revenue sharing, loan structure, or other Treasury return options (EMURGO, CardanoYoda, Patrick_Tobler, Cerkoryn)

---

_Analysis generated from on-chain voting rationale data, February 2026._
