# Data Warehouse and Analytics Project

Data Warehouse solution built with Microsoft SQL Server, implementing the Medallion Architecture (Bronze, Silver, Gold) to transform raw data into high-quality analytical insights.
Design as a portfolio project to simulate a real business analytics environment from raw operational data to curated reporting datasets and analytical insights

---
## 📌Project Requirements
### Building the Data Warehouse (Data Engineering)


#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model design for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**:Provide clear documentiaon of the data model to support both business stakeholders and analytics teams.

---
#### Data Architecture
The data architecture for this project follows a Medallion Architecture Bronze, Silver, and Gold Layers:
![Data Architecture](https://github.com/evan-dg31/Data-Warehouse/blob/7446a49b16cde4ce27f185c544c106d237db4d4d/docs/Data%20Architecture.png)

### Data Warehouse Layer Overview:
The data warehouse is organized into three layers to support analytics and reporting. The Bronze Layer stores raw, unprocessed data ingested directly from source systems. The Silver Layer cleanses, standardizes, and normalizes this data to create consistent, structured datasets. Finally, the Gold Layer houses business-ready data in a star schema, combining fact and dimension tables for reporting, dashboards, and advanced analytics.

### Repo Structure
<img width="589" height="447" alt="repo_structure" src="https://github.com/user-attachments/assets/99987d65-881e-4604-b40a-04ad0b1bd6fe" />


---

### BI: Analytics & Reporting (Data Analytics)
#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**


👤 **About Me**

Hi there! I'm **Evan de Guzman**, a graduate student in Data Science and Business Analytics with a strong passion for turning data into impact. My interests span data engineering, analytics engineering, machine learning, and AI engineering.

#### Graduate Student in Data Science & Business Analytics | Data Engineering • Machine Learning • AI

## 🛡️License

This project is licensed under the [MIT LICENSE](https://choosealicense.com/licenses/mit/). You are free to use, modify, and share this project with proper attribution


