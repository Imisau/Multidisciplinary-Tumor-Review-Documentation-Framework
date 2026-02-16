# Multidisciplinary-Tumor-Review-Documentation-Framework

![](https://github.com/Imisau/Multidisciplinary-Tumor-Review-Documentation-Framework/blob/main/Screenshot%20(89).png)
### Registry & Health Information Systems Analytics Portfolio
________________________________________
# Project Overview
This portfolio project simulates a hospital-based cancer registry and multidisciplinary tumor board (MDT) documentation system using a 10,000-record oncology dataset. The project demonstrates how registry and health information systems (HIS) teams can use routine tumor board data to monitor data quality, clinical governance, and system performance, in alignment with NAACCR, Commission on Cancer (CoC), and LMIC oncology program standards.
The analysis focuses on system behavior rather than individual clinician performance and applies variance, correlation, and regression analysis only where they meaningfully support operational decision-making.
________________________________________
# Standards Alignment
This project is aligned to the following frameworks:
-	NAACCR: Data completeness, internal consistency, documentation QA, audit readiness
-	Commission on Cancer (CoC): Multidisciplinary tumor board participation, guideline adherence, care coordination
-	LMIC Oncology Programs: Time-to-treatment monitoring, system bottleneck identification, resource-aware analytics
________________________________________
# Dataset Description
-	Records: 10,000 multidisciplinary tumor review cases
-	Cancer Types: Breast, Cervical, Prostate, Lung, Colorectal, Liver, Ovarian
-	Stages: I–IV
-	Key Dimensions:
o	MDT participation by discipline
o	Documentation completeness and QA flags
o	Guideline concordance
o	Time-to-treatment
o	Composite audit risk indicators
________________________________________
Methodology
Data Preparation
•	Excel was used to create rule-based registry indicators, including:
o	MDT participation scores
o	Documentation QA scores
o	Delay risk categories
o	Composite audit readiness scores
Analytical Approach
•	Power BI was used for:
o	Descriptive statistics
o	Variance analysis to identify instability and inconsistency
o	Correlation analysis to assess interdependencies between registry dimensions
o	Exploratory regression analysis to identify predictors of risk and delay
All analyses were conducted at the system level to reflect registry and HIS responsibilities rather than clinician-level performance evaluation.
________________________________________
Key Findings & Interpretation
1. Multidisciplinary Tumor Board Participation
(CoC Governance Indicator)
•	Average MDT participation score was approximately 78%
•	Full MDT participation occurred in about 53% of cases
•	The highest variability was observed in surgical and radiation oncology inputs
Correlation analysis demonstrated a moderate positive relationship between MDT participation and documented clinical consensus.
Registry interpretation:
Inconsistent MDT documentation represents a governance and data quality risk, not merely a clinical workflow issue. MDT participation is a measurable registry performance indicator under CoC standards.
________________________________________
2. Documentation Quality & QA Performance
(NAACCR Data Quality Standard)
•	Mean documentation QA score was approximately 76%
•	Critical documentation issues were identified in about 8% of records
•	Variability increased significantly in:
o	Advanced-stage disease
o	Combined modality treatment plans
Regression analysis identified documentation QA score as a strong predictor of audit outcome, with lower scores disproportionately increasing audit risk.
Registry interpretation:
Documentation risk clusters around case complexity, indicating the need for risk-based QA strategies rather than uniform sampling.
________________________________________
3. Guideline Adherence & Clinical Context
(CoC & LMIC Standards)
•	Overall guideline concordance was approximately 77%
•	Early-stage cases demonstrated higher adherence than late-stage cases
•	Disease stage emerged as a statistically meaningful predictor of non-concordance
Correlation analysis showed that higher MDT participation was associated with improved guideline documentation.
Registry interpretation:
Lower concordance in advanced disease reflects legitimate clinical deviation and resource constraints. The registry’s role is to capture rationale, not to enforce rigid adherence.
________________________________________
4. Time-to-Treatment Performance
(LMIC System Efficiency Indicator)
•	Median time-to-treatment was approximately 36 days
•	Critical delays (>60 days) occurred in about 13% of cases
•	Variability increased with:
o	MDT incompleteness
o	Documentation risk
o	Treatment complexity
Regression analysis showed MDT participation and documentation quality to be significant predictors of treatment timeliness.
Registry interpretation:
Treatment delays are primarily system coordination failures, aligning with LMIC oncology system challenges related to information flow and resource availability.
________________________________________
5. Composite QA & Audit Readiness
(NAACCR & CoC Continuous Quality Improvement)
•	Audit pass rate was approximately 70%
•	Review-required cases represented about 22%
•	Critical audit risk was identified in about 8% of records
Composite QA scores demonstrated strong relationships with MDT completeness, documentation quality, and delay risk.
Registry interpretation:
Quality dimensions are interdependent. Improvements in documentation and MDT participation reduce delay risk and strengthen audit outcomes simultaneously.
________________________________________
Limitations
•	The dataset is simulated and may not capture all real-world clinical nuances
•	Regression analyses are exploratory and not intended for causal inference
•	Patient socioeconomic factors and facility-level resource constraints were not explicitly modeled
These limitations reflect common constraints in real-world registry and HIS analytics and are acknowledged to avoid over-interpretation.
________________________________________
Conclusion
This project demonstrates how cancer registries and HIS teams can use routine MDT documentation data to:
•	Identify predictable quality risks
•	Monitor system performance
•	Support accreditation and audit readiness
•	Improve care coordination and governance
By applying variance, correlation, and regression thoughtfully, the registry becomes an active system improvement function, not a passive data repository.


