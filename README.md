# Lead-Gen-Automation-n8n
This n8n workflow automatically scrapes business leads from Google Maps using SerpAPI. It collects business data, visits websites, extracts emails, and stores the results in Google Sheets — creating a ready-to-use lead database for outreach and sales.

README
Overview

This workflow automates local business lead generation by extracting business listings from Google Maps using SerpAPI, enriching them with website data, extracting emails, and storing them in Google Sheets.
It is ideal for agencies, marketers, and freelancers looking to build targeted outreach lists.

⚙️ How It Works
1️⃣ Form Trigger
User submits search parameters such as:
Business type
Location
Keywords

2️⃣ Initialize Variables
Prepares search query and workflow variables.

3️⃣ SerpAPI Google Maps Search
Retrieves business listings from Google Maps.

4️⃣ Parse Results
Extracts:
Business Name
Address
Phone
Website
Rating
Reviews

5️⃣ Split Businesses
Processes each business individually.

6️⃣ Fetch Website
Visits the business website.

7️⃣ Extract Emails from HTML
Scrapes visible email addresses.

8️⃣ Append to Google Sheets
Stores enriched lead data.

📊 Output Data
Each lead includes:
Business Name
Address
Phone Number
Website URL
Email (if found)
Google Rating
Review Count

🧰 Requirements
Accounts & APIs

✅ SerpAPI account & API key
✅ Google Sheets integration
✅ n8n (cloud or self-hosted)

Recommended
VPS hosting for large scraping runs
Proxy support (if scaling)

🔧 Setup Instructions
Import workflow into n8n.
Add your SerpAPI API key.
Connect Google Sheets credentials.
Configure the form trigger fields.
Execute the workflow.

🎯 Use Cases

✔ Lead generation agencies
✔ Local SEO prospecting
✔ B2B outreach campaigns
✔ Drop servicing client acquisition
✔ Market research

⚠️ Notes & Best Practices
Respect website scraping policies.
Some websites may block scraping.
Email extraction depends on website availability.
Use delays to avoid rate limiting.

💰 Cost Considerations
SerpAPI: Pay-per-search pricing
n8n Cloud / VPS: hosting cost
OpenAI (optional enrichment): extra usage cost

🔮 Future Improvements
AI lead qualification
Contact page detection
LinkedIn extraction
CRM integration
Automated outreach
