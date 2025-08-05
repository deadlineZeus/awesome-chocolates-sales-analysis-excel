# Awesome Chocolates – Excel-Based Sales Data Analysis

## Project Overview

This project demonstrates Excel-based data analytics applied to a simulated retail company, *Awesome Chocolates*. It addresses 10 core business questions using structured sheets, pivot tables, Excel formulas, and visualizations — all designed for beginner-to-intermediate data analysts.

The workbook is structured to make exploration intuitive, with each business question linked to its respective analysis sheet. All sheets include a "Home" button to return to the starting page.

---

<details>
<summary>Table of Contents</summary>

- [Objectives](#objectives)
- [Business Questions](#business-questions)
- [Dataset Overview](#dataset-overview)
- [Project Files](#project-files)
- [Navigation Features](#navigation-features)
- [Tools and Techniques](#tools-and-techniques)
- [Recommendations](#recommendations)
- [Project Structure](#project-structure)
- [Contact](#contact)
</details>

---

## Objectives

- Analyze sales, profit, and returns across product categories and customer segments
- Identify regional and time-based patterns
- Use Excel’s core analytical features to draw business insights
- Build a clean, interactive workbook for guided analysis (non-dashboard)

---

## Business Questions

This project explores the following questions:
1. Which region generates the highest sales?
2. Which customer segment is most profitable?
3. What product category has the highest return rate?
4. Which time periods show peak sales activity?
5. Which subcategories yield the lowest profit?
6. What is the trend of sales over time?
7. Are returns affecting specific segments or regions more?
8. How does quantity sold relate to profit margins?
9. What are the most and least profitable customer types?
10. What insights can help improve operations at Awesome Chocolates?

Each question is hyperlinked to a dedicated analysis sheet within the Excel file.

---

## Dataset Overview

- **File**: `raw_data.xlsx`
- **Fields Included**:
  - Order ID, Order Date, Product, Subcategory
  - Sales, Profit, Quantity, Customer, Region, Segment
  - Return flag (Yes/No)

---

## Project Files

| File Name                   | Description                                                   |
|----------------------------|---------------------------------------------------------------|
| `raw_data.xlsx`            | Original sales dataset for *Awesome Chocolates*               |
| `data_analysis_on_excel.xlsx` | Excel workbook with:                                     |
|                            | - Data cleaning and preparation                              |
|                            | - Ten analysis sheets linked to core business questions       |
|                            | - Pivot tables, formulas, conditional formatting              |
|                            | - Navigation links for seamless exploration                  |

---

## Navigation Features

- Each question in the main sheet is clickable and takes the viewer to its corresponding analysis sheet.
- Each analysis sheet contains a "Home" button to return to the main question sheet.

---

## Tools and Techniques

Platform: Microsoft Excel  
Excel Features Demonstrated:
- Pivot Tables
- Conditional Formatting
- Slicers (optional in future versions)
- Formula logic: `SUMIFS`, `COUNTIFS`, `IF`, `AVERAGEIFS`, logical operators
- Data filtering and sorting
- Structured workbook navigation using hyperlinks

---

## Recommendations

The following recommendations are based on insights derived from the sales and profit analysis of Awesome Chocolates:

<details>
<summary><strong>1. Discontinue low-performing subcategories based on negative profit trends</strong></summary>

Consistently unprofitable subcategories should be reviewed for discontinuation, as they indicate a mismatch between cost and customer demand. These products reduce overall profitability and may occupy valuable shelf or warehouse space that could be better used for high-margin items. By eliminating or repositioning underperformers, Awesome Chocolates can streamline its offerings, reduce operational waste, and reallocate resources toward more successful product lines, leading to improved overall financial health.

</details>

<details>
<summary><strong>2. Optimize high-return segments by improving product quality or customer support</strong></summary>

A high volume of product returns often signals issues with quality, packaging, or post-sale service. Identifying these segments allows the company to improve products or support processes that may be causing dissatisfaction. Enhancing product quality, clarifying marketing descriptions, or improving return policies can significantly reduce return rates. This not only minimizes financial losses but also improves customer satisfaction and loyalty — both critical for long-term brand success.

</details>

<details>
<summary><strong>3. Use similar Excel-driven templates for recurring performance reviews</strong></summary>

The current Excel-based model is structured, repeatable, and easy to update, making it ideal for monthly or quarterly performance tracking. With minimal changes to the data source, stakeholders can monitor KPIs, segment performance, and emerging trends in a consistent format. Adopting this approach across reporting cycles saves time, improves decision-making, and promotes data transparency. It serves as a lightweight, effective alternative to complex BI tools for small-to-mid-sized businesses like Awesome Chocolates.

</details>

---

## Project Structure

