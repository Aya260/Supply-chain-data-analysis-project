# Supply-chain-data-analysis-project
🌍 Global Health Supply Chain Analysis for HIV Commodities
This project involves a comprehensive data analysis of the Global Health Supply Chain focused on tracking procurement, delivery, and logistics performance of pharmaceutical and diagnostic products for HIV treatment across multiple countries.

📊 Objective
To identify inefficiencies and provide actionable recommendations in the global health supply chain by analyzing:

Cost overruns and their drivers

Delivery delays

Vendor performance

Product-specific bottlenecks

🧹 Data Cleaning & Preparation
Using Python, the raw dataset was cleaned and pre-processed with the following steps:

Handling Missing Values
Missing entries in shipment method, dosage, and line item insurance were imputed or flagged for further investigation.

Data Type Correction
Columns with object types were converted to appropriate types, such as datetime for shipment dates and numerical types for cost and quantity fields.

Export to CSV
Cleaned data was exported to a .csv file to enable easier exploratory data analysis (EDA) and dashboard creation.

🔍 Exploratory Data Analysis (EDA)
Performed using Python (pandas, seaborn, matplotlib):

Checked for duplicates and assessed data uniqueness.

Generated summary statistics.

Correlation heatmaps were created to explore relationships between key numerical variables.

📈 Visualization & Dashboard
Used Power BI to build an interactive dashboard covering:

Overview: General supply chain performance indicators

Shipping & Logistics: Shipping methods, durations, and costs

Countries: Country-specific performance and challenges

Products: Analysis by product type, batch, and urgency

🔑 Key Insights
Shipping Costs Vary by Country
Countries like Nigeria, Zambia, and Côte d'Ivoire incur higher freight costs due to logistical and vendor-related factors.

Air Freight is Fast but Costly
While faster, air freight is significantly more expensive and best reserved for urgent or sensitive commodities.

Supplier Performance Varies
Certain suppliers, e.g., Aspen Pharmacare, show consistent on-time delivery, while others frequently delay.

Insurance and Shipping Charges Vary Widely
Even for similar products, shipping and insurance costs fluctuate, emphasizing the need for better negotiation and benchmarking.

🎯 Recommendations
Optimize Freight Mode Selection: Use ocean freight for non-urgent goods to reduce costs.

Vendor Benchmarking: Prioritize reliable suppliers based on past performance metrics.

Negotiate Shipping Contracts: Standardize and benchmark insurance and shipping charges across vendors.

Targeted Interventions: Focus efforts on countries and products with frequent cost overruns or delays.
🔧 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

Power BI

Excel/CSV

Jupyter Notebooks

🤝 Contributions
Feel free to fork this repository or raise issues for improvements or collaboration opportunities!
