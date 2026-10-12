---
name: moneyhub-sync-and-read-transactions
description: Refresh a user's bank connection and read their accounts and enriched transactions from the Moneyhub Data API.
api: moneyhub:moneyhub-data-api
operations:
- postSyncByConnectionId
- getAccounts
- getAccountsByAccountIdBalances
- getTransactions
generated: '2026-10-12'
method: generated
---
1. Obtain a user-scoped access token from identity.moneyhub.co.uk (OIDC) with the accounts and transactions read scopes.
2. Call `postSyncByConnectionId` to refresh the connection. A connection can be synced at most once every 5 seconds; on 429 honour `Retry-After`.
3. Call `getAccounts`, then `getAccountsByAccountIdBalances` for each account of interest.
4. Call `getTransactions` (paged; default limit applies) to read enriched, categorised transactions.
5. The Data API is limited to 1000 requests per minute per API client (docs/rate-limit).
