<div align="center">
  <img width="1117" height="254" alt="Kleo Banner" src="https://github.com/user-attachments/assets/18f0796c-0183-43f2-8907-9ab71701fe52" />
</div>
<hr>
Access to credit in emerging economies depends almost entirely on intermediaries, banks, lenders, and financial institutions who act as trusted third parties to evaluate risk and enforce repayment. While this model works for formal borrowers, it fails for the majority of individuals in *Latin America*, where most workers lack formal income, collateralizable assets, or a credit history. As a result, meaningful participation in financial systems is restricted, and millions rely on informal lending networks with abusive terms.

# Why Kleo?
Kleo is a **tokenless**, undercollateralized lending protocol that turns **real social trust** into **measurable on-chain risk**, so people can access credit without collateral, and lenders can earn yield without becoming underwriters 24/7.

Kleo is built on 3 pillars:

- **Star System (Reputation)**
  A dynamic on-chain reputation score (“Stars”) that grows with successful repayment and responsible vouching. Stars unlock **higher borrowing limits**, **better rates**, and **more influence** in the trust network.

- **Web-of-Trust Vouching (Accountability Layer)**
  Loans require one or more **vouchers** who back the borrower. Vouchers are rewarded when borrowers repay, and penalized when they don’t, making trust expensive to fake and valuable to maintain.

- **Sustainable, Tokenless Incentives**
  Lender yield comes from **real borrower interest**, not emissions. Lenders can stay passive (deposit and earn) or vouch for borrowers to earn **boosted returns**, all while keeping the system economically grounded and scalable.

# How Kleo?
Kleo enables undercollateralized loans through a **shared lending pool**, a **reputation layer**, and a **default loss waterfall** that makes outcomes transparent and predictable:

1. Lending Pool (Core Liquidity Engine)
Lenders deposit stablecoins into a pooled liquidity engine.
They earn a base yield funded by borrower interest—no active management required.

2. Borrow Requests (No Collateral)
Borrowers request a loan amount and term without posting collateral.
Approval depends on reputation + being backed by vouchers (quality and count scale with loan size).

3. Vouching Requirement (Trust -> Underwriting)
To unlock a loan, borrowers must get backed by vouchers who meet minimum reputation requirements.
Vouchers can opt into backing a borrower to earn boosted yield and reputation gains if the loan performs.

4. Verifiable Repayment (On-Chain Proofs)
Repayments are recorded on-chain: timestamped, signed, and publicly auditable.
Borrowers build Stars by paying on time; missed payments are visible and affect reputation.

5. Default Handling (Deterministic Loss Waterfall)
If a borrower defaults, losses are absorbed in a predefined order:
- voucher backing absorbs losses first (where applicable),
- then protocol reserves/buffers (if configured),
- then the remaining impact is distributed proportionally at the pool level.

This makes risk **transparent**, discourages Sybil/collusion through slow reputation buildup + multi-voucher requirements, and keeps the system scalable for micro-loans.


<hr>

# Architecture
## Frontend
- Next.js
- Scaffold TypInk

## SDK
- Node.js

## Smart Contracts
- Ink v6
<hr>

## Deployed contracts
Add soon.

<hr>

# Usual flow for users
<img width="2562" height="1560" alt="flow lender and borrower" src="https://github.com/user-attachments/assets/dec1dac8-04ef-4264-9ab5-66900d5b0548" />

<hr>

> Kleo is launching soon, on Polkadot.
>
> If you want early access to undercollateralized DeFi credit:
>
> 👉 https://kleo.finance
>
> Credit that fits you.

