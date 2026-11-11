## Boston Condo Sales Analysis | Tableau

### Project Overview

This project analyzes Boston condominium sales data using Tableau Desktop. It explores sales performance, property characteristics, pricing patterns, area-level comparisons, and sales trends over time.

The workbook combines analytical worksheets, interactive dashboards, calculated fields, filters, parameters, and a storyboard to present the analysis from multiple perspectives.

### Project Objectives

Evaluate sales performance across different areas and property types.

Analyze sales patterns by bedroom and bathroom configurations.

Compare property prices across areas and individual properties.

Examine monthly, quarterly, and yearly sales trends.

Explore property characteristics such as square footage, condo fees, and taxes.

Identify high-value and low-value properties.

Build interactive dashboards to support data exploration.

### Tools & Techniques

Tool: Tableau Desktop

### Techniques used:

Data visualization and dashboard development

Calculated fields and data categorization

Parameters and parameter-driven analysis

Sets and Top N analysis

Interactive filters and dashboard actions

Time-based analysis using month, quarter, and year

Comparative analysis and data storytelling

### Data Overview

The workbook uses the Boston Condo Dataset and Dictionary.

The dataset includes fields relating to:

Sales: Sales ID, sale price, first price, last price, first date, and close date.

Property: Property ID, street number, street name, unit, and area.

Property characteristics: Interior square footage, number of bedrooms, bathrooms, and rooms.

Property costs: Condo fee and tax.

Additional information: RC field used in the workbook's property-type classification.

The packaged Tableau workbook (.twbx) includes its data extract.

### Analytical Areas

The workbook contains multiple analytical worksheets and seven dashboards covering the following areas:

### 1. Sales Performance by Area

Sales value comparisons across different areas.

Area contribution to overall sales.

Area-level sales comparisons using filters and actions.

### 2. Property Type and Configuration Analysis

Residential and commercial property classification.

Sales comparisons by bedroom configuration (1BHK, 2BHK, 3BHK, and 4BHK).

Sales analysis by bathroom configuration.

Property-type comparisons.

### 3. Property Pricing Analysis

Top 10 highest-priced properties.

Top 10 lowest-priced properties.

First price, last price, and sale price comparisons.

Price correlation analysis.

Sale price distribution.

### 4. Time-Based Sales Analysis

Monthly and yearly sales trends.

Quarterly area sales.

Quarterly sales trend comparisons.

Sales seasonality analysis.

### 5. Property Characteristics and Costs

Condo fees by area.

Property taxes by area.

Minimum and maximum square footage by area.

Property-level and area-level comparisons.

### 6. Interactive and Parameter-Driven Analysis

Top-area analysis using parameters.

Parameter-driven filtering and set-based analysis.

Dashboard actions connecting different visualizations.

Interactive exploration by area, property type, and other dimensions.

## Dashboard Previews

The following three dashboards highlight selected parts of the broader workbook.

### 1. Area and BHK Sales Analysis

Compares sales values across areas and bedroom configurations, with additional analysis by bathroom configuration.



### 2. Quarterly Sales Trends

Examines quarterly sales activity across years and compares annual and quarterly performance.



### 3. Property Pricing and Sales Seasonality

Compares the top 10 high-cost and low-cost properties and explores quarterly sales price patterns across years.



## Storyboard: Key Observations

The workbook's storyboard documents the following observations:

Area M (ZIP code 2112) contributes the highest recorded sales value in the area percentage analysis, at approximately 24.46%.

The third quarter of 1993 records a notable peak in the seasonal sales analysis.

A substantial portion of transactions falls within the 100K–200K sale-price range.

Cambridge Parkway stands out in the street-level analysis with a recorded value of 455,455.

The first-price, last-price, and sale-price comparison indicates a downward pattern across the areas analyzed.

The price correlation analysis shows many observations below the diagonal, indicating last prices below first prices.

The 2BHK category is highlighted as a leading category in the workbook's sales analysis.

Area E is identified as having the highest average condo fee and average tax in the area comparisons.

These are observations documented in the workbook's storyboard and should be interpreted in the context of the dataset and selected views.

| File | Description |
|---|---|
| `Vasandhan_DVT Boston Condo.twbx` | Complete Tableau packaged workbook, including the data extract |
| `Screenshots/` | Selected dashboard previews |

### How to Explore the Project

1. Download the .twbx file from this repository.

2. Open it using Tableau Desktop.

3. Navigate through the worksheets, dashboards, and storyboard.

4. Explore the interactive filters, dashboard actions, and parameter-driven views.

### Acknowledgement

Completed as part of the Great Learning Tableau course.
