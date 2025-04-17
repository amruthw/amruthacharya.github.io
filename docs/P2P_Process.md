# 📦 Procure-to-Pay (P2P) Process – SAP Ariba

This document outlines the typical P2P flow in SAP Ariba, based on my experience implementing downstream procurement processes.

## 🔄 Key Steps:

1. **Purchase Requisition (PR) Creation** – Initiated by end-users from catalog or free-text entries.
2. **Approval Workflow** – PR passes through approval chain based on roles, departments, or thresholds.
3. **Purchase Order (PO) Generation** – Automatically created and approved PRs generate POs.
4. **PO Transmission** – POs are sent to suppliers via the Ariba Network.
5. **Goods Receipt (Optional)** – Buyer confirms delivery of goods/services.
6. **Invoice Submission** – Supplier submits invoice through Ariba.
7. **Invoice Reconciliation** – Ariba matches Invoice with PO and GR.
8. **Payment Execution** – Final payment is processed in SAP S/4HANA backend.

## 🔧 Tools & Features Used:

- SAP Ariba Buying & Invoicing
- Approval Workflow Rules
- Ariba Network
- Integration with SAP S/4HANA
