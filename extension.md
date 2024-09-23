# Ignore this part of the challenge

## Advanced Feature - Transaction Network Analysis

Implement a recursive check for linked transactions when a transaction is rejected:

1. Identify all transactions involving the buyer or seller of the rejected transaction.
2. Recursively check these linked transactions up to a depth of 3 levels.
3. Flag all these linked transactions for review, marking them with a "Linked to Rejected Transaction" reason.

Example:
- If Transaction A (Buyer: John, Seller: Alice) is rejected
- Check all other transactions involving John or Alice
- For each of those transactions, check transactions involving their counterparties
- Continue this process one more level deep

Update the UI to:
- Display a visual indicator for transactions flagged due to links with rejected transactions
- Provide a way to view the chain of linked transactions
