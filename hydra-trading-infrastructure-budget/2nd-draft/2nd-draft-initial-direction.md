# DeltaDeFi 2nd Draft: Direction

Based on DRep feedback from 1st submission (82.6% NO by voting power). Full rationale analysis [here](./cgov-analysis-on-1st-draft.md).

## What We Heard

The most consistent feedback was clear: DeltaDeFi is a commercial trading venue, and the 1st draft did not adequately reckon with that. DReps raised fair questions about why the treasury should fund a private product, what return ADA holders receive, and what accountability exists if the project underperforms.

We agree.

## Our View

A healthy ecosystem is built by participants each acting on their own motivation while creating value for one another. The treasury does not need to limit itself to pure public goods — but it should not simply grant funds to private ventures either.

We believe there is a middle ground: treasury support for private initiatives that meet a higher bar. These should have a clear repayment mechanism to treasury, demonstrated public good elements with synergy to the broader ecosystem, a team with proven track record, and community veterans with real identity and long-term commitment to supporting the treasury.

DeltaDeFi is a private initiative. The 2nd draft will not frame this as neutral public infrastructure.

Instead, the treasury ask will be paired with a **repayment schedule** — a concrete hedge for ADA holders. If DeltaDeFi succeeds, the treasury is repaid. Open source contributions (Hydra production learnings, MeshJS features, tooling) are additional upside, not the basis of the funding request.

This follows precedent. Several DReps referenced the SNEK loan structure as a model, and multiple rationales called for loan, revenue-share, or equity-like instruments for treasury-funded commercial projects.

## What Changes

### Treasury return

- We acknowledge DeltaDeFi is a private initiative, and repayment to treasury is the primary accountability mechanism
- 50% revenue-sharing with treasury, executed monthly, until 100% of the budget is repaid
- No further treasury withdrawal request will be submitted until fully repaid
- If this proposal succeeds, we commit to establishing a permanent revenue-sharing arrangement with the Cardano treasury in a follow-up proposal

### Budget

- KPI dashboard excluded from this proposal
- DeltaDeFi will participate in the next Builder DAO round and incorporate the KPI dashboard there, with the goal of pushing KPI-driven accountability culture across a wider set of builders
- Full budget itemization: headcount by role, man-day rates with benchmarks, and infrastructure costs

### ADA holder benefit

- Whether L2 activity is net beneficial to L1 is an open question that requires experimental data — not productive to argue without evidence
- This proposal does not use increased L1 activity as its primary accountability mechanism — the repayment schedule is a more tangible and verifiable commitment to ADA holders today
- We still believe DeltaDeFi will be beneficial to L1 activity and will continue gathering data for further community discussion, but this is out of scope for this treasury withdrawal proposal
- Relevant metrics will be tracked on a public dashboard (see Budget section above)

### Liquidity strategy

- DeltaDeFi's liquidity strategy relies on capital efficiency, not liquidity depth — our in-house market making is already live on mainnet with tight spreads on ADA/USDM with minimal capital, proving the model works and is ready to scale
- Liquidity vault for retail LPs to provide efficient liquidity is on the roadmap
- Initially, liquidity will be supplied privately with ecosystem partners — viable because DeltaDeFi's order book model enables an order of magnitude better capital efficiency compared to traditional AMM swaps
- Still, DeltaDeFi complements existing Cardano DeFi — since launch, we have observed increased swap volume on L1 DEXs directly DeltaDeFi enables CEX-DeltaDeFi-L1 DEX arbitrage flows, benefiting existing protocols rather than displacing them

### Decentralization and transparency

- DeltaDeFi starts with a single node operator — we have strong incentive to introduce more participants to mitigate reputation risk
- The design philosophy is not how decentralized we are at day one, but how easily the protocol can transition to decentralized operation
- Full documentation of current operator topology, custody assumptions, and failure scenarios
- Decentralization roadmap with auditable milestones
