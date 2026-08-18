# Insurance Cost Analysis 
<img width="825" height="361" alt="Dashboard final" src="https://github.com/user-attachments/assets/db613140-a791-4f23-9a57-5b6ea90e3fce" />

Excel dashboard analyzing 1,338 medical insurance records. Tracks charges by smoking status, BMI bracket, age group, region, and family size. Surfaces the biggest cost drivers to support premium pricing and risk assessment.

Insurance Charges Analysis

Excel Dashboard Report (Pivot Tables)

Executive Summary

Using Excel (data cleaning, bracketing, and pivot tables), I built a dashboard to analyze 1,338 insurance policyholder records. This report identifies the key drivers of medical insurance charges. Key findings show smokers pay nearly 4x more than non-smokers on average, and charges rise sharply with age and BMI. After identifying trends within this dataset, I recommend the following adjustments to improve pricing accuracy and risk management:

1) Apply a stronger smoker surcharge in premium pricing, as smoking is the single largest cost driver
2) Introduce BMI-based risk tiers, since obese policyholders show consistently higher average charges
3) Review regional pricing, as the Southeast region shows the highest average charges across nearly every group

Business Problem
Insurance providers need visibility into which policyholder attributes drive up medical costs so premiums can be priced fairly and risk can be managed effectively. Without this breakdown, pricing models risk under-charging high-risk groups and over-charging low-risk groups.

The key questions

●	Which factors (smoking, BMI, age, region) drive the highest insurance charges?

●	How much more do smokers cost on average compared to non-smokers?

●	Which regions and demographic groups carry the highest average charges?

Methodology

Dataset: Medical Cost Personal Dataset (Kaggle), 1,338 records, 7 core fields (age, sex, BMI, children, smoker, region, charges), covering policyholders aged 18–64.

Excel: Data cleaning, bracketing (Age Brackets: young/middle age/old; BMI Brackets: Normal Weight/Overweight/Obese), data validation, data transformation

Excel Pivot Tables: Built pivot tables and pivot charts to break down average charges by smoker status, sex, age bracket, BMI bracket, and region.

Skills

●	Excel (pivot tables, pivot charts, data bracketing)

●	Data cleaning and transformation

●	Dashboard design (cross-tab pivots, grouped comparisons)

●	Insurance/healthcare cost analysis and KPI definition

Average of Charges	Smoker		
Gender	yes	no	Grand Total
female	30679	8762	12570
male	33042	8100	13975
Grand Total	32050	8441	13279
<img width="455" height="146" alt="image" src="https://github.com/user-attachments/assets/023d1e70-239c-4447-927d-2a67a2781410" />


Results

Dashboard visuals and key metrics:

●	Average charges by smoker status vs. sex (pivot table)

●	Average charges by region, split by smoker status and age bracket (pivot table)

●	Charges by BMI bracket (Normal Weight / Overweight / Obese)

●	Charges by age bracket (young / middle age / old)

●	Policyholder count by region and children count

Key findings:

●	Smokers pay an average of $32,050 in charges vs. $8,441 for non-smokers — nearly 4x higher

●	Charges rise consistently from young to old age brackets across every region

●	Southeast region has the highest average charges overall ($14,735), driven by its smoker population ($34,845 avg)

●	Obese policyholders make up the largest BMI bracket and trend toward higher charges

<img width="1118" height="481" alt="image" src="https://github.com/user-attachments/assets/4c3e94e8-9ae5-483d-924e-30392b476442" />


Business Recommendations
●	Weight smoker status heavily in premium pricing models — it's the single largest cost multiplier
●	Build BMI and age brackets into underwriting to price risk more accurately
●	Investigate Southeast region cost drivers before setting regional premium adjustments

Next Steps
●	Incorporate additional health metrics (blood pressure, pre-existing conditions) for deeper risk modeling
●	Build a predictive model to estimate charges from policyholder attributes
●	Expand analysis to track charges over time as claims data accumulates
