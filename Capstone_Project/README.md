### Introduction 

**Employee turnover**, or **staff turnover**, is a measurement of how many employees are leaving a company. It’s a way to track whether a company has more employees leaving than is typically expected. This includes employees that either quit, were let go, or retired. However, companies that measure their employee turnover often separate these to manage each type of turnover.

It is very costly for organizations, where costs include but not limited to: separation, vacancy, recruitment, training and replacement. On average, organizations invest between four weeks and three months training new employees. This investment would be a loss for the company if the new employee decided to leave the first year. Furthermore, we can also factor the cost of hiring for that position, any severance or bonus packages, and managing the role when it is not filled.  Organizations such as consulting firms would suffer from deterioration in customer satisfaction due to regular changes in Account Reps and/or consultants that would lead to loss of businesses with clients.  

Thus, every organization should strive to retain their employees for as long as possible. If they see a uptick in employee turnover, then they should take action to reduce turnover and improve retention. This results in more efficient operations, higher morale, and higher profits.

--- 

## The Data
In this notebook we will use a simulated HR data from [kaggle](https://www.kaggle.com/liujiaqi/hr-comma-sepcsv) to build a classifier that helps us predict what kind of employees would likely to leave based on given attributes.  These classifiers will help an organization predict employee turnover and will enable them to become pro-active in helping to address this ongoing problem.

The data has 14,999 examples (samples). Below are the features and the definitions of each one:
- **satisfaction_level**: Level of satisfaction {0-1}.
- **last_evaluationTime**: Time since last performance evaluation (in years).
- **number_project**: Number of projects completed while at work.
- **average_montly_hours**: Average monthly hours at workplace.
- **time_spend_company**: Number of years spent in the company.
- **Work_accident**: Whether the employee had a workplace accident.
- **left**: Whether the employee left the workplace or not {0, 1}.
- **promotion_last_5years**: Whether the employee was promoted in the last five years.
- **sales**: Department the employee works for.
- **salary**: Relative level of salary {low, medium, high}.

Let's first load all the packages.

---

## Objectives


- To be able to accurately predict employee turnover 
- To determine what are the features that best predict turnover.

---

