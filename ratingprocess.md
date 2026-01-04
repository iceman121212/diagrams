flowchart LR
  A[1) Issuer requests rating\nStakeholder: Issuer] --> 
  B[2) Kick off commercial engagement\nOwner: Commercial / Relationship Team] --> 
  C[3) Analytical engagement to understand\nbusiness + financial profile\nOwner: Analytical Team] --> 
  D[4) Internal analysis + draft + rating committee\nOwner: Analytical Team + Committee] --> 
  E[5) Issuer review for factual errors /\nconfidential info\nOwner: Analytical Team + Issuer] --> 
  F[6) Publish credit opinion/article\nOwner: Analytical Team / Publishing Ops] --> 
  G[7) Ongoing surveillance + updates\nOwner: Analytical Team]

  %% Optional annotations of key info flows
  Issuer[(Issuer)] -.->|Engagement terms, fees, scope| B
  Issuer -.->|Financials, forecasts, KPIs, strategy, events| C
  C -.->|Clarifications / follow-ups| Issuer
  D -.->|Draft rationale, key drivers, rating/outlook| D
  E -.->|Factual corrections + confidentiality flags\n(not negotiation)| D
  F -.->|Published opinion| Investors[(Investors / Market)]
  G -.->|Periodic updates + event-driven outreach| Issuer
