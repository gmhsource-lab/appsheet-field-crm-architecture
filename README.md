📱 Enterprise Field CRM & ERP (Multi-Tenant Architecture)
A professional-grade mobile solution built on AppSheet Databases. This system is architected for high-performance field operations, featuring a secure multi-tenant data model that allows multiple independent organizations to operate within a single application instance.

🛡️ Cloud-Native Database Architecture
Unlike traditional spreadsheet-linked apps, this CRM utilizes AppSheet Databases for enhanced performance and data integrity.

Data Normalization: Structured to eliminate redundancy across Lead, Site, and Project tables.

Relational Integrity: Implemented via Ref (Reference) columns to ensure parent-child relationships between Customers and Site Reports.

High-Concurrency Support: Optimized for multiple field users syncing data simultaneously without row-locking issues.

🏢 Multi-Tenant Data Isolation
The architecture utilizes a centralized orgid (Organization ID) mapping system to securely partition data.

Secure Access: Users only interact with records associated with their specific orgid, preventing data "bleeding" between different companies.

Scalability: The system is built to scale horizontally, allowing new organizations to be onboarded without changes to the core codebase.

✨ Core Functionalities
Offline-First Data Capture: Engineered for remote site work where cellular service is unreliable; features full offline data sync capabilities.

Automated Document Engine: Integrated with Google Apps Script to trigger automated PDF generation (Quotes/Invoices) based on field data entries.

Operational Intelligence: Real-time dashboards providing management with visibility into project progress, labor burden, and profit margins.

🛠️ Data Schema Overview
Org IDs: The master gatekeeper table managing company-level access and permissions.

Project Sites: Tracks physical locations, GPS data, and site-specific safety logs.

Bill of Quantities (BOQ): Relational itemized costs linked directly to the document generation engine.

Companies & Clients: Separate tables to distinguish between service providers and end-customers.
