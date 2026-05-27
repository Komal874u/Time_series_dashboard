📊 Project 1: Credit Card Financial & Customer Analytics (Power BI)
This project simulates a real-world corporate analytics scenario. It focuses on converting messy transactional database records into structured data pipelines to track a credit card portfolio worth $12M in Revenue and $45M in Transaction Volume.

🛠️ Data Engineering & ETL Pipeline (Power Query)
Before building any visual components, you performed rigorous data cleaning and shaping steps in Power Query:

Dynamic Attribute Creation: You wrote standard expressions to calculate absolute revenue bands using the formula:
$$\text{Revenue} = \text{Annual Fees} + \text{Total Transaction Amount} + \text{Interest Earned}$$
Data Structuring & Age Bucket Logic: To avoid cluttered visualizations, you used conditional logic to segment continuous customer numerical values into uniform bins:

Age Grouping: 20-30, 30-40, 40-50, 50-60, and 60+.

Income Grouping: Categorized based on salary bands into Low, Medium, and High.

Data Cleansing: Standardized state codes (NY, TX, CA, etc.), handled missing values in customer demographic attributes (such as Education level or Marital status), and structured uniform relational date lookups.
📈 Deep-Dive Report Metrics & Domain Insights
Report View A: Credit Card Transaction Performance
This view serves as an executive-level summary of financial operations:

Strategic High-Level KPIs: $12M total revenue, $7.84M interest accrued, $45M transaction value, and 12K active individual swipe actions.

Tier Performance Analysis: Blue Tier Credit Cards dominate the entire business portfolio, pulling in an incredible $11.2T scale in baseline data. This proves that standard entry-level products drive the operational volume compared to luxury tiers like Platinum ($0.7T) or Gold ($1.5T).

Consumer Spending Categories: Transaction tracking reveals that Bills ($3.4T) and Food ($2.9T) dominate expenditure profiles, while point-of-sale interaction heavily relies on physical Card Swiping ($9.0T) versus digital Online Channels ($1.0T).

Report View B: Customer Demographic Intelligence
This view profiles consumer personas to optimize target marketing:

Core Demographics: The prime spending demographic is the 30-40 age cohort, generating $16T in combined baseline revenue. From a gender perspective, male clients lead overall generation slightly at $88.7M versus female clients at $71.9M.

Socio-Economic Triggers: High-income, married individuals form the highest-value customer segments.

Geographical Vectors: Spatial tracking shows that New York (NY) and Texas (TX) are your top two geographic markets, with NY representing roughly 11.32% of overall consumer scale.

🏥 Project 2: Role-Based Healthcare Management Portal (Web Development)
A responsive, multi-tenant portal designed to streamline operational workflows within medical environments. It provides custom internal workspaces for administrative, clinical, and frontline staff.

💻 Tech Stack & Hosting Specs
Frontend Foundations: Pure semantic HTML5 elements alongside structured CSS3 custom layouts.

Architecture: Modular, page-driven routing setup (dashboard1.html, dashboard2.html, etc.) providing instant load times without modern framework overhead.

Live Link: Currently fully operational and deployed via your public portfolio page on GitHub Pages: https://komal874u.github.io/Hospital_managment_portal/
