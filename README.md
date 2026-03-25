# UK Online Retail Analysis

A data analysis project completed as part of **COMP7024 – Programming for Data Science** at Western Sydney University (Q1 2026).

## Overview

This project analyses a UK-based online retailer dataset across four key areas using R and R Markdown.

## Analysis

- **Part 1 – Product Revenue Analysis:** Joined Orders and Product Info tables, calculated total revenue per product, identified Top 10 and Bottom 10 products, and measured revenue concentration of the Top 3 products.
- **Part 2 – High-Value Customer Analysis:** Identified the Top 5 highest spending customers and analysed their purchasing behaviour by product quantity.
- **Part 3 – Global Market Analysis:** Calculated total revenue by country across 38 markets and identified the most purchased product per country.
- **Part 4 – Temporal Analysis & Trends:** Extracted monthly revenue trends, identified peak sales months, and flagged consistently low-selling products over time.

## Tech Stack
    
- **Language:** R
- **Libraries:** tidyverse, ggplot2, dplyr, kableExtra, lubridate
- **Report Format:** R Markdown (PDF output)

## Repository Contents

- `Assignment_Template.Rmd` – R Markdown source file with all code, comments, and interpretations
- `Assignment_Template.pdf` – Rendered PDF report with all tables, ggplot2 visualisations, and analysis
- `project_orders.csv` – Transactional orders data (InvoiceNo, StockCode, Quantity, InvoiceDate, UnitPrice, CustomerID, Country)
- `project_product_info.csv` – Product details data (StockCode, Description)
