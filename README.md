# corporate-vendor-contract-system
# Corporate Vendor and Contract Management System

A full-stack, role-based web application to manage vendors, contracts, purchase orders, budgets, reports, and performance evaluations across departments.

## 🔧 Technologies Used

- **Frontend**: HTML5, CSS, Bootstrap 5.3.0
- **Backend**: Node.js, Express.js
- **Database**: MySQL (DDL, Triggers, Stored Procedures)
- **Visualization**: D3.js
- **Security**: JWT-based Authentication, Role-Based Access Control

## 📁 Project Structure

corporate-vendor-contract-system/ ├── frontend/ → All HTML interface pages ├── backend/ → Node.js backend files ├── database/ → SQL scripts (DDL, triggers, procedures) ├── docs/ → Reports (PDF, DOCX)├── README.md

## 📌 Features

- Vendor Registration & Management
- Contract Lifecycle Tracking with Renewal Notifications
- Purchase Order Creation and Approval
- Budget Allocation and Expense Monitoring
- User Roles: Admin, Procurement Manager, Department Head
- Audit Logs, Task Assignment, System Settings
- Reports and Visual Charts with D3.js
- Trigger-based notifications and budget enforcement

## 🗃️ SQL Highlights

- Fully normalized schema
- Triggers: contract alerts, budget checks, log actions
- Stored Procedures: vendor registration, renewals, evaluations
- Constraints: Primary Keys, Foreign Keys, Checks

## 🚀 Setup Instructions

1. Import the SQL scripts from `database/` folder into MySQL.
2. Start backend with:
3. Open `login.html` to begin using the system.

## 📄 License

MIT License — see `LICENSE` for details.
