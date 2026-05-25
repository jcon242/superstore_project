# Superstore Sales Dashboard

An interactive multi-page Power BI dashboard built on the [Kaggle Superstore dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final), providing business insights across sales performance, geography & products

## About the Dataset

The Superstore dataset is a widely used fictional US retail dataset available on Kaggle. It contains ~9,994 orders placed between 2014 and 2017 across three product categories (**Furniture**, **Office Supplies**, and **Technology**) sold to customers in the Consumer, Corporate, and Home Office segments.

**Key fields include:** Order & ship dates, shipping mode, customer info, region/state/city, product category & sub-category, sales, quantity, discount, and profit.

It's commonly used for practicing data analysis, visualisation, and business intelligence projects, customers, and shipping.

## Tools Used

- **Python (Pandas)** - data cleaning and preprocessing (`superstore.ipynb`)
- **Power BI Desktop** - dashboard design and visualisation

## Dashboard Pages

| Page | Purpose |
|------|---------|
| **Executive Overview** | High-level KPIs |
| **Geographic Performance** | Regional and state-level performance across the US |
| **Product Performance** | Best and worst performing products and sub-categories |
| **Customer Analysis** | Top customers by revenue and profit, order behaviour |
| **Shipping Analysis** | Shipping modes, delivery times, and logistics trends |

## Getting Started

1. Clone or download this repository
2. Open `Superstore Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. If prompted, re-link the data source to `store_clean.csv`

## Notes

- The raw dataset was cleaned in Python before being loaded into Power BI - see `superstore.ipynb` for the preprocessing steps
- All data is fictional and intended for practice/portfolio purposes only
