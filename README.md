# KPI Scorecard Analysis

## Background and Overview

This project analyzes the relationship between **employee performance** (measured through **Error Rates**) and **Customer Satisfaction (CSAT)** across various teams, age groups, tenures, and shifts within a company. By applying data analysis techniques, the goal is to uncover insights that can improve operational efficiency and customer experience, providing actionable recommendations to optimize employee performance and customer satisfaction.

The focus is on key performance metrics across different dimensions, such as team leads, shifts, age groups, and employee tenures. This analysis allows us to identify patterns and correlations between operational efficiency and customer satisfaction, enabling informed decisions for process improvements.

## Data Structure Overview

The dataset contains multiple columns, including:

- **Error Rate**: Percentage of operational errors made by employees.
- **CSAT (Customer Satisfaction)**: Percentage representing customer satisfaction scores for each employee.
- **Date**: The date when each performance record was captured.
- **Shift**: Categorizes employees by shift (AM, PM, MID).
- **TeamLead**: The supervisor managing the employee’s team.
- **Age**: Employee’s age.
- **Age Group**: Categorizes employees by age group (21-30, 31-40, etc.).
- **Tenure**: Number of years the employee has been with the company.

This data structure enables us to perform analyses based on different employee characteristics while correlating error rates and CSAT for more comprehensive insights.

## Executive Summary

The analysis revealed several key performance trends across teams, shifts, and age groups. Key takeaways include:

- **Low error rates** are consistently observed across teams, shifts, and age groups, highlighting operational accuracy.
- **CSAT shows wider variability** across these dimensions, suggesting that factors beyond error rates (such as leadership or team structure) may influence customer satisfaction.
- **Certain teams** (e.g., Buckey Barnes’s team) exhibit more performance outliers in both error rate and CSAT, suggesting areas for improvement, while other teams (e.g., Don De Marco’s team) perform more consistently.
- **Age and tenure** have minimal impact on error rates, but CSAT scores vary slightly, particularly for younger and older employees.

## Insights Deep Dive

### Team Lead Performance
- **Buckey Barnes’s team** shows higher error rates and more outliers in both error rates and CSAT. This suggests inconsistent performance within the team.
- **Don De Marco’s** and **Joey Jordison’s teams** have lower error rates and more consistent CSAT scores, indicating stable and reliable performance across these teams.

  ![output_teamperformance](https://github.com/user-attachments/assets/7a4484ef-0ddb-4f54-9d2c-2c2c94d05847)


### Error Trends Over Time
- **Error rates remain stable** over time, with minimal fluctuations, indicating strong operational control. However, **CSAT shows periodic fluctuations**, suggesting that other factors beyond error rate may be influencing customer satisfaction.
- A more detailed investigation into non-operational drivers of CSAT, such as employee engagement and team dynamics, may provide further insights.

  ![output_errorratetrend](https://github.com/user-attachments/assets/ba2fbfd4-daf4-4b48-8609-b9d250f07a09)


### Shift Impact on Performance
- **MID shift** employees tend to have a slightly higher error rate, with more outliers compared to AM and PM shifts. However, **CSAT remains relatively high** across all shifts, showing that even with occasional errors, customers remain satisfied.
- **AM shift** employees show the most consistent performance, with both low error rates and high CSAT scores, making this shift the most reliable in terms of both operational accuracy and customer satisfaction.

  ![output_shiftimpact](https://github.com/user-attachments/assets/46ab7947-9524-407f-a273-968629c7eb39)
  ![output_shiftimpact2](https://github.com/user-attachments/assets/fef5b198-3bea-4536-80c4-2fd3959e61f5)


### Tenure Impact on Performance
- Employees with **4 years of tenure** show the **lowest CSAT**, while those with **5 years of tenure** have the **highest CSAT**, indicating a possible drop in engagement after the 4th year, followed by an improvement.
- **Error rates remain consistently low** across all tenure groups (around 0.02%), highlighting that tenure does not significantly impact error rates but may influence customer satisfaction.

  ![output_tenureperformance](https://github.com/user-attachments/assets/9ef064cc-4413-41fe-b4e6-2d4a25f56412)


### Age Group vs Performance
- Employees in the **21-30** and **61-65** age groups show slightly lower CSAT scores compared to other age groups, although **error rates remain consistently low**. This suggests that factors other than operational performance, such as training or customer interaction skills, may impact satisfaction for these age groups.
- Overall, **error rates remain stable** across all age groups, reinforcing that age is not a strong determinant of operational accuracy.

  ![output_ageperformance](https://github.com/user-attachments/assets/f4e7d1b3-2c03-461a-bf3a-2cf6b24e346b)


### Error Rate & CSAT Correlation by Team Lead
- The scatter plot reveals **no strong correlation between Error Rate and CSAT**, indicating that lower error rates do not necessarily lead to higher customer satisfaction. This suggests that **other factors**, such as team dynamics or employee engagement, may play a more critical role in driving CSAT.
- **Don De Marco’s and Joey Jordison’s teams** exhibit more consistent performance, with fewer outliers in both metrics.
- **Buckey Barnes’s team** shows a higher number of outliers, with both **higher error rates** and **lower CSAT scores**, suggesting performance inconsistencies that need to be addressed.

  ![output_correlation](https://github.com/user-attachments/assets/180b14b7-be3e-4ad7-8387-3b7123041016)


## Recommendations

1. **Targeted Training for Buckey Barnes’s Team**:
   - Focus on reducing error rates and improving customer interaction strategies within **Buckey Barnes’s team**. Identifying specific challenges and providing additional coaching can help align this team’s performance with the rest of the organization.

2. **Improve MID Shift Performance**:
   - Investigate the reasons behind the higher error rates in the **MID shift**. Consider **re-distributing workloads** or introducing **process improvements** during this shift to reduce errors while maintaining the high CSAT.

3. **Support for Younger and Older Employees**:
   - Provide targeted **training programs** for employees in the **21-30** and **61-65** age groups to help improve customer interactions. These programs should focus on addressing the challenges faced by these age groups in achieving higher CSAT scores.

4. **Leverage Success of Don De Marco & Joey Jordison’s Teams**:
   - The **consistent performance** of these teams can serve as a **benchmark** for others. Sharing best practices from these teams could help improve overall performance across the company.

5. **Enhance Employee Engagement for 4-Year Tenure Group**:
   - The lower CSAT for employees with **4 years of tenure** suggests a possible drop in engagement. Introducing **career development opportunities** or **new incentives** at this tenure stage could help boost employee motivation and, by extension, customer satisfaction.
