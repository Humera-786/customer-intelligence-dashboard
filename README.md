# Retenza Pro – Customer Intelligence & Churn Analytics Dashboard

An interactive, browser-based analytics dashboard designed to analyze customer retention, detect churn patterns, and highlight revenue risk using customer data.

## 🚀 Key Features

- **Automated CSV Field Mapping:** Automatically detects and aligns fields like `MonthlyCharges`, `tenure`, `Contract`, `PaymentMethod`, and `Churn` status.
- **Executive Metrics:** Displays total customer count, churn rates, monthly revenue totals, and average customer tenure.
- **Interactive Visualizations:** Dynamically renders revenue trends, contract breakdowns, and churn risk segments.
- **Client-Side Data Processing:** Operates directly in the browser with no backend database setup required.

## 📁 Repository Structure

```text
├── index.html                 # Main dashboard web application
├── Telco-Customer-Churn.csv   # Standard customer dataset
└── README.md                  # Project documentation
🛠️ How to Run Locally
Clone or download this repository.
Open index.html directly in any modern web browser (Google Chrome, Microsoft Edge, Firefox, or Safari).
Click Upload Dataset on the dashboard.
Select Telco-Customer-Churn.csv to populate all cards, charts, and metrics automatically.
📊 Dataset Details
The application is fully compatible with the standard Telco Customer Churn dataset. The code expects (or maps) the following standard fields:
customerID
gender
tenure
Contract
MonthlyCharges
TotalCharges
Churn
PaymentMethod
📄 License
This project is created for academic and personal portfolio demonstration purposes.
