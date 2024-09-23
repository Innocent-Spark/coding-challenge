# Asset Management Compliance Review System

## Background
You are a programmer for an asset management firm. The compliance team has implemented an advanced model for flagging potentially non-compliant investment transactions on the secondary market system. These flagged transactions require manual review. This is just a toy app, to be used to learn more about your programming and technical design skills.

We don't care about building a super polished UI - but the challenge is to demonstrate the depth and breadth of your technical knowledge.

## Technical Requirements
- Backend: C# (.NET Core)
- Frontend: React (can be using NextJS)
- Please avoid using a framework for any CSS (i.e bootstrap, chakra. Styled Components, SCSS are fine
- Use an in-memory data structure for storage (no need for a database)

## Core Features

### 1. Transaction Display
Display a list of flagged transactions, ordered from newest to oldest. Each transaction should show:
- Transaction ID
- Date
- Buyer ID
- Seller ID
- Investment Type
- Amount
- Flagged Reason

The JSON representation needed to display this can be found in this repository as `transactions.json`

### 2. Action Buttons
Provide two action buttons for each transaction:
- "Approve": Marks the transaction as compliant
- "Reject": Marks the transaction as non-compliant

### 3. Status Update
- When either button is clicked, update the transaction's status in the backend.
- Once a transaction's status is updated, it should no longer be visible in the UI.

### 4. Persistence
- The status of each transaction should persist through page refreshes (F5).
- Approved or rejected transactions should not reappear after a refresh.

### 5. Real-time Updates
- The UI should reflect changes immediately after a transaction is approved or rejected, without requiring a manual refresh.

## UI Representation
The UI should look similar to this:

![image](https://github.com/user-attachments/assets/1f4ec97b-e9a4-4362-859a-e36cb721527d)

## Evaluation Criteria
- Code and testing quality
- Technical choices
- A runnable full-stack application

## Time Limit
Please don't spend more than 4 hours on this challenge.

## Note
If during your implementation you find that something could be designed in multiple different ways, implement the one which seems most reasonable to you. A short (one sentence) explanation of your choice would be appreciated.

