SOMALIA LABOUR MARKET
Data Analysis Report
Somali Labour Force Survey 2019



A portfolio case study covering data preparation, weighted labour-market indicators,
exploratory analysis, DAX measures, and an interactive Power BI report.

Dataset	Somali Labour Force Survey 2019
Analytical records	27,411 respondents
Primary tools	Microsoft Excel, Power Query, Power BI, DAX
Final deliverable	Five-page interactive Power BI report with Executive Summary
Prepared as a professional data analytics portfolio project
 
1. Project Overview
This project analyzes the Somali Labour Force Survey 2019 to examine key labour-market conditions in Somalia. The analysis focuses on labour-force participation, employment, unemployment, demographic inequalities, employment structure, and youth labour-market outcomes.
The original survey contains 27,411 respondents and 101 variables. A focused analytical dataset was prepared using selected labour-market and demographic variables. The official survey weight was incorporated so that the principal indicators represent weighted population estimates rather than only raw sample counts.
The project covers the full analytical workflow: data checking and cleaning, exploratory analysis, indicator calculation, visualization, and development of an interactive Power BI report. The final report contains five pages: Executive Summary, Labour Market Overview, Demographics & Inequality, Employment Structure, and Youth Labour Market.
2. Project Objectives
•	Measure the Labour Force Participation Rate (LFPR), Employment-to-Population Ratio, and Unemployment Rate using appropriate survey weights and denominators.
•	Examine differences in labour-market outcomes by sex, age group, geography, and education level.
•	Analyze employment structure, including formal versus informal employment, public versus private employment, economic activity, and occupation.
•	Examine labour-market outcomes for young people aged 15-24, including youth unemployment and labour-force status.
•	Identify important labour-market inequalities and patterns for evidence-based discussion and decision-making.
•	Build a professional, interactive Power BI report that communicates findings clearly to technical and non-technical audiences.
3. Dataset and Analytical Scope
The analysis uses respondent-level data from the Somali Labour Force Survey 2019. The working dataset contains 27,411 valid respondent records. Twenty-seven selected demographic and labour-market variables formed the core analytical extract, and the official sample weight was reattached from the original survey file through an exact respondent-ID match.
All 27,411 respondent IDs matched one-to-one when the survey weight was restored. Numeric source codes were preserved, while readable label fields were added for verified categorical variables to support clear reporting in Power BI.
4. Data Quality and Preparation
Duplicate and row validation: No duplicate respondent IDs or completely duplicated respondent records were found. An apparent extra record was traced to an Excel Total Row containing SUBTOTAL formulas; it was excluded from the analytical data while valid respondent ID 27411 was retained.
Structural missingness: Blank values were not automatically treated as errors. Labour-force variables are structurally blank for respondents under age 15, while many job-characteristic fields apply only to employed respondents.
Sparse working-hours fields: Usual Working Hours and Actual Working Hours were retained without imputation. Actual Working Hours is particularly sparse and is therefore interpreted cautiously.
Category handling: Verified survey categories were preserved. For example, Education Level 'Level not stated' was retained as a legitimate category rather than recoded as missing.
NEET coding: NEET Status was treated cautiously because only positive cases were explicitly coded in the selected extract; blank records were not recoded to 'No'.
5. Methodology and Key Measures
The main labour-market indicators were calculated as weighted descriptive estimates. The denominators were selected according to the definition of each indicator rather than using all survey respondents.
Indicator	Definition used
Labour Force Participation Rate (LFPR)	Weighted Labour Force / Weighted Working-Age Population
Employment-to-Population Ratio	Weighted Employed / Weighted Working-Age Population
Unemployment Rate	Weighted Unemployed / Weighted Labour Force
Weighted results are point estimates. Complex-survey standard errors and confidence intervals were not calculated, so the report emphasizes descriptive patterns rather than statistical inference.
6. Power BI Report Structure
Executive Summary — A single-page management view of the most important indicators and findings.
Labour Market Overview — Headline KPIs, labour-force status, and comparisons by sex and geography.
Demographics & Inequality — Labour-market rates by age group and education, with demographic slicers.
Employment Structure — Formality, institutional sector, economic activity, and occupation among employed respondents.
Youth Labour Market — Youth unemployment and labour-force status for people aged 15-24, including sex and geography comparisons.
7. Key Findings
32.4%	Weighted Labour Force Participation Rate
25.5%	Weighted Employment-to-Population Ratio
21.4%	Weighted Unemployment Rate
37.4%	Youth unemployment rate for ages 15-24
45.9% vs 20.3%	Male versus female LFPR, a gap of about 25.6 percentage points
38.4% vs 31.2%	Rural versus urban LFPR
81.1%	Informal main-job share among employed people with a valid formality category
50.9%	Employment-to-population ratio for respondents with advanced education
8. Limitations
•	The analysis is descriptive and should not be interpreted as establishing causal relationships.
•	Complex survey-design standard errors and confidence intervals were not calculated.
•	Some variables contain structural or survey-routing blanks and should not be interpreted as ordinary missing data.
•	Actual Working Hours contains relatively few nonblank observations and should be used cautiously.
•	NEET Status was not converted into a complete Yes/No indicator because the selected extract explicitly codes only positive cases.
9. Conclusion
The analysis indicates a labour market characterized by relatively low overall participation, a large gender participation gap, high youth unemployment, and a strong concentration of employment in informal work. The dashboard also shows meaningful variation by geography, age, and education. These findings demonstrate the value of combining careful survey-data preparation with weighted indicators and interactive visualization to communicate labour-market conditions clearly.
10. Tools and Deliverables
Microsoft Excel: Initial review and workbook organization
Power Query: Data transformation and preparation
Power BI: Data modeling, interactive visualization, and report design
DAX: Weighted population and labour-market measures

End of Report
