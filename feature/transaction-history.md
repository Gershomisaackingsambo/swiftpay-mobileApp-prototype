# Feature: Transaction History

## Feature Description
Allows users to view a detailed list of their past transactions including date, amount, transaction type, and recipient/sender.

## Functional Goals
- Show list of past transactions in reverse chronological order
- Filter transactions by date, type (sent/received), or status
- Allow users to tap to see transaction details
- Display running balance after each transaction

## Business Value
Transaction history builds trust and transparency for the user. It is critical for tracking financial activity and resolving disputes.

## User Story
As a user, I want to see my transaction history so that I can track my spending and verify past payments.

## Acceptance Criteria
- ✅ Shows at least 30 recent transactions by default
- ✅ Filters work correctly (date/type/status)
- ✅ Each transaction shows amount, type, date, recipient/sender, and status
- ✅ Loads fast and supports mobile scrolling

## Security Notes
- User must be logged in to view history
- All data retrieved via secure API endpoints
- Pagination or load-more feature to avoid data overload
