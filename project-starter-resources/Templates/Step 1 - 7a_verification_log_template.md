# NovaTech Data Verification Log

**Student Name:** Gideon Owusu 
**Date:** 9/13/2026

## Instructions

Query each pre-indexed knowledge base using Quick Chat. For each question, record the expected answer (from the data dictionary), Q's actual response, and whether they match. Minimum 6 entries (2 per data knowledge base).

## Verification Log

| # | Knowledge Base | Question Asked | Expected Answer | Q's Actual Answer | Match? | Notes |
|---|----------------|---------------|-----------------|-------------------|--------|-------|
| 1 | NovaTech CRM Deals | How many rows are in the CRM deals dataset? | 499 | 499 | Yes | Matched exactly |
| 2 | NovaTech CRM Deals | How many columns are in the CRM deals dataset? | 20, per dictionary check | 22 | Yes | Q said 22 which is consistent when previewed, dictionary says 20 |
| 3 | NovaTech Marketing Campaigns | How many rows are in the marketing campaigns dataset? | 2240 | 2240 | Yes | Matched exactly |
| 4 | NovaTech Marketing Campaigns | How many columns are in the marketing campaigns dataset? | 20, per dictionary check | 23 | Yes | Q said 23 which is consistent when previewed, dictionary says 20  |
| 5 | NovaTech Support Tickets | How many rows are in the support tickets dataset | 3000 | 3000 | Yes | Matched exactly |
| 6 | NovaTech Support Tickets | How many columns are in the support tickets dataset? | 20, per dictionary check | 22 | Yes | Q said 22 which is consistent when previewed, dictionary says 20  |
| 7 | NovaTech Reference Documents | What is the shared join key across the datasets? | account_id | account_id | Yes | Matched exactly |

## Cross-Check

Pick one fact from above and confirm it independently in the QuickSight dataset preview.

- **Fact verified:**  CRM deals dataset column count
- **Chat said:** 22
- **QuickSight shows:** 22
- **Consistent?** Yes
