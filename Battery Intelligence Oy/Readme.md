**🔋 Battery Health \& Fleet Optimization Dashboard**

**Inspired by Battery Intelligence Oy (Bamomas)**

**This project analyzes industrial battery health and performance, transforming raw IoT data into actionable business insights. It demonstrates a full data analysis workflow, from initial data cleaning to final dashboard creation, using a simulated dataset.**

**🎯 Objectives**

**Clean and Process Data: Use Excel for initial data cleaning and Python (Pandas) for more advanced data manipulation and feature engineering.**

**Build KPIs: Create key performance indicators (KPIs) to measure battery health, track degradation, and detect anomalies.**

**Create a Dashboard: Develop an interactive dashboard in Power BI to visualize insights and support data-driven decisions.**

**Provide Insights: Offer clear recommendations on how to reduce costs, optimize maintenance schedules, and improve fleet sustainability.**

**🗂️ Dataset**

**The dataset is a simulated collection of readings from a fleet of industrial batteries. It includes the following columns:**

**battery\_id: Unique identifier for each battery.**

**date: Timestamp of the reading.**

**voltage (V): Voltage output.**

**current (A): Current draw.**

**temperature (°C): Operating temperature.**

**cycles: Number of charge/discharge cycles.**

**capacity (Ah): Current battery capacity.**

**rated\_capacity (Ah): The original design capacity of the battery.**

**health\_percent: Calculated percentage of remaining battery health.**

**region: The geographical location of the battery in the fleet.**

**🛠️ Tools \& Technologies**

**Excel: For initial data review and basic cleaning.**

**Python (Pandas, Matplotlib): For advanced data processing, analysis, and visualization.**

**Power BI: For building the interactive and insightful dashboard.**

**GitHub: For project version control and portfolio showcase.**

**📊 Dashboard Features**

**KPIs: Average Battery Health, Number of Critical Batteries, and Predicted Failures.**

**Visuals: Trends showing battery health over time, the impact of temperature on degradation, and region-specific fleet performance.**

**Anomaly Detection: Alerts for batteries with abnormally high temperatures or low voltage.**

**🚀 Workflow**

**Raw Data: The simulated raw data is provided as a .csv file.**

**Excel \& Pandas Cleaning: The data is processed to handle missing values, outliers, and create new features like health\_percent.**

**Power BI: The cleaned dataset is imported to create visualizations and the final dashboard.**

**GitHub Publishing: All project files, including data, code, and dashboard, are uploaded to this repository.**

**📂 Repository Structure**

**Battery-Intelligence-Analysis/

**│**

**├── data/**

**│   ├──costing_data

**│   └── sales_data Q1

**│   └── Ssles_data Q2

**│**

**├── notebooks/**

**│   └── final_data_sets

**│**

**├── dashboard/**

**│   └── final_data.pbix

**│**

**├── images/**

**│   └──check_adain.png

**│**

**└── README.md**

**🔮 Future Improvements**
**Implement a Machine Learning model to predict battery lifetime with greater accuracy.**

**Expand the analysis to include a larger, real-world dataset.**

**Build a web application (e.g., using Streamlit) for dynamic, online access to the analysis.**


