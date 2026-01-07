# Open Doors SACCO Management System (Documentation)

## Overview
Open Doors SACCO Management System is a web-based application designed to automate SACCO operations including member management, deposits, loans, repayments, receipts, and staff workflows.

This repository only contains the documentation for the project.  
 **No source code is included** to protect security and intellectual property.

---

##  Key Modules

- **Member Portal**
  - Member login and profile access
  - Deposits and withdrawals
  - Loan application and loan tracking
  - Transaction history and receipts

- **Staff Dashboard**
  - Member registration and account management
  - Role-based access (Admin / Credit / Member Services)
  - Loan processing workflows
  - Transaction tracking and receipts management
  - Reporting and dashboard summaries

---

## Security & Access Control
- JWT-based authentication concept
- Role-based access controls for staff operations
- Validation and sanitization for sensitive inputs
- Secure handling of payment references and transaction status

---

##  Payment & Messaging Integrations (Sandbox)
- **MPESA Daraja API (STK Push)** for member payments and transaction confirmation
- **Africa’s Talking SMS (OTP verification)** for login/verification flows (sandbox environment)

---

##  Technologies Used (Implementation)
- Node.js + Express (Backend)
- MySQL (Database)
- HTML, Tailwind CSS, JavaScript (Frontend)
- MPESA Daraja API (Payments)
- Africa’s Talking SMS API (OTP)

---

## Screenshots
See the /screenshots folder for system UI images.

---

##  Documentation
- `/docs/system-overview.md` – how the system works
- `/docs/features.md` – detailed features list
- `/docs/architecture.md` – architecture and data flow
- `/docs/api-summary.md` – API endpoints overview (high-level)
- `/database/schema-overview.md` – database design summary

---

##  Note
For security and intellectual property reasons, the full source code is not publicly available.

