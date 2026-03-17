# Postman Collection

This repository stores Postman collection integrations exported from Postman. Each collection covers a specific feature and can be imported directly into Postman.

## Available Collections

| Collection | File | Description |
|---|---|---|
| **FDS Sefis** | `Postman Collections/fds_sefiss_collection.json` | Fraud Detection System (FDS) & Sefis — includes endpoints for fraud analysis, transaction validation, merchant upload, and merchant registration. |
| **Merchant Loan** | `Postman Collections/merchant_loan.json` | Merchant Loan APIs — covers loan calculation (manual & automatic), loan detail retrieval, loan history, and transaction data. |
| **OpenApi Disbursement** | `Postman Collections/open_api_disbursement_collection.json` | Netzme OpenApi Disbursement — covers authentication, single and bulk disbursement, internal disbursement, callback handling, disbursement detail and reporting, topup management, account inquiry, and balance retrieval. |
| **QRIS CPM** | `Postman Collections/qris_cpm_collection.json` | QRIS Consumer Presented Mode (CPM) — includes QR generation, payment inquiry, payment processing, refund/reversal handling, and settlement for On-Us and Off-Us scenarios. |
| **QRIS MPM** | `Postman Collections/qris_mpm_collection.json` | QRIS Merchant Presented Mode (MPM) — includes authentication, invoice creation, payment processing, refund and reimbursement, settlement, utilities (health check, transaction status, QRIS token generation), and acquirer integrations. |

## How to Use

1. **Clone or download** this repository.
2. Open **Postman**.
3. Click **Import** (top-left corner).
4. Drag and drop the desired `.json` file from the `Postman Collections` folder, or click **Upload Files** and select it.
5. The collection will appear in your Postman sidebar, ready to use.

> **Tip:** You only need to import the collection for the feature you are working on.
