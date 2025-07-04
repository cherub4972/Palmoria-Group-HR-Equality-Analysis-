# Palmoria-Group-HR-Equality-Analysis-
Palmoria Group HR Equality Analysis 
An HR analytics report exploring gender disparities, salary equity, and performance fairness across regions.
## Introduction
This report was commissioned to support Palmoria Group’s efforts to address growing concerns around gender inequality, salary gaps, and regulatory compliance. Using employee-level data from internal sources, this report provides an analytical foundation to guide policy reform and HR decision-making.
## Methodology
Data Sources:Palmoria Group emp-data.csv: Employee records including gender, region, department, salary, and ratings
Palmoria Group Bonus Rules.xlsx: Guidelines for allocating bonus payments based on performance
## Tools Used:
Power BI for dashboard design and DAX analysis
## Steps Taken:
1. Cleaned the employee data:
Removed rows with missing salary or undefined departments, Re-coded “Not Disclosed” gender as “Unspecified”
2. Analyzed gender representation, pay distribution, and performance ratings
3. Calculated bonuses using rating-based multipliers
## Analysis & Findings
A. Gender Representation
Males dominate the workforce in nearly all regions and departments
Lowest female representation in Manufacturing, Production, and Operations
Gender-neutral or female-led roles exist mostly in Admin and HR
B. Performance Ratings
Males are disproportionately present in higher performance brackets
Average female ratings hover between 2–3, indicating possible bias or lack of development support
C. Salary Structure
Gender pay gap is evident in at least 5 departments
Average male salaries exceed female salaries by up to $15,000 in some areas
D. Minimum Wage Compliance
A significant number of employees earn below $90,000
Most of these roles are concentrated in regional operations and factory-based units
E. Salary Band Distribution
Majority of employees earn between $70,000–$90,000
Only a small fraction exceed the $150,000 bracket
F. Bonus Allocation
Bonus calculated using the predefined rating tiers (e.g., 25% for 5 stars)
High-performing employees receive significant bonus boosts, further increasing total disparity if ratings are biased
## Interpretation
These results highlight systemic HR issues:
Possible unconscious bias in performance ratings
Gender pay inequity baked into departmental structures
Regulatory compliance issues that expose the company to penalties
Bonus policies that reward top performers but could amplify existing inequities

![Image](https://github.com/cherub4972/Palmoria-Group-HR-Equality-Analysis-/blob/main/power%20bi.jpg)






## Challenges Encountered
During the analysis, the following issues were observed:
a. Missing or Dirty Data
Several employee records had missing salary values or NULL departments
Some gender fields were listed as “Not Disclosed”, which required logical recoding
b. Data Integrity Issues
Duplicate or outdated records (e.g., employees no longer with the company but still listed)
Inconsistent naming conventions for departments and regions
c. Bonus Rule Format
Bonus rules were provided in Excel, not joined with the employee dataset, requiring a merge based on performance score
Manual mapping and cleaning had to be done before applying rules
d. Tool Limitations
File size affected Power BI refresh speed
Calculating bonus payouts in Power BI required DAX workarounds to handle dynamic percentages per rating
e. Ethical Considerations
Reassigning “Not Disclosed” genders introduced a risk of oversimplifying gender identity
Sensitive nature of salary and performance data needed cautious framing
## Conclusion & Recommendations
# Summary:
Palmoria is facing serious equity and compliance challenges.
Bias in rating and pay structures could limit female advancement.
Urgent action is needed to avoid brand damage and potential lawsuits.
# Recommendations:
Launch a gender equality audit across all departments.
Revise performance review methods to eliminate systemic bias.
Enforce the minimum salary rule with immediate effect.
Create clearer, role-specific pay bands to ensure transparency.
Promote female inclusion in technical and leadership roles.
