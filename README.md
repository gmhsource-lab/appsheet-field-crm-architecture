### 🛡️ Cloud-Native Database Architecture
Unlike traditional spreadsheet-linked apps, this CRM utilizes **AppSheet Databases** for enhanced performance and data integrity.

- **Data Normalization:** Structured to eliminate redundancy across Lead, Site, and Project tables.
- **Relational Integrity:** Implemented via Ref (Reference) columns to ensure parent-child relationships between Customers and Site Reports.
- **High-Concurrency Support:** Optimized for multiple field users syncing data simultaneously without row-locking issues.
