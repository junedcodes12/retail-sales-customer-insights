# Week 1 Project Plan

## Project title
Retail Sales and Customer Insights Using Python

## Executive summary
This project proposes a practical business analytics solution for understanding retail sales performance and customer purchasing behaviour. Publicly available transaction data will be inspected, cleaned, explored and analysed using Python. The final outputs will include KPI summaries, visualisations and evidence-based recommendations. The project is designed as a structured entry-level analytics workflow and will be extended through the remaining internship tasks.

## Objectives
- Measure revenue, order volume and quantity sold.
- Identify best- and low-performing products and categories.
- Study monthly and seasonal sales patterns.
- Explore customer and regional patterns where suitable fields are available.
- Examine discounts and their relationship with sales where the dataset contains discount information.
- Present findings in clear charts and recommendations.

## Key business questions
1. Which products and categories contribute most to sales?
2. How do sales and order volumes change over time?
3. Which regions or channels perform best, if those fields exist?
4. Which customers or customer groups have the highest purchase value, if customer IDs exist?
5. Which products or categories show weak performance?
6. What actions could improve inventory planning, promotions or customer retention?

## Scope
The project covers data understanding, data-quality checks, cleaning, transformation, exploratory data analysis, KPI calculation and visual reporting. Expected fields may include order date, product, category, quantity, unit price, sales, customer ID and region. Actual analysis will depend on the selected dataset. Production deployment and complex predictive modelling are outside the initial scope.

## Data strategy
Select a public retail transaction dataset from a recognised open-data source such as Kaggle or a university/open-data repository. Record the dataset URL, download date, licence, date range, geography and column definitions. Preserve the original file separately from cleaned outputs. Do not collect or publish private customer information.

## Methodology
1. Acquire a public dataset and document its provenance.
2. Inspect dimensions, data types, summary statistics and missing values.
3. Check missing values, exact duplicates, inconsistent formats, invalid quantities/prices and unusual values.
4. Create derived fields such as sales value (quantity × unit price) and order month when source fields permit.
5. Aggregate and compare product, category, customer, region and time-based performance.
6. Visualise findings using suitable charts.
7. Translate verified findings into practical recommendations and state limitations.

## Tools
- Python: main programming language.
- Pandas: data loading, cleaning, transformation and aggregation.
- NumPy: numerical operations.
- Matplotlib and Seaborn: visualisation.
- Jupyter Notebook / Google Colab: analysis environment.
- GitHub: version control and project documentation.

## Six-week timeline
| Week | Activities | Deliverable |
|---|---|---|
| 1 | Planning, business questions, scope and data strategy | Project plan |
| 2 | Dataset selection, inspection and data-quality assessment | Dataset and data profile |
| 3 | Cleaning and transformation | Cleaned dataset and cleaning notes |
| 4 | EDA and KPI calculations | Notebook and KPI tables |
| 5 | Visualisation and recommendations | Charts and insight summary |
| 6 | Documentation, review and presentation | Final report and repository |

## Expected business impact
The analysis may help a retail decision-maker understand revenue drivers, identify products needing attention and recognise periods of stronger demand. Product and category comparisons may support assortment and inventory decisions. Time trends may help plan promotions and stock levels. Customer analysis, where supported by the data, may identify valuable customer groups. Outcomes are insights and recommendations, not guaranteed business results.

## Risks and mitigation
- Missing/incomplete records: measure missingness and document treatment.
- Duplicates/inconsistent formats: validate key fields and standardise formats.
- Limited coverage: document period/geography and avoid overgeneralisation.
- Outliers: investigate before excluding values.
- Time or setup constraints: use Google Colab and maintain backups.
- Privacy/licensing: use public data, check terms and avoid identifying individuals.

## Evaluation criteria
Clarity of objectives, dataset relevance, cleaning quality, calculation correctness, visualisation suitability, interpretation, feasibility of recommendations and completeness of documentation.

## Conclusion
This plan defines a feasible six-week retail analytics project using Python. It progresses from business questions and data strategy through cleaning, exploratory analysis, visualisation and recommendations. It provides practical experience in Python, Pandas, data preparation, analytical thinking and business communication.
