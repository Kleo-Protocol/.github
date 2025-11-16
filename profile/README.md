<div align="center">
  <img src="/kleo.svg" height=15/>
</div>
# Kleo
Access to credit in emerging economies depends almost entirely on intermediaries, banks, lenders, and financial institutions who act as trusted third parties to evaluate risk and enforce repayment. While this model works for formal borrowers, it fails for the majority of individuals in *Latin America*, where most workers lack formal income, collateralizable assets, or a credit history. As a result, meaningful participation in financial systems is restricted, and millions rely on informal lending networks with abusive terms.
Check our white paper :) [whitepaper](https://docs.google.com/document/d/1cprLlST7alIFdnsflJ7I-The5Y79KM5TBG_fvv-QDZk/edit?usp=sharing)


# Why Kleo?
Kleo combines 3 essential pilar to build *trust* between lendors and borrowers:
- Trust. A consenus protocol that relies on the trust between lendors, the amount of lendors and the score of the borrowers.
- Math. Through probabilistic models and some algorithms we can build trust and let lenders the amount of trust they should put into a borrower.
- Credit score onchain. Leveraging all these txs to prove that some users actually deserve benefits for they good reputation.

# How Kleo ? 
Kleo enables lending without collateral by combining overfunding, distributed trust scoring, and verifiable repayment proofs:

1. Multi-Lender Overfunding

Instead of one lender taking all the risk, each loan is funded by several lenders who collectively contribute more than the borrower receives.
The extra amount becomes a risk buffer that protects lenders from default.

2. Borrower Trust Score

Borrowers are evaluated through a decentralized trust score built on repayment behavior, identity verification, and social signals.
Lenders only participate if the borrower meets their trust threshold.

3. Verifiable Repayment Flow

Every repayment is timestamped, cryptographically signed, and publicly visible.
Borrowers cannot fake payments, hide missed installments, or manipulate their history.

4. Deterministic Loss Distribution

If a default occurs, the buffer absorbs the loss first.
Any remaining loss is distributed proportionally among all lenders—mathematically predictable, transparent, and fair.


# Architecture
## Frontend
- NextJs
- Scaffold typink(polkaVM)
- Contratos en ink v6

## Smart Contracts
- Ink v6
- Hydration(will be implemented within the next 2 weeks)

## Backend 
- Golang
- Neo4j

# Workflow scheme
<img width="1050" height="3142" alt="image" src="https://github.com/user-attachments/assets/706e47d6-255c-4f13-88fe-228df2ec77ba" />

