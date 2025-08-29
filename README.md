# Intelligent CRM Lead Ingestion and Opportunity Creation ERP System
## 🎯 Objective
To automate the end-to-end process of ingesting new leads from various sources, intelligently qualifying and enriching them, and creating both a lead and a corresponding opportunity in the ERPNext CRM. This process minimizes manual intervention, ensures data accuracy, and accelerates the sales pipeline.

## 🔁 Process Description
This automation leverages UiPath's intelligent capabilities to manage the entire lead-to-opportunity workflow. The process begins by monitoring a specified intake channel (e.g., an email inbox or a shared network folder) for new lead documents. Using UiPath's Document Understanding framework, it extracts key information such as name, email, company, and phone number from unstructured or semi-structured formats (like PDFs or scanned forms). The bot then performs an intelligent lead qualification check based on predefined business rules, such as company size or industry. For qualified leads, it uses an enrichment API to gather additional firmographic data. Finally, the bot logs into ERPNext via its API to create a new lead record and, if the lead meets the criteria, automatically creates a new sales opportunity associated with that lead. The entire process is logged and exceptions are handled for human-in-the-loop validation.

## 🧰 Tools
- UiPath Studio: The core RPA development environment.
- ERPNext API: The interface for creating leads and opportunities.
- CRM Source: An email inbox, shared folder, or web form where new leads are received.
- Third-Party Enrichment API: A web service (e.g., Clearbit) for lead data enrichment.

## 🗺️ Process Map
<img width="1648" height="204" alt="image" src="https://github.com/user-attachments/assets/639a7684-48cd-4855-98cc-a149bca769df" />

