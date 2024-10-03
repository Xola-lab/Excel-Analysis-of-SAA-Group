# Excel Analysis: South African Airways (Group) Income Data (2021 - 2022)

## Background and Overview
This project focuses on analysing the financial performance of the South African AIrways (SAA) Group for the years 2021 and 2022. The data for this analysis was sourced directly from SAA's website in the form of a PDF document. The PDF contained detailed financial reports, from which I sourced the Income Statement and transformed it into a structured dataset for analysis

The purpose of this project was to assess the airline's financial health by analysing key metrics such as total income, operating costs, and net income/loss, providing insights into the overall operational performance and areas for improvement.

This project demonstrates the ability to clean, prepare, and analyse raw financial data, uncovering insights that are crucial for decision-making.

## Data Structure
The data struture for SAA's financial income statement was only a single table, containing the key sections of a financial statement:

<p align="center">
<img src="Data Structure.png">
</p>

## Executive Summary
#### Objective:
This project focuses on analysing the financial performance of the South African Airways (SAA) Group over the financial years 2021 and 2022, highlighting income, operating costs, and net income trends. The analysis aims to provide insight into the airline's financial recovery and ongoing challenges.

#### Key Findings:
- **Total Income**:
  In 2021, the total income was R5.44 billion, primarily driven by airline revenue (R2.38 billion) and other income sources (R3.06 billion).
  In 2022, the total income declined significantly to R2.01 billion, with airline revenue at R1.59 billion and other income dropping sharply to R418 million.
- **Operating Costs**:
  Operating costs in 2021 stood at R11.83 billion, including notable expenses such as aircraft lease costs (R1.51 billion).
  In 2022, operating costs were reduced to R5.19 billion, indicating an effort to manage financial strain during the recovery phase.
- **Net Income/Loss**:
  In 2021, the airline suffered a net loss of **R6.39 billion** due to high operating costs outweighing income.
  In 2022, the net loss was reduced to **R3.17 billion**, reflecting both lower income and operating expenses.

**Conclusion**: This analysis highlights the financial struggles faced by the SAA Group, including a sharp drop in total income and significant operating losses in both years.
While there was some reduction in losses by 2022, the company still faced major financial challenges.

#### Skills Demonstrated:
- **Data Cleaning and Preparation**: I structured the raw financial data into readable insights, using tools like Excel **pivot tables** and **charts** for dynamic analysis.
- **Descriptive Analysis**: I calculated key financial metrics, i.e. Net Income, to better prepare the data.
- **Visualisation (Dashboard)**: I created an interactive dashboard that visualises trends in the data over the two years.

#### Impact:
1. **Informed Decision-Making**: By analysing SAA's total income, oparating costs, and net income, this project could help stakeholders understand the airline's financial
trajectory. The findings can assist in making more informed decisions around cost-cutting, revenue generation, and operational strategies.
2. **Identification of Financial Risks**: The significant decline in total income and the consistent overspending on operating costs have been clearly identified. These
financial risks highlight the need for more aggressive cost management and revenue diversification to prevent further losses.
3. **Operation Efficiency Focus**: SAA's operational efficiency worsened in 2022, indicating a growing gap between income and costs. The airline will need to pinpoint
areas within the operational framework that require better cost controls.
4. **Recovery Strategies**: The year-on-year comparison provides a benchmark for tracking the success of recovery strategies implemented by the airline. As SAA seeks to
stabilise, these metrics can serve as a foundation to measure improvement in financial health.

<p align="center">
<img src="DASHBOARD SAA.png">
</p>

## Cleaning and Preparation
As already mentioned above, the initial dataset for this project was extracted from a PDF file containing the SAA's Income Statement for 2021 and 2022 [download or view here] (https://github.com/Xola-lab/Excel-Analysis-of-SAA-Group/blob/main/2022-south-african-airways-(saa)-annual-report.pdf). I took the following steps to clean and prepare the data for analysis:

1. **PDF to Excel Conversion**: The Income Statement was converted from the original PDF format to an Excel shett to facilitate further analysis. This ensured that the data was in a usable format, ready for manipulation and calculations.
2. **Data Formatting**: After extraction, the data required reformatting to ensure consistency:
   - Column headers were renamed for clarity (e.g., "Group 2021 (Rm)" and "Group 2022 (Rm)") to specify amounts in million Rands.
   - Then, using Power Query, I then used "Unpivot Colums" to create a new "Group Year" column.
   - Another column, "Group Category" was created to group the categories in the statement accordingly.
3. **Data Structuring**: Using the newly created column, the data was categorised by key financial metrics, including _Total Income_, _Operating Costs_, and other specific categories. This reshaping the data for easier comparison between the years.
4. **Error Checking**: The dataset went through review for any inconsistencies to ensure that all figured aligned with the original PDF data.

<p><img src="Income Reshaped.png"></p>

This thorough cleaning and preparation ensured that the data was accurate, consistent, and ready for insightful analysis, enabling a clearer understanding of SAA's financial performance over the two-year period.
