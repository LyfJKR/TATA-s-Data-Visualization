TATA Data Visualization: Empowering Business with Effective Insights

<img width="1135" height="805" alt="image" src="https://github.com/user-attachments/assets/4eca4831-9ef6-435e-b985-042aeb330a4c" />

A comprehensive data visualization and analysis project demonstrating effective business intelligence techniques for the online retail dataset.

Project Overview

This project is part of the   TATA Data Visualization course   completed in April 2026. It encompasses the complete journey from data exploration to actionable business insights through multiple visualization platforms.

 Skills Covered
 - Framing the Business Scenario
 - Choosing the Right Visuals
 - Creating Effective Visuals
 - Communicating Insights and Analysis

Project Structure

```TATA Data Visualization/
│
├── README.md                            This file
├── assets/
│   ├── images/
│   │   ├── certificate.png             Certificate of completion
│   │   ├── tableau dashboard.png        Tableau visualizations
│   │   ├── powerbi dashboard.png        Power BI visualizations
│   │   ├── eda overview.png             EDA key findings
│   │   └── data sample.png              Dataset sample screenshot
│   └── documents/
│       └── project_summary.md           Detailed project summary
│
├── data/
│   ├── Online_Retail_Data_Set.csv      Raw dataset (541,908 records)
│   └── Online_Retail.xlsx               Data in Excel format
│
├── analysis/
│   ├── EDA.ipynb                        Exploratory Data Analysis (19 cells)
│   └── insights.md                      Key findings and insights
│
├── visualizations/
│   ├── Tableau/
│   │   ├── TATA_data.twb               Tableau workbook
│   │   └── dashboard screenshots/       Dashboard snapshots
│   │
│   ├── PowerBI/
│   │   ├── TATA_visualization.pbix     Power BI file
│   │   └── dashboard screenshots/       Dashboard snapshots
│   │
│   └── Model_Answers/                   Reference implementations
│       ├── Power BI.pbix
│       └── Tableau.twbx
│
└── documentation/
    ├── data_dictionary.md               Field descriptions
    └── methodology.md                   Analysis approach
```
Dataset Information

    Online Retail Dataset
    Records  : 541,908 transactions
    Time Period  : 2010 2011
    Variables  : 8 key fields
    
```
Field Descriptions
| Field | Type | Description |
|     |    |         |
| InvoiceNo | String | Unique invoice identifier |
| StockCode | String | Product code |
| Description | String | Product name/description |
| Quantity | Integer | Units purchased in transaction |
| InvoiceDate | DateTime | Date and time of purchase |
| UnitPrice | Float | Price per unit (in £) |
| CustomerID | Integer | Unique customer identifier |
| Country | String | Customer's country |
```
 Data Characteristics
    Geographic Coverage  : Multiple countries
    Currency  : British Pounds (£)
    Data Quality Issues  : Some null values and negative quantities to be handled

Exploratory Data Analysis
The EDA notebook (`EDA.ipynb`) contains:
  - 19 Python code cells   analyzing the dataset
  - Data cleaning and validation
  - Descriptive statistics
  - Distribution analysis
  - Time series patterns
  - Customer and product insights

 Key Findings
  - Product performance metrics
  - Customer spending patterns
  - Seasonal trends
  - Country wise sales distribution

Visualizations
  Tableau Dashboards (TATA_data.twb)
Interactive dashboards showcasing:
  - Sales trends over time
  - Product performance analysis
  - Customer segmentation
  - Geographic distribution
 <img width="1652" height="851" alt="image" src="https://github.com/user-attachments/assets/f226a559-744a-4c43-923c-a6e941694c8c" />

  Power BI Dashboards (TATA_visualization.pbix)
Comprehensive business intelligence reports:
 - Revenue analysis
 - Customer lifetime value
 - Market insights
 - Product profitability
<img width="1161" height="652" alt="image" src="https://github.com/user-attachments/assets/dd4e7a6e-7144-4ca7-b645-b4d1ec491e6a" />

Model Answer Files
Reference implementations provided in `visualizations/Model_Answers/`:
  `Power BI.pbix`   Professional Power BI dashboard
  `Tableau.twbx`   Professional Tableau workbook

Getting Started
    Prerequisites
    Python 3.x   (for Jupyter notebook)
    Tableau Public   or   Tableau Desktop   (for .twb files)
    Power BI Desktop   (for .pbix files)
    Jupyter Notebook   or   JupyterLab  

Installation
```bash
  Clone the repository
git clone https://github.com/yourusername/TATA Data Visualization.git
cd TATA Data Visualization

Install Python dependencies
pip install  r requirements.txt

Launch Jupyter Notebook
jupyter notebook analysis/EDA.ipynb
```

Opening Visualizations
Tableau:  
```bash
  Open Tableau Public/Desktop
  File > Open > visualizations/Tableau/TATA_data.twb
```
Power BI:  
```bash
  Open Power BI Desktop
  File > Open > visualizations/PowerBI/TATA_visualization.pbix
```
Project Milestones
  - Data Acquisition  : Online Retail dataset loaded
  - Data Exploration  : EDA completed with Python
  - Tableau Development  : Interactive dashboards created
  - Power BI Development  : Business intelligence reports created

Contact & Support
    Author  : Jeevan Rayamajhi
    Location  : Kathmandu, Nepal
    Course  : TATA Data Visualization (Forage)
License
This project is created for educational purposes as part of the TATA Data Visualization course by Forage.

 Acknowledgments
    - TATA Corporation   for the real world dataset and business context
    - Forage   for the virtual internship program
    - Tom Brunskill  , Co Founder of Forage, for course guidance

  

  Note  : Replace placeholder sections marked with `[Add your...]` with your actual findings and data.
