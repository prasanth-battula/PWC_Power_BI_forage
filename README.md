# README: Forage PwC Power BI Task

## Overview
This README provides a comprehensive guide to understanding, analyzing, and explaining the Power BI dashboards created for the Forage PwC task. These dashboards were sourced from GitHub, and the purpose of this document is to help you understand how they were created, their purpose, and the methodologies used in the analysis.

---

## Project Goals
The primary objectives of the project are:
1. **Data Visualization:** Convert raw datasets into interactive and meaningful visualizations.
2. **Insights Derivation:** Highlight key trends, patterns, and actionable insights from the data.
3. **Business Value:** Address business-related challenges and provide data-driven recommendations.

---

## Files Provided
1. **Power BI Reports (.pbix files):**
   - `Call Center Solution.pbix`
   - `Diversity Inclusion.pbix`
   - `Customer Retention.pbix`

2. **Datasets:**
   - `01 Call-Center-Dataset.xlsx`
   - `02 Churn-Dataset.xlsx`
   - `03 Diversity-Inclusion-Dataset.xlsx`

3. **Other Supporting Files:**
   - Documentation or notes (if any).

---

## Dashboard Details

### 1. Call Center Solution Dashboard
#### Purpose:
- Monitor and improve call center performance.

#### Key Visualizations:
- **Call Volume Trends:** Line charts showing call volumes over time.
- **Agent Performance:** Bar charts ranking agents based on key performance indicators (KPIs).
- **Customer Satisfaction (CSAT):** A gauge chart tracking customer satisfaction levels.
- **First Call Resolution (FCR):** Percentage visual tracking resolution effectiveness.

#### Methodology:
1. **Data Cleaning:** Processed raw call logs to identify incomplete and duplicate records.
2. **Modeling:** Built relationships between `Agent`, `Call`, and `Customer` tables.
3. **Metrics Used:** Average Handling Time (AHT), Abandonment Rate, and CSAT score.
4. **Interactivity:** Used slicers for filtering by date, agent, and region.

---

### 2. Diversity Inclusion Dashboard
#### Purpose:
- Analyze workplace diversity and inclusion metrics.

#### Key Visualizations:
- **Gender Representation:** Pie charts showing the proportion of male and female employees.
- **Employee Satisfaction:** Heatmaps showing satisfaction scores by department.
- **Turnover Rates:** Bar charts displaying employee turnover trends by demographics.
- **Pay Gap Analysis:** Line and bar visualizations illustrating pay differences.

#### Methodology:
1. **Data Transformation:** Normalized and aggregated diversity data.
2. **Calculated Metrics:** Diversity Index, Satisfaction Score, and Turnover Rate.
3. **Filters:** Enabled segmentation by department, role, and demographic.

---

### 3. Customer Retention Dashboard
#### Purpose:
- Understand factors affecting customer churn and improve retention strategies.

#### Key Visualizations:
- **Churn Trends:** Line charts showing monthly churn rates.
- **Retention by Plan Type:** Clustered bar charts analyzing retention by subscription plan.
- **Customer Feedback:** Word clouds summarizing common feedback themes.
- **Predictive Metrics:** Visualizing scores indicating churn likelihood.

#### Methodology:
1. **Data Preparation:** Consolidated multiple customer feedback and subscription datasets.
2. **Predictive Analysis:** Used historical data to calculate churn probability using DAX formulas.
3. **Visual Interactivity:** Enabled dynamic filtering by region, product type, and feedback category.

---

## Tools and Techniques Used
1. **Power BI Desktop:** For data modeling, visualization, and report creation.
2. **Data Cleaning:** Performed in Power Query.
3. **DAX (Data Analysis Expressions):** Used for calculated columns, measures, and advanced analytics.
4. **Data Sources:** Connected to Excel datasets provided and established relationships.
5. **Themes and Aesthetics:** Applied a consistent color scheme and layout for user-friendly navigation.

---

## Steps to Recreate Dashboards
1. **Data Import:** Load the datasets into Power BI.
2. **Data Transformation:** Clean and preprocess data using Power Query.
3. **Data Modeling:** Establish relationships between tables (e.g., one-to-many, many-to-many).
4. **Measure Creation:** Write DAX expressions for KPIs and calculated fields.
5. **Visualization:** Use charts, tables, and slicers to create dashboards.
6. **Interactivity:** Configure filters and slicers for dynamic analysis.
7. **Testing:** Validate insights and ensure consistency across visualizations.

---

## How to Analyze the Dashboards
1. **Understand KPIs:** Focus on the metrics used and their relevance to business goals.
2. **Check Interactivity:** Test slicers, filters, and drill-through options.
3. **Insights Validation:** Cross-check visualized trends against raw data.
4. **Recommendations:** Consider how insights can inform strategic decisions.

---

## Recommendations for Improvement
1. **Data Sources:** Explore integrating additional datasets for richer insights.
2. **Predictive Analytics:** Incorporate machine learning models for advanced forecasting.
3. **Report Enhancements:** Add tooltips and dynamic narratives for better user understanding.
4. **Automation:** Schedule data refreshes for up-to-date dashboards.

---

## Conclusion
The provided dashboards offer valuable insights into call center performance, diversity metrics, and customer retention strategies. By following the steps and methodologies outlined above, you can thoroughly understand and replicate these reports, as well as identify areas for enhancement.

