# Company Sales Manager — Development Plan

## Goal
Build an internal Django application for managing electrical-appliance and mobile/technology sales, inventory, customers, installments, invoices, and management reporting.

## Architecture
- Django + Django Templates
- Tailwind CSS for the interface
- SQLite + Django ORM for initial deployment
- Django Admin for administration
- Responsive UI for desktop and mobile
- Dockerized for deployment to Coolify
- Resend for production email notifications
- Terminal email backend during development

## Core modules
1. Dashboard
2. Products and categories
3. Inventory and stock movements
4. Customers
5. Sales and invoices
6. Installment contracts and payment tracking
7. Employees and permissions
8. Reports
9. Company settings

## Business rules
- A completed sale reduces available inventory.
- Installment sales record total price, down payment, remaining balance, schedule, and payments.
- Payments reduce the outstanding balance and are auditable.
- Stock changes are recorded as movements.
- Financial calculations use Decimal, never floating point.
- The application is internal to the company.
- Email notifications are directed only to the company head.

## Initial milestone
Bootstrap the Django project, create the core apps and models, configure Tailwind-friendly templates, authentication, admin, SQLite, tests, Docker, environment configuration, and a basic dashboard.

## Later milestones
- Complete sales workflow
- Complete installment workflow
- Inventory reports and low-stock alerts
- Printable invoices and receipts
- Mobile UX refinement
- Email notifications through Resend
- Production hardening and Coolify deployment
