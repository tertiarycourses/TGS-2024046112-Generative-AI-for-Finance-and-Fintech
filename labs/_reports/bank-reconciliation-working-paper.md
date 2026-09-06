# Northstar Finance — Bank Reconciliation Working Paper

**Document ID:** RPT-FIN-003  
**Reporting period:** FY2026 H1 (January to June 2026)  
**Data as at:** 30 June 2026  
**Owner:** Treasury Analyst  
**Classification:** Internal  
**Currency:** Singapore Dollars (SGD)

> Synthetic data created for training (TGS-2026065050). Not real financial results.

## Summary

The June 2026 bank statement contains **17** lines: total credits SGD 4,120,232.29 and total debits SGD 2,631.68.

Matching rules from the Month-End Close Calendar and Controls policy: an exact match agrees on amount and reference; a tolerance match differs by SGD 50 or less; a reference-only match agrees on amount but the bank narrative lost the invoice identifier; anything else is an exception.

## Bank statement lines

| Bank ref | Value date | Description | Credit | Debit | Invoice ref | Suggested classification |
|---|---|---|---|---|---|---|
| BNK-2026-00001 | 2026-06-30 | RCPT Sydney Freight Co | SGD 719,003.82 | SGD 0.00 | INV-2026-0004 | Exact match |
| BNK-2026-00002 | 2026-06-30 | RCPT Tampines Medical G | SGD 120,618.60 | SGD 0.00 | INV-2026-0014 | Exact match |
| BNK-2026-00003 | 2026-06-30 | RCPT Victoria Payments  | SGD 612,252.14 | SGD 0.00 | INV-2026-0019 | Exact match |
| BNK-2026-00004 | 2026-06-30 | RCPT Marina Bay Logisti | SGD 270,735.55 | SGD 0.00 | (none) | Reference-only match — needs reviewer confirmation |
| BNK-2026-00005 | 2026-06-30 | RCPT Victoria Payments  | SGD 289,901.12 | SGD 0.00 | INV-2026-0023 | Exact match |
| BNK-2026-00006 | 2026-06-30 | RCPT Tampines Medical G | SGD 571,736.47 | SGD 0.00 | INV-2026-0024 | Tolerance match — note and clear with reviewer |
| BNK-2026-00007 | 2026-06-30 | RCPT Orchard Lifestyle  | SGD 355,535.81 | SGD 0.00 | INV-2026-0026 | Exact match |
| BNK-2026-00008 | 2026-06-30 | RCPT Victoria Payments  | SGD 361,321.14 | SGD 0.00 | INV-2026-0027 | Exact match |
| BNK-2026-00009 | 2026-06-30 | RCPT Melaka Shipping | SGD 166,254.45 | SGD 0.00 | INV-2026-0030 | Exact match |
| BNK-2026-00010 | 2026-06-30 | RCPT Harbourfront Retai | SGD 317,088.77 | SGD 0.00 | INV-2026-0032 | Exact match |
| BNK-2026-00011 | 2026-06-30 | RCPT Victoria Payments  | SGD 321,048.76 | SGD 0.00 | (none) | Reference-only match — needs reviewer confirmation |
| BNK-2026-00012 | 2026-06-20 | BANK CHARGES | SGD 0.00 | SGD 938.82 | (none) | Bank-only item — investigate and explain |
| BNK-2026-00013 | 2026-06-28 | FX ADJUSTMENT | SGD 0.00 | SGD 271.42 | (none) | Bank-only item — investigate and explain |
| BNK-2026-00014 | 2026-06-06 | RETURNED PAYMENT | SGD 0.00 | SGD 1,421.44 | (none) | Bank-only item — investigate and explain |
| BNK-2026-00015 | 2026-06-29 | INTEREST CREDIT | SGD 2,198.68 | SGD 0.00 | (none) | Bank-only item — investigate and explain |
| BNK-2026-00016 | 2026-06-27 | UNIDENTIFIED RECEIPT | SGD 5,351.44 | SGD 0.00 | (none) | Bank-only item — investigate and explain |
| BNK-2026-00017 | 2026-06-27 | MERCHANT SETTLEMENT | SGD 7,185.54 | SGD 0.00 | (none) | Bank-only item — investigate and explain |

Unreconciled items above SGD 10,000 or older than 60 days are escalated to the Financial Controller. No AI agent may prepare, approve or post a journal entry; every reconciliation requires a named preparer and an independent reviewer.
