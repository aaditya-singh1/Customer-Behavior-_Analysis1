# Customer Behavior Analysis

## 📌 Project Overview
This repository contains an end-to-end data analytics project focused on understanding consumer shopping habits, purchasing patterns, and demographic trends. By leveraging **SQL** for deep-dive data manipulation and **Power BI** for interactive visualizations, this project uncovers actionable insights to optimize marketing strategies, enhance customer retention, and drive business growth.

## 📊 Tech Stack
* **Database & Querying:** SQL (Structured Query Language)
* **Data Visualization:** Power BI Desktop (`.pbix`)
* **Data Source:** Customer Shopping/Behavior Datasets

## 📂 Repository Structure
```text
├── Customer_Shopping_Behavior_Data/   # Raw and cleaned dataset files
├── Solutions1.sql                     # SQL scripts for data exploration & business logic
├── customer_behavior.pbix             # Power BI Dashboard file
└── README.md                          # Project documentation
```

## 🔍 Key Insights & SQL Analysis
The `Solutions1.sql` file contains advanced queries addressing critical business questions, including:
- **Demographic Segmentation:** Analyzing spending behavior across different age groups, genders, and locations.
- **Purchase Trends:** Identifying peak shopping seasons, high-demand product categories, and preferred payment methods.
- **Customer Lifetime Value (CLV):** Segmenting high-value customers from low-frequency shoppers.

## 📉 Power BI Dashboard
The `customer_behavior.pbix` dashboard provides interactive visual elements such as:
* **Executive Summary:** Overview of total sales, total transactions, and average order value.
* **Customer Persona Tabs:** Filters for drilling down into specific demographic behavior.
* **Sales Performance:** Visual trackers for top-performing product categories and payment types.

### How to View the Dashboard
1. Download and install [Power BI Desktop](https://microsoft.com).
2. Clone this repository locally.
3. Open `customer_behavior.pbix` to explore the interactive visual metrics.

## 🚀 Getting Started

### Prerequisites
To replicate this project locally, ensure you have:
* A SQL Database Management System (e.g., PostgreSQL, MySQL, or SQL Server).
* Microsoft Power BI Desktop.

### Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Database Setup:** 
   - Import the dataset from the data folder into your SQL database.
   - Execute the scripts inside `Solutions1.sql` to run the data analysis queries.
3. **Dashboard Connection:**
   - Open the `.pbix` file and update the data source settings to link to your local dataset copy if necessary.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com).

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
