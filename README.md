# Summary
Delegation Dynamics for Decentralised Lending 

## Concepts
- Credit Delegration through RANDAOs
- Credit Delegattion through Quadratic DAOs

## Workflow
- Owner deposits collateral in Aave via its LendingPool
- Owner uses the data provider contract to retrieve the associated DebtToken for the borrower's desired asset to borrow
- Owner interacts with the DebtToken contract to approve the borrower to take out a given amount of credit on the asset
- Borrower borrows in Aave via its LendingPool increasing the Owner's totalDebtETH
- Eventually, Borrower repays loan, decreasing the Owner's totalDebtETH
- Eventually, Owner withdraws collateral from Aave
