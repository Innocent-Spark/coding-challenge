# Ignore this part of the challenge

## Advanced Feature - Transaction Network Analysis

Implement a check for linked transactions when a transaction is rejected:

1. Identify all transactions involving the buyer or seller of the rejected transaction.
2. Check these linked transactions up to a depth of 3 levels.
3. Flag all these linked transactions for review, marking them with a "Linked to Rejected Transaction" reason.

Example:
- If Transaction T001 (Buyer: JOHN001, Seller: ALICE002) is rejected
- Check all other transactions involving John or Alice
- For each of those transactions, check transactions involving their counterparties
- Continue this process one more level deep

## CSS skills: 

Implement this layout in CSS:

![image](https://github.com/user-attachments/assets/57d2593e-7103-4089-9235-ff2948599d2b)


