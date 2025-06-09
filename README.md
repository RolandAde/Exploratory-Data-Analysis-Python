# Online Clothing Store: Sales Analysis (Jan–June 2024)

This project presents a comprehensive exploratory data analysis (EDA) and monthly sales trend analysis for an online clothing store, using synthetic data spanning from January to June 2024.

## 🔍 Project Focus
- **Exploratory Data Analysis (EDA)**: Summary statistics, category performance, customer types, and regional breakdowns.
- **Sales Trend Analysis**: Monthly sales figures, spike/dip detection, and an investigation into April’s significant sales decline.

Each analysis is contained in its own Jupyter notebook and concluded with a professional report written in plain language for decision-makers.

---

## 📂 Project Structure

```bash
project-root/
│
├── eda_summary.ipynb           # Full EDA: Summary stats, category insights, etc.
├── monthly_sales_trend.ipynb   # Monthly sales trends and April investigation
├── dataset_description.md      # Description of the dataset columns
├── README.md                   # This file

____________________________

---

### 📘 `dataset_description.md` — Dataset Column Descriptions

```markdown
# Dataset Column Descriptions

This markdown file describes each column present in the synthetic dataset used for this analysis.

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Date`            | Date of transaction (format: YYYY-MM-DD)                                    |
| `Customer_Type`   | Type of customer — either `New` or `Returning`                              |
| `Region`          | Region of the buyer — `North`, `South`, `East`, or `West`                   |
| `Category`        | Broad product category — e.g., `Footwear`, `Bodywear`, etc.                 |
| `Subcategory`     | More detailed product classification — e.g., `Sneakers`, `T-shirt`, etc.    |
| `Unit_Price`      | Price of a single unit of product in USD                                     |
| `Units_Sold`      | Quantity of units sold in that transaction                                   |
| `Discount`        | Discount applied on the product (as a proportion, e.g., 0.10 = 10%)          |
| `Sales (USD)`     | Total revenue generated for the transaction (after discount)                |

> ⚠️ Note: Discounts are proportions, not percentages. Multiply by 100 to convert (e.g., 0.08 → 8%).


