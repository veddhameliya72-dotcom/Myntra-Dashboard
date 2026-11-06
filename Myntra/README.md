<div align="center">

# 🛍️ Myntra Sales & Product Analysis Dashboard
### *Power BI E-Commerce Sales Analysis & Interactive Dashboard Project*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-blue?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-Myntra%20E--Commerce-ff3f6c?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Sales%20%26%20Product%20Analysis-5b3cc4?style=for-the-badge)

**Power BI · Myntra Dashboard Project**

</div>

---

# 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [📦 Dataset & Data Model](#-dataset--data-model)
- [✨ Features](#-features)
- [🏗️ Repository Structure](#️-repository-structure)
- [🗂️ Report Pages](#️-report-pages)
  - [📊 Page 1: Sales Overview](#-page-1-sales-overview)
  - [📦 Page 2: Product Analysis](#-page-2-product-analysis)
- [🔍 Filters & Slicers](#-filters--slicers)
- [💡 Key Insights](#-key-insights)
- [🎨 Theme & Formatting](#-theme--formatting)
- [🛠️ Tools & Techniques](#️-tools--techniques)
- [🚀 How to Use This Project](#-how-to-use-this-project)
- [🎥 Video Walkthrough](#-video-walkthrough)
- [📈 Learning Outcomes](#-learning-outcomes)
- [👤 Author](#-author)

---

# 📌 Overview

The **Myntra Sales & Product Analysis Dashboard** is a Microsoft Power BI project designed to explore e-commerce order performance, revenue, product distribution, inventory, brand performance and order status.

The report contains **two pages**:

- 📊 **Sales Overview**: summarizes total orders and net revenue, and compares orders by city tier, category and brand.
- 📦 **Product Analysis**: explores product distribution, size-wise inventory, brand revenue, city-tier revenue, top products and order status distribution.

The dashboard uses a Myntra-themed design with a dark navy header, purple accents and interactive report elements.

---

# 🎯 Objective

The main objective of this project is to analyze Myntra e-commerce data and present key business metrics through an interactive Power BI dashboard.

The project focuses on:

- Understanding overall order and revenue performance
- Comparing orders across product categories and brands
- Analyzing order distribution across city tiers
- Reviewing product distribution and size-wise inventory
- Comparing brand revenue performance
- Identifying top products by revenue
- Understanding the distribution of order statuses
- Presenting the analysis in a clear, multi-page dashboard

---

# 📦 Dataset & Data Model

The Power BI model screenshot shows the following tables:

| Table | Purpose shown / inferred from table name |
|---|---|
| `Date` | Date-related fields |
| `myntra_db orders` | Order data |
| `myntra_db products` | Product data |
| `myntra_web_catalog` | Myntra web catalog data |
| `Size Table` | Product size information |

**Note:** The screenshots do not show the original dataset download source, file format, row counts or full column list. Those details are therefore not specified here.

---

# ✨ Features

- 💰 KPI cards for **Total Orders** and **Net Revenue**
- 📊 Orders by City Tier doughnut chart
- 📊 Orders by Category column chart
- 📊 Orders by Brand horizontal bar chart
- 🎛️ Brand, Category and City Tier slicers
- 👕 Product Distribution doughnut chart
- 📦 Size Wise Inventory chart
- 🏷️ Brand Performance by Revenue chart
- 🌆 City Tier Analysis by Revenue chart
- 📋 Top 10 Products by Revenue table
- 🔄 Order Status Distribution doughnut chart
- 📄 Two-page report: Sales Overview and Product Analysis

---

# 🏗️ Repository Structure

The folder screenshot shows the Power BI report and an asset folder. The structure below reflects the visible items; add the image files to the asset folder if you want to include dashboard screenshots in this README.

```text
📦 Myntra_SQL_Power_BI
│
├── 📊 myntra_Dashboard.pbix       → Power BI Dashboard File
│
├── 📁 Assest                      → Project Assets Folder
│
├── 📁 Dataset                     → Data Tables Folder
│
└── 📝 README.md                   → Project Documentation
```

---

# 🗂️ Report Pages

## 📊 Page 1: Sales Overview

The **Sales Overview** page provides a summary of Myntra order and revenue performance. It includes slicers on the left, two KPI cards across the top, and charts comparing orders by city tier, category and brand.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 🛒 Total Orders | 2,00,000 |
| 💰 Net Revenue | ₹1,472M |

### Orders by City Tier

The doughnut chart shows the distribution of orders across the three city tiers.

| City Tier | Orders | Share |
|---|---:|---:|
| Tier 2 | 100.06K | 50.03% |
| Tier 1 | 75.04K | 37.52% |
| Tier 3 | 24.9K | 12.45% |

### Orders by Category

| Category | Orders |
|---|---:|
| School Shoes | 24.3K |
| Kids Wear | 24.2K |
| Perfume | 17.1K |
| Lipstick | 16.6K |
| Face Wash | 15.7K |
| Tops | 13.8K |

### Orders by Brand

| Brand | Orders |
|---|---:|
| Puma | 22.0K |
| Hrx | 21.9K |
| Nike | 21.6K |
| Levis | 20.9K |
| H&M | 20.8K |
| Campus | 19.4K |
| Zara | 18.8K |

### 📸 Dashboard Screenshot

Add your Sales Overview screenshot in the project and update the image path below.

<img src="Assets/Dashboard image/Page-1.png" alt="Myntra Sales Overview Dashboard">

---

## 📦 Page 2: Product Analysis

The **Product Analysis** page focuses on product mix, inventory, brand revenue and order status. It also includes a table showing the top 10 products by revenue.

### Product Distribution

The doughnut chart displays the distribution of products across five categories:

- Face Wash
- Kids Wear
- Lipstick
- Perfume
- School Shoes

The chart displays an even **20%** share for each category.

**Total Products:** 3,000

### Size Wise Inventory

| Size | Inventory (Units) |
|---|---:|
| XS | 380K |
| S | 457K |
| M | 672K |
| L | 524K |
| XL | 300K |

### Brand Performance (Revenue)

| Brand | Revenue |
|---|---:|
| Hrx | ₹167M |
| Levis | ₹157M |
| Puma | ₹156M |
| Nike | ₹154M |
| H&M | ₹153M |
| Campus | ₹151M |
| Us Polo | ₹144M |
| Roadster | ₹136M |
| Zara | ₹130M |
| Adidas | ₹124M |

### City Tier Analysis (Revenue)

| City Tier | Revenue |
|---|---:|
| Tier 2 | ₹738M |
| Tier 1 | ₹552M |
| Tier 3 | ₹182M |

### Top 10 Products by Revenue

The table displays the following fields:

- Product Name
- Brand Name
- Category
- Total Orders
- Total Revenue

It ranks products by revenue and provides a product-level view of performance.

### Order Status Distribution

| Order Status | Share displayed |
|---|---:|
| Returned | 27.76% |
| Cancelled | 24.86% |
| Shipped | 24.12% |
| Delivered | 23.27% |

The page also displays a **Total Orders** card of **200K**.

### 📸 Product Analysis Screenshot

Add your Product Analysis screenshot in the project and update the image path below.

<img src="Assets/Dashboard image/Page-2.png" alt="Myntra Product Analysis Dashboard">

---

# 🔍 Filters & Slicers

The Sales Overview page visibly includes the following slicers:

| Slicer | Field |
|---|---|
| Brands | Brand |
| Category | Category |
| City Tier | City Tier |

The slicers include an **All** selection and checkbox-style options. They allow the report to be explored by brand, product category and city tier.

---

# 💡 Key Insights

Based on the values visible in the dashboard screenshots:

- 🛒 The Sales Overview reports **2,00,000 total orders**.
- 💰 The displayed net revenue is **₹1,472M**.
- 🌆 **Tier 2** contributes the largest share of orders at **50.03%** and the highest city-tier revenue at **₹738M**.
- 👟 **School Shoes** has the highest displayed category order count at **24.3K**, closely followed by Kids Wear at **24.2K**.
- 🏷️ **Puma** has the highest displayed brand order count at **22.0K** on the Sales Overview page.
- 📈 **Hrx** has the highest displayed brand revenue at **₹167M** on the Product Analysis page.
- 📦 Size **M** has the highest displayed inventory at **672K units**.
- 🔄 **Returned** is the largest order-status segment shown at **27.76%**.

---

# 🎨 Theme & Formatting

### Design

- Dark navy header and left-side navigation panel
- Myntra logo and page titles in the header
- Light grey report canvas
- White visual containers with rounded corners
- Purple accents for navigation and selected elements
- Blue, green, orange and purple chart colors
- KPI cards with large, clearly visible values

### Dashboard Layout

- **Page 1:** Left-side slicers with KPI cards and order charts.
- **Page 2:** Four analysis visuals across the top, with a product revenue table and order status chart below.

---

# 🛠️ Tools & Techniques

| Tool / Feature | Purpose |
|---|---|
| Microsoft Power BI Desktop | Report creation and data visualization |
| Power Query Editor | Data preparation and transformation |
| Data Model | Organizing the date, order, product, catalog and size tables |
| KPI / Card Visuals | Displaying total orders, revenue and product totals |
| Doughnut Charts | Showing city-tier, product and order-status distributions |
| Column Chart | Comparing orders by category and revenue by city tier |
| Bar Charts | Comparing brand orders, inventory and brand revenue |
| Table Visual | Displaying the top 10 products by revenue |
| Slicers | Filtering by brand, category and city tier |

---

# 🚀 How to Use This Project

1. **Clone** or download this repository.
2. Open `myntra_Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If Power BI displays a data-source error, open **Home → Transform data → Data source settings** and update the source path to the location of your dataset.
4. Select **Refresh** to load the data.
5. Use the Brand, Category and City Tier slicers on the Sales Overview page to explore the report.
6. Navigate between **Sales Overview** and **Product Analysis** to review the different analyses.

**Note:** The screenshots do not show the original dataset file name or source path, so the data-source location may need to be updated on your computer.

---

# 📈 Learning Outcomes

- ✅ Build a multi-page Power BI dashboard
- ✅ Work with a data model containing multiple tables
- ✅ Present sales and revenue KPIs
- ✅ Compare orders by brand, category and city tier
- ✅ Analyze product distribution and size-wise inventory
- ✅ Compare brand revenue performance
- ✅ Create product-level revenue tables
- ✅ Visualize order-status distribution
- ✅ Use slicers to explore report data
- ✅ Present business information through interactive visualizations

---

# 👤 Author

<div align="center">

# Ved Dhameliya


**Myntra Sales & Product Analysis Dashboard – Power BI Project**

*Power BI · SQL · E-Commerce Data Analysis*

---

### ⭐ Thank You For Visiting This Project ⭐

Made with ❤️ using Microsoft Power BI

</div>
