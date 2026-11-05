# Postman Collection

This repository contains exported Postman collections for various integration and API workflows used in the project. Each `.postman_collection.json` file can be imported directly into Postman.

## Available Collections

| Collection | File | Description |
|---|---|---|
| **Create Invoice Web** | `Create Invoice Web.postman_collection.json` | Invoice creation flow for web-based transaction processing. |
| **FDS Sefis** | `FDS Sefis.postman_collection.json` | Fraud detection and Sefis integration endpoints. |
| **Lenjer Rest** | `Lenjer-Rest.postman_collection.json` | REST API collection for Lenjer services. |
| **Merchant Loan** | `[Merchant Loan].postman_collection.json` | Merchant loan APIs for loan calculation and inquiry flows. |
| **Open API Disbursement** | `open_api_disbursement_collection.json` | Open API disbursement workflow and callback handling. |
| **PPOB Open API** | `[PPOB] Open API.postman_collection.json` | PPOB Open API request collection. |
| **QRIS Alto Issuer** | `[QRIS] Alto Issuer.postman_collection.json` | QRIS Alto Issuer integration. |
| **QRIS CPM** | `[QRIS] CPM.postman_collection.json` | QRIS consumer-presented mode flows. |
| **QRIS Cross Border** | `[QRIS] Cross Border.postman_collection.json` | QRIS cross-border payment scenarios. |
| **QRIS MPM** | `[QRIS] MPM.postman_collection.json` | QRIS merchant-presented mode flows. |
| **QRIS Tap** | `qris tap.postman_collection.json` | QRIS tap payment integration collection. |
| **Toko Cache** | `Toko-Cache.postman_collection.json` | Toko cache-related API operations. |
| **Toko Kare** | `Toko-Kare.postman_collection.json` | Toko Kare integration endpoints. |
| **Toko Publish** | `Toko-Publish.postman_collection.json` | Toko publish and content-related API flows. |
| **Toserba** | `Toserba.postman_collection.json` | Toserba business process collection. |

## How to Use

1. Clone or download this repository.
2. Open Postman.
3. Click **Import** in the top-left corner.
4. Select the relevant `.json` file from the repository root or upload it from your local folder.
5. The collection will appear in your Postman sidebar and can be used immediately.

> Tip: Import only the collection you need for the feature or integration you are working on.

## Repository Notes

- All exported files are stored directly in the repository root.
- File names are kept aligned with the original Postman export names for easier identification.
- If the collection requires a variable environment, import the matching environment configuration alongside it in Postman.