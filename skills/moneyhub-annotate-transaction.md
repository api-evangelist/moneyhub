---
name: moneyhub-annotate-transaction
description: Split a transaction or attach a file to it in the Moneyhub Data API.
api: moneyhub:moneyhub-data-api
operations:
- getTransactionsByTransactionId
- postTransactionsByTransactionIdSplits
- postTransactionsByTransactionIdFiles
generated: '2026-10-12'
method: generated
---
1. Read the transaction with `getTransactionsByTransactionId`.
2. Create splits with `postTransactionsByTransactionIdSplits` (split amounts must sum to the transaction amount), or attach a receipt with `postTransactionsByTransactionIdFiles`.
3. Splits can be removed with `deleteTransactionsByTransactionIdSplits` and files with `deleteTransactionsByTransactionIdFilesByFileId`.
