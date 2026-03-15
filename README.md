# Accounts-Payable-Management-System
End-to-End Accounts Payable Management System built in Excel covering invoice processing, 3-way matching, duplicate payment detection, supplier reconciliation, and AP dashboard reporting.

Project Overview

This project simulates an end-to-end Accounts Payable (AP) process for managing supplier invoices, ensuring accurate payment processing, and monitoring operational KPIs.

The system processes 200+ supplier invoices across multiple vendors and sites, performing validation checks such as 3-way matching (PO-GRN-Invoice), duplicate payment detection, supplier reconciliation, and turnaround time monitoring.

Key Features
Invoice Processing

Process supplier invoices and credit notes

Validate invoice details before payment approval

3-Way Matching

Ensures consistency between:

Purchase Order (PO)

Goods Receipt Note (GRN)

Supplier Invoice

Duplicate Invoice Detection

Implemented using Excel COUNTIFS logic to detect duplicate:

Vendor

Invoice number

Amount

This prevented 10 duplicate payments.

Supplier Reconciliation

Reconciled vendor statements with AP records to identify:

missing invoices

duplicate payments

outstanding balances

KPI & MIS Reporting

Dashboard tracks:

On-time payment %

Turnaround Time (TAT)

Invoice processing status

Vendor-wise invoice distribution

Tools Used

Microsoft Excel

Pivot Tables

VLOOKUP

COUNTIFS

Conditional Formatti
