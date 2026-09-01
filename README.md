# Nexus Budget

Nexus Budget is a lightweight, mobile-first personal budgeting app built as a single-page HTML application.

## Features

- Week, Month, and Year views
- Salary-month cycles based on payday
  - 25th
  - Month end
  - Custom payday
- Monthly budgets vs actual spending
- Weekly allocations based on **Actual Remaining**
- Optional exclusion of weeks from an allocation cycle
- Transaction tracking with paid/unpaid status
- Local browser storage with optional Supabase cloud sync
- JSON import/export and CSV transaction export
- HTML and PDF financial reports
- Dark and light themes
- Responsive mobile-first interface

## Salary Months

Months follow your configured salary cycle rather than calendar dates.

For example, with a payday on the **25th**:

**September → 25 August to 25 September**

The same logic applies to month-end and custom payday settings.

## Data

Nexus Budget stores data locally in your browser by default. Supabase authentication and cloud synchronization can optionally be enabled for cross-device access.

## Current Release

**Version:** 1.3.4  
**Build:** 2026.09.01.1
