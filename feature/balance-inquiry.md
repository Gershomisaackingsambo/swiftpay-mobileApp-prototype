# Feature: Balance Inquiry

## Feature Description
This feature allows users to check their current account or wallet balance at any time through the app.

## Functional Goals
- Display the user’s current available balance
- Option to refresh balance
- Show balance after every transaction
- Display in preferred currency

## Business Value
Users need real-time access to their account balance to make financial decisions. This feature improves transparency and user confidence.

## User Story
As a user, I want to quickly check my balance so that I know how much money I currently have in my SwiftPay account.

## Acceptance Criteria
- ✅ Displays balance in local/preferred currency
- ✅ Balance updates after every transaction
- ✅ Refresh button available
- ✅ Balance only shown after login/verification

## Security Notes
- Require user to be logged in
- Hide balance by default (optional privacy mode)
- Encrypt balance data during transmission
