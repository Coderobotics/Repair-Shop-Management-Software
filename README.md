# Repair Shop Management Software

Repair Pro is repair and service shop management software for auto workshops, phone repair shops, electronics repair centers and other service businesses. It covers repair orders, appointments, estimates that customers approve online, digital inspections with photos, inventory with FIFO costing, invoicing and payments in one system. Customers get their own portal to follow repairs, approve estimates, pay invoices and book appointments. The shop gets role-based access for admins, receptionists, technicians and accountants, plus a CRM for leads, five business reports, a full audit log, push notifications and an app that installs on phones and desktops. Repair Pro is built with Laravel 12, Livewire 3 and Tailwind CSS, and a guided web installer handles the setup.

<img src="https://www.coderobotics.com/frontend/assets/icon/repair-shop-php-mysql-script.jpg">

Repair Pro runs a repair shop from the first customer contact to the final payment. Customers book an appointment, you inspect the item and send an estimate they can approve online, and technicians see only their own jobs. When the job is done, parts are taken out of stock at their real cost and an invoice goes to the customer.

A switch in the settings changes the wording across the app to match your trade: vehicles, phones, devices or your own custom terms.

Who It's For
 
Auto repair workshops: vehicles with plates, VINs and odometer readings, a 30-point vehicle inspection, and parts suppliers
Phone repair shops
Electronics repair centers
Other service businesses: you set your own terms for the items you service
Key Features
 
Repair Orders and Workflow
 
Repair orders move through a status workflow you can track
Assign jobs to technicians, who see only their own work and no prices
Start a job from an appointment or from an inspection
Estimates with Remote Approval
 
Send an estimate and the customer approves or declines it online
Items flagged in an inspection become estimate lines in one click
Staff get a push notification when a customer responds
Digital Inspections
 
Inspection templates for each shop type
Rate each item Good, Monitor or Needs Repair, with notes and photos
Share the report through a public link and see when the customer first opens it
Appointments
 
Book appointments at the front desk
Booking requests from the customer portal arrive as pending appointments and alert the front desk right away
Invoices and Payments
 
Download invoices as PDF
Payments can't be edited after they're saved. Corrections are made as reversal entries, which keeps the audit trail clean
Track what each customer owes
Inventory Management
 
Multiple warehouses and storage locations
Suppliers, and purchase orders that go from Draft to Review to Confirmed
FIFO stock batches, so parts are costed at what you actually paid
Parts come out of stock automatically when a job is completed. They go back if the job is reopened and are never deducted twice
Stock transfers, kits split into parts with the cost shared out, low-stock alerts and a full stock ledger
Finance
 
Debt aging for customers and suppliers
Supplier payments, which can also be reversed
Cash book with automatic entries, manual income and expenses, opening and closing balances per account, and a daily summary
CRM and Leads
 
Sales pipeline with an activity log and follow-ups
Turn a lead into a customer in one click
Reports
 
Five reports, each filtered by Today, 7 Days, Month, Quarter, Year or a custom range:

Revenue and profit
Inventory
Debt and cash flow
Operations
Customers and assets
Customer Portal
 
Customers have their own secure login, kept completely separate from staff accounts. In the portal they can:

Follow each repair and see what it costs
Approve or decline estimates
View and download invoices and see what they owe
Open inspection reports
Request appointments
Change their password
Staff turn portal access on or off from the customer's page. When access is switched off, the customer is signed out on their next click.

More Features
 
Installable app (PWA): add Repair Pro to a phone or desktop home screen, with an offline page
Push notifications: alerts for new jobs, completed jobs and estimate responses
Audit log: see every change with before and after values
Email settings: set up SMTP from the admin panel and send a test email
Dark mode
Translation-ready: all interface text is in language files, so you can change the wording or translate it
7-step web installer: a guided setup that locks itself when it's finished

Technology
 
Framework	Laravel 12
Frontend	Livewire 3, Alpine.js, Tailwind CSS v4
Database	MySQL / MariaDB
Permissions	Spatie Permission
Auditing	Laravel Auditing
PDF	DomPDF
The code follows a layered design (Service and Repository pattern), which makes it easy to maintain and extend.

Requirements
 
PHP 8.2 or later, with Composer
MySQL or MariaDB
Node.js, to build the frontend files (or upload the ready-built files)
HTTPS, for push notifications in production

Installation
 
Upload the files, point the web root at the public/ folder and open your domain. The web installer starts automatically and walks you through the setup.

More detaisl and download link:
https://www.coderobotics.com/product/repair-shop-management-software
