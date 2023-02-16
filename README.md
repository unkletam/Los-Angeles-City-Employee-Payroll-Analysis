# Los-Angeles-City-Employee-Payroll-Analysis
Analyzing Los Angeles City Employee Payroll Data Using R

# Introduction & Problem Statement

The "City Employee Payroll" dataset provides a comprehensive overview of the financial status of Los Angeles City Employees, including the three proprietary departments: Water and Power, Airports, and Harbor. This data was updated bi-weekly by the Los Angeles City Controller's Office and contains valuable information about employee payroll and benefits. This report focuses specifically on the total payments made to Los Angeles City Employees. The data covers the years between 2013 and 2018 and provides an in-depth analysis of the total payments made to employees in each city department, including the three proprietary departments.
![fig1a](https://github.com/unkletam/Los-Angeles-City-Employee-Payroll-Analysis/blob/main/png_assets/Hero_Illustration.png)
The aim of this report is to gain insights into the total payments made to Los Angeles City Employees and to compare the total payments made across different city departments. This report will provide valuable insights into the financial situation of each city department and its employees, helping researchers, policymakers, and anyone interested in the topic to gain a deeper understanding of the total payments made to Los Angeles City Employees.

--------------------------
# Section 1: Insights into Budget Allocation and Departmental Payouts
![fig1a](https://github.com/unkletam/Los-Angeles-City-Employee-Payroll-Analysis/blob/main/png_assets/1A.png)
### Question 1 - Which city departments have the highest volume of payouts in LA?

### Insight -
The treemap (Fig1A) provides a visual representation of the city departments with the highest payroll. The departments listed, such as the Public Accountability Department, Fire Department, City Attorney Department, and Water and Power Department, are just some of the departments that have a significant payroll output.

Additionally, the treemap shows that the volume of payouts in most Council districts is similar, indicating a balanced allocation of resources among the various council districts.

### Question 2 - How much do departments pay their top employees ?


### Insight - 

The data from the "City Employee Payroll" dataset provides intriguing insights (Fig 1B) into the payroll distribution among Los Angeles City Employees. Surprisingly, the top three highest-paying professions are found within the Harbour Department, despite the overall payroll budget being lower compared to other departments such as Fire, Police, and Airport.

Upon further analysis, the data suggests that the payroll budget of the Harbour Department is skewed towards higher-paying positions. This finding may be explained by the ratio of jobs to the department, indicating that the Harbour Department has fewer employees relative to other departments.

### Question 3 - What are the employee benefits provided by city council ? How have they changed throughout the years?

### Insights -

Fig 1C shows that the City Council allocates a significant portion of its payroll budget towards healthcare benefits, while comparatively less is allocated to other benefits.Also, it is important to note that this bias has seen incremental growth throughout the years where healthcare benefits have increased while rest of the benefits are stagnant. This allocation reflects the City Council's recognition of the high healthcare costs in California and the importance of providing adequate healthcare benefits to its employees.

However, this allocation also highlights the broader issue of the need for improvement in the healthcare industry in the United States. Compared to a developing country like India, the life insurance benefit to overall compensation ratio for city council employees in Los Angeles is low. This comparison highlights the need for the healthcare industry to improve, not only in the United States but globally.

### Question 4 - How are payroll resources allocated to bonus payments ? Does city council favor a particular type of bonus?


### Insights -

Permanent bonus pay, longevity bonus pay, and temporary bonus pay are all forms of additional compensation that an employee may receive on top of their base salary.

- Permanent bonus pay: A permanent bonus is a recurring or ongoing bonus that is built into an employee's base salary or compensation package. It's usually a set amount of money that an employee can expect to receive on a regular basis as long as they remain employed with the company.

- Longevity bonus pay: A longevity bonus is a type of bonus that is paid to an employee as a reward for reaching a certain length of service or tenure with a company. Longevity bonuses are often paid out annually and increase as the employee's length of service increases.

- Temporary bonus pay: A temporary bonus is a one-time payment that an employee may receive in addition to their regular pay. Temporary bonuses can be awarded for a variety of reasons, such as meeting a performance goal, completing a special project, or as a holiday or seasonal bonus. Unlike permanent bonuses, temporary bonuses are not a regular part of an employee's compensation package and are not expected to be received on an ongoing basis.

According to the data presented in Figure 1D, a significant portion of payroll allocation is dedicated to permanent bonuses. Meanwhile, the allocation for longevity and temporary bonuses is roughly equal among city departments. While it is beneficial for employees to receive a high permanent bonus, it is also crucial for city council departments to pay attention to longevity bonuses, especially considering that the rate of attrition has increased in recent times. This could negatively impact a company's growth if not properly addressed.

### Question 5 - What percent of the employment is part time in the top 10 part time offering departments?

### Insight -

A closer examination of Figure 1E reveals that while the Recreation and Parks Department might initially seem to have the largest representation of part-time positions, it is noteworthy that the City Clerk and Los Angeles Convention Center are equally competitive in this regard, both offering ample opportunities for individuals looking to pursue a part-time career path. With over 75% of part-time positions available, these departments present a viable option for job seekers seeking a balanced work-life setup. Thus, it is important to consider all three departments when exploring part-time job opportunities in the city.


----------------------------------------
# Section 2: Are Employees Being Paid Fairly?

### Question 1 - Is the yearly payroll increment enough?

### Insight -

The parallel coordinate chart in Figure 2A shows that city council employees have received substantial increases in their total salary. This is significant because it indicates that their actual income has managed to outpace inflation from the beginning.

For example, if an employee started with a salary of \$100,000 in 2013, by 2018 they would need to earn \$108,000 just to keep pace with inflation. In other words, the value of \$1000 in 2013 would have decreased to approximately $910 in present day. However, the chart demonstrates that the salary of city council employees has grown to an extent that they have effectively "beaten" inflation and maintained their purchasing power.

### Question 2 - Is the paygap between top 10% earners and bottom 10% earners getting closer?

### Insight -

The Lollipop chart in Figure 2B shows that the pay gap between the top 10% highest earning employees and the bottom 10% lowest earning employees has slightly improved from 2013 to 2018.

It is important to note that reducing the pay gap between top and bottom earners is crucial for several reasons. Firstly, it helps to promote equality and fairness in the workplace. When the pay gap is reduced, employees are more likely to feel valued and motivated, which can improve their overall job satisfaction and performance. Secondly, reducing the pay gap can have positive impacts on the wider economy and society. When lower earning employees have more disposable income, they are able to contribute more to the economy through spending on goods and services, which can stimulate economic growth and create jobs. Finally, reducing the pay gap is important for addressing issues of income inequality and poverty. When the pay gap is reduced, lower earning employees are better able to support themselves and their families, and have more financial security and stability.

Overall, while the marginal improvement shown in the Lollipop chart is a step in the right direction, continued efforts to reduce the pay gap between top and bottom earners are important for promoting equality, fairness, and economic growth.

-----------------------------------------------
# Section 3: Addressing Controversies Using Statistics

### Question 1 - Is Temporary Bonus Pay more likely to be received by Police Officer-II employees?

### Insight -

We conducted one sample t-test where the hypothesis are as follow:

- Null Hypothesis -> H0 : mu = pop_mean
- Alternate Hypothesis -> Ha: mu > pop_mean
- Confidence Level - 95%

According to the results of the t-test shown in Figure 3A, we observed that the sample mean is greater than the population mean, with a p-value of 0.5. However this won't allow us to reject the null hypothesis and conclude that Police Officer II employees are more likely to receive a Temporary Bonus compared to other employees in both the same and different departments. There isn't enough data to support alternate hypothesis.

### Question 2 - Was the data justified in supporting the statement that Recreation and Parks Department Employees were denied Longevity Bonus Pay in 2014?

### Insight -

We conducted one sample t-test where the hypothesis are as follow:

- Null Hypothesis -> H0 : mu = pop_mean
- Alternate Hypothesis -> Ha: mu < pop_mean
- Confidence Level - 95%

The results of the t-test displayed in Figure 3B revealed that the sample mean was lower than the population mean, with a p-value of 0.99. This supports the acceptance of the null hypothesis and suggests that employees in the Recreation and Parks Department received similar Longevity Bonus Pay. Though we can still agree that, on average, Recreation and Parks Department employees are paid marginally less compared to population mean.


# Conclusion :

The data analysis of the city's budget allocation and departmental payouts provides a comprehensive understanding of the allocation of resources within Los Angeles. Through the use of treemaps, parallel coordinate charts, and t-tests, the study sheds light on some of the key findings related to employee compensation and benefits.

This analysis of budget allocation, departmental payouts, and employee compensation can be beneficial in several ways. Firstly, it provides an in-depth understanding of the distribution of payroll among different departments and council districts. This information can be useful for stakeholders, such as taxpayers, who want to understand where their money is going and if it is being used efficiently. Secondly, the insights into employee compensation can help individuals assess the fairness of pay and determine if they are being paid equitably in comparison to their peers. The findings on the growth of salaries and reduction of the pay gap between top and bottom earners can provide a positive outlook on the current state of employee compensation and serve as a motivation for continued efforts to promote equality and fairness. Finally, the statistical analysis on controversial topics like Temporary and Longevity Bonus Pay can provide valuable insights into the allocation of bonuses and help address any discrepancies that may exist. These findings can be useful in addressing any workplace issues and promoting equitable treatment of employees.

In conclusion, this data analysis provides valuable insights into the allocation of resources and employee compensation within Los Angeles City Council. Further analysis and efforts to address the issues highlighted in the study would lead to a more equitable and efficient allocation of resources and promote fair treatment of employees.

# References :

- https://controllerdata.lacity.org/Payroll/City-Employee-Payroll-2013-2018-/pazn-qyym
- https://www.in2013dollars.com/us/inflation/2013?amount=1#:~:text=The%20dollar%20had%20an%20average,Labor%20Statistics%20consumer%20price%20index.
- https://www.officialdata.org/articles/consumer-price-index-since-1913/





























