# phonepe-digital-payments-case-study
This case study involves analysing transaction data from the financial application phone pe along with demography data across various states and districts in India. 
This project involves a deep-dive analysis of a comprehensive fintech dataset to uncover patterns in digital transactions, user demographics, and app usage across various states and districts. By merging transaction data with demographic information, the study identifies key drivers of digital adoption and provides actionable business insights.

Key Analysis Modules:
1. Exploratory Data Analysis (EDA)
Transaction Trends: Analyzed year-over-year growth in transaction volumes and amounts, identifying the top and bottom 5 performing states.

Market Share & Behavior: Identified the most frequent transaction types (e.g., Peer-to-peer, Merchant payments) and the dominant device brands used by registered users in each region.

Geographic Deep-Dive: Mapped population hotspots by identifying the most populous districts and calculated the Average Transaction Value (ATV) per state to understand regional spending power.

App Usage Patterns: Tracked app engagement (opens) over time to identify seasonal trends and growth cycles.

2. Data Quality & Integrity
Consistency Audits: Performed cross-level validation by aggregating district-level data (transactions, users, amounts) and comparing them against state-level records to ensure data integrity.

Data Cleaning: Created unique mapping files for districts and codes to streamline future joins and exports.

3. Advanced Data Merging & Correlation
Digital Penetration: Merged demographic datasets to calculate the User-to-Population ratio, highlighting states with high market saturation vs. those with untapped potential.

Economic Correlation: Analyzed the relationship between population density and transaction volume to determine if urbanization is a primary driver of digital payments.

Device Brand Analysis: Calculated the ratio of specific device brands per state to help tailor platform-specific marketing strategies.

4. Visual Insights
Trend Analysis: Developed line plots for temporal trends and pie charts for transaction type distributions.

Demographic Mapping: Utilized bar charts and column charts to visualize population density and user ratios across different districts.

Business Insights & Recommendations:
High-Growth Hubs: Identified states with low ATV but high volume as ideal targets for small-ticket merchant expansion.

Device Strategy: Found correlations between specific device brands and user activity, suggesting targeted app optimizations for dominant hardware.

Expansion Opportunities: Pinpointed districts with high population density but low user-to-population ratios as "Cold Spots" for targeted user acquisition campaigns.

Tech Stack:
Language: Python

Libraries: Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization)

Data Handling: CSV Exporting, Merging, and Multi-level Aggregation
