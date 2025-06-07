# Feature: Multi-Currency Support

## Feature Description
This feature allows users to hold, send, and receive money in multiple currencies within their SwiftPay wallet. It includes real-time currency conversion and display.

## Functional Goals
- Users can select their preferred currency
- Support conversion between currencies (e.g., SLL, USD, GBP, EUR)
- Show equivalent values during transactions
- Allow transfers in multiple currencies
- Sync with exchange rates API (future integration)

## Business Value
This enables SwiftPay to operate globally and serve customers who use different currencies, making the app more flexible and competitive.

## User Story
As a user, I want to use different currencies in my wallet so I can transact internationally without confusion or delays.

## Acceptance Criteria
- ✅ Currency dropdown for user selection
- ✅ Automatic exchange rate updates
- ✅ Transaction history reflects currency used
- ✅ Convert currency before or during a transaction

## Security Notes
- Currency conversions should be verified for accuracy
- Exchange rates should come from secure APIs
- Avoid storing outdated rates — refresh regularly
