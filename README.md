# Excel Analysis: South African Airways (SAA) Group Income Data (2021 - 2022)

## Background and Overview
This project focuses on analysing the financial performance of the South African AIrways (SAA) Group for the years 2021 and 2022. The data for this analysis was sourced directly from SAA's website in the form of a PDF document. The PDF contained detailed financial reports, from which I sourced the Income Statement and transformed it into a structured dataset for analysis

The purpose of this project was to assess the airline's financial health by analysing key metrics such as total income, operating costs, and net income/loss, providing insights into the overall operational performance and areas for improvement.

This project demonstrates my ability to clean, prepare, and analyse raw financial data, uncovering insights that are crucial for decision-making.

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
- **Visualisation (Dashboard)**: I created an interactive dashboard that visualises trends in the data over the two years [download here](https://github.com/Xola-lab/Excel-Analysis-of-SAA-Group/blob/main/SAA%20Income%20Data%20(2021%20-%202022).xlsx)

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
As already mentioned above, the initial dataset for this project was extracted from a PDF file containing the SAA's Income Statement for 2021 and 2022 [download or view here](https://github.com/Xola-lab/Excel-Analysis-of-SAA-Group/blob/main/2022-south-african-airways-(saa)-annual-report.pdf). I took the following steps to clean and prepare the data for analysis:

1. **PDF to Excel Conversion**: The Income Statement was converted from the original PDF format to an Excel sheet to facilitate further analysis. This ensured that the data was in a usable format, ready for manipulation and calculations.
2. **Data Formatting**: After extraction, the data required reformatting to ensure consistency:
   - Column headers were renamed for clarity (e.g., "Group 2021 (Rm)" and "Group 2022 (Rm)") to specify amounts in million Rands.
   - Then, using Power Query, I then used "Unpivot Colums" to create a new "Group Year" column.
   - Another column, "Group Category" was created to group the categories in the statement accordingly.
3. **Data Structuring**: Using the newly created column, the data was categorised by key financial metrics, including _Total Income_, _Operating Costs_, and other specific categories. This reshaping the data for easier comparison between the years.
4. **Error Checking**: The dataset went through review for any inconsistencies to ensure that all figured aligned with the original PDF data.

<p><img src="Income Reshaped.png"></p>

This thorough cleaning and preparation ensured that the data was accurate, consistent, and ready for insightful analysis, enabling a clearer understanding of SAA's financial performance over the two-year period.

## Insights: Deep Dive
The analysis of the SAA Group's Income Statement for 2021 and 2022 revealed several key insighst into the company's financial performance during these two critical years. Here a deep dive into the findings:

1. **Decline in Total Revenue**:
   - **2021**: The total income was R5.44 billion, boosted by airline revenue and other income streams.
   - **2022**: There was a significant drop in total income to R2.01 billion. Airline revenue decreased to R1.59, while other income sources fell drastically to R418 million. This suggests a weakened business environment for the airline, possibly due to reduced operational activity or external economic factors.
**Insight** The sharp decline in income signals an urgent need for SAA to diversify its revenue streams and increase operational activity to offset these losses.
2. **High Operating Costs**:
   - **2021**: Operating costs were substantial at R11.83 billion, with notable expenses such as aircraft lease costs (R1.51 billion) and maintenance services.
   - **2022**: While operating costs reduced to R5.19 billion, they were still more than double the total income. Key expenses remained high, despite the reduced operational scale.
**Insight**: ALthough SAA managed to cut operating costs by more than half in 2022, these costs remain disproportionate to the group's income. There is a clear need for further optimisation of cost structures, particularly in non-revenue-generating expenses.
3. **Net Losses and Financial Strain**:
   - In 2021, SAA recorded a significant net loss of R6.39 billion, driven by the wide gap between income and expenses.
   - In 2022, the net loss narrowed to R3.17 billion, but this is still a significant deficit that highlights ongoing financial stability.
**Insight**: The reduction in net loss from 2021 to 2022 shows signs of financial recovery, but the overall losses indicate that SAA'a cost management and revenue generation need significant restructuring. Monitoring cost-saving measures will be essential for future sustainability.
4. **Operating Efficiency**:
   - **2021**: Operating costs were more than double the income.
   - **2022**: Operating costs doubled, indicating that, despite a reduction in total expenses, costs remained too high relative to income.
**Insight**: The worsening operating efficiency highlights an imbalance between revenue generation and operational expenditure. The focus should be on both increasing revenue through strategic initiatives and further reducing unnecessary costs.
5. **Other Income**:
   - In 2021, other income streams (R3.06 billion) played a crucial role in propping up the total income. By 2022, these sources of income had nearly vanished, with only R418 million recorded.
**Insight**: The heavy reliance on non-operational income sources is unsustainable in the long term. SAA needs to strenghten its core business model and rely more on operational revenue to ensure stability.

This deep dive reveals that while SAA made a progress in reducing costs from 2021 to 2022, the overall financial picture remains concerning. To return to profitability, the airline must address its high operating costs, diversify its income sources, and improve operational efficiency. These insights provide a clear direction for SAA's financial recovery and strategic planning moving forward.

## Recommendations
1. **Cost Optimisation**: Further streamline operating expenses, especially in aircraft leasing and maintenance, to align with the reduced revenue stream.
2. **Revenue Diversification**: Explore new income opportunities beyond traditional airline operations.
3. **Operational Efficiency**: Implement technology-driven solutions to enhance efficiency in operations and improving cost controls.
4. **Strenghten Revenue**: Focus on strategies to boost airline revenue, such as increased flight activity and targeted marketing to regain market share.


