# ServiceNow-Based Employee Laptop Request Application

An automated ServiceNow application built in an isolated scoped environment to streamline corporate employee laptop provisioning, managerial approval hierarchies, and inventory fulfillment tasks.

## Key Features & Highlights
- **Custom Scoped Table Architecture:** Normalized data schema (`x_2056547_projec_0_laptop_request`) with field validations, auto-numbered request records, and hardware spec choices.
- **Service Catalog Integration:** End-user facing Record Producer with dynamic category mapping and variable sets.
- **Automated Workflow Studio Flow:** Automated approval routing to reporting managers, conditional evaluation branches, and automated Catalog Task (`sc_task`) generation for IT teams upon approval.
- **Business Rule Governance:** Server-side scripting enforcing business policies (blocking duplicate requests within the same calendar year).
- **Role-Based Security & ACLs:** Granular CRUD access control separating requester submission permissions from managerial read-only review rights.
