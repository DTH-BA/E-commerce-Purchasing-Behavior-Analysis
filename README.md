# E-commerce Purchasing Behavior Analysis

## Project Overview
This project aims to analyze **customer purchasing behavior** using transactional data from a simulated e-commerce platform.  
The dataset includes multiple entities (**users, products, promotions, orders, and order items**) which together provide a 360° view of customer activity.  

**Key goals:**
- Build a relational database schema in MySQL.  
- Perform SQL-based data wrangling to clean, join, and prepare the data.  
- Conduct exploratory data analysis (EDA) on customer behavior.  
- Visualize insights using Tableau dashboards.  

---

## Datasets
The project uses **5 CSV files** as input:  
- `users_extended.csv` – customer demographic & profile info.  
- `products_extended.csv` – product catalog with categories, prices, margins.  
- `promotions_extended.csv` – promotion campaigns and discount details.  
- `orders_extended.csv` – high-level order information (dates, amounts, payment).  
- `order_items_extended.csv` – line-item details for each order.  

---

## Tools & Technologies
- **Database**: MySQL 8.0 (import via `LOAD DATA INFILE`)  
- **SQL**: Data cleaning, transformations, and joins  
- **Visualization**: Tableau (interactive dashboards)  
- **Version control**: GitHub repository for datasets, SQL scripts, and documentation  

---

## Project Requirements

### 1. Database Setup
- Create `ecommerce_db` in MySQL.  
- Import all 5 CSV files into staging tables.  
- Clean inconsistent data (missing values, invalid dates, null integers).  
- Build an ERD (Entity Relationship Diagram) showing relations.  

### 2. Data Wrangling (SQL)
- Convert raw string dates into proper `DATE` or `DATETIME`.  
- Normalize categorical values (e.g., gender, status).  
- Ensure correct data types for numeric columns (price, discount, cost).  
- Create clean tables with PK/FK constraints for analysis.  

### 3. Exploratory Analysis
- Customer segmentation by demographics, location, and loyalty status.  
- Product performance by category, margin, and ratings.  
- Promotion effectiveness (discount rate vs. sales uplift).  
- Order trends over time (seasonality, channels, payment methods).  

### 4. Visualization (Tableau)
- **Dashboard 1**: Customer profile & segmentation.  
- **Dashboard 2**: Sales trends & product performance.  
- **Dashboard 3**: Promotion effectiveness & ROI.  

### 5. Documentation & Delivery
- Provide ERD diagram.  
- Save MySQL schema (`.sql` dump).  
- Publish Tableau dashboards.  
- Write project report summarizing findings.  
