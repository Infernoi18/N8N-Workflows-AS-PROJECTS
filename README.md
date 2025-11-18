📌 N8N Automation Projects

This repository contains a collection of N8N-based automation workflows built to streamline lead generation, outreach, and data extraction processes. These workflows were developed during an internship to help startups automate customer onboarding and outbound campaigns using N8N, Google APIs, OpenAI, and other integrations.

🔧 Tech Stack & Integrations
Category	Tools / APIs Used
Automation	N8N, Webhooks, Cron, Function nodes
APIs	Gmail API, Google Places API (Advanced), Google Search/Maps data, OpenAI API
Databases / Storage	Google Sheets, Excel, Notion (optional)
Communication	Email Campaigns, Lead Outreach
Output Format	CSV, JSON, Sheet updates, Email triggers
📂 Projects Overview
1) Industry Level Campaign (Using Gmail API)-
Automates outreach campaigns using leads stored in Sheets.

Features
1. Detects new leads from Excel/Google Sheets
2. Checks status column and sends emails only if unsent
3. Uses Gmail API inside N8N to fully automate campaign sending
4. Workflow File: Industry Level Campaign.json

2) Industry Level Lead Generation-
Scrapes industry-specific business data using Google and AI enrichment.

Features
1. Uses Google Places API (Advanced) to fetch business details
2. Uses OpenAI API for lead enrichment/qualification
3. Ideal for targeted B2B outreach
4. Workflow File: Industry Level Lead Generation.json

3) Cold Email System for Startups-
Automates email sending for newly acquired leads.

Features
1. Reads scraped leads stored in Google Sheets
2. Sends customized cold emails using Gmail API
3. Supports campaign batching and follow-up sequences
4. Workflow File: Cold Email System for Startups.json
5. GitHub: link pending

4) Lead Scraper Using Google Maps-
A cost-efficient scraping system that does not rely on Google Places API usage limits.

Features-
1. Scrapes lead data from Google Maps search results
2. Operates without high API cost or quotas
3. Supports manual and automated scraping modes
4. Workflow File: Lead Scraper Using Google Maps.json

5) Phone Number Scraper Using Google Maps-
Extracts phone numbers of businesses based on category & region.

Features
1. Queries Google Maps for targeted businesses
2. Gathers available phone numbers and relevant contact details
3. Useful for small business outbound sales and telemarketing
4. Workflow File: Phone Number Scraper Using Google Maps.json


🧪 Example Use Cases
These workflows can be adapted for:
✔ Startup lead acquisition
✔ B2B prospecting & outbound sales
✔ Email & newsletter automation
✔ Local business market research
✔ Automating CRM data enrichment

📜 License
This project is licensed for personal and internship/learning usage.
For commercial use, API terms (Google, OpenAI, Gmail) must be respected.

🙋 Author
Kumar Ayush
🔗 LinkedIn: https://linkedin.com/in/Kumar-Ayush-18-Infernoi
🐙 GitHub: https://github.com/Infernoi18
