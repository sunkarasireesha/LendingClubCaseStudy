# Project Title: Lending Club Case Study
> Project Description: 
 This project aims to analyze loan default data to identify patterns and factors influencing whether a borrower is likely to default on their loan. By employing exploratory data analysis (EDA) techniques, we can derive insights that help a consumer finance company make informed lending decisions, thereby minimizing credit loss. The dataset contains information about past loan applicants and their repayment statuses, enabling us to distinguish between applicants who defaulted on their loans and those who did not.

## Table of Contents
 * [Objectives](#objectives)
 * [Data Source](#data-source)
 * [Methodology](#methodology)
 * [Key Insights](#key-insights)
 * [Technologies Used](#technologies-used)
 * [Files Included](#files-included)
 * [How to Run the Project](#how-to-run-the-project)
 * [Conclusion](#conclusion)
 * [Contact](#contact)
  
## Objectives
- Understand the driving factors behind loan default.
- Identify high-risk loan applicants to reduce potential credit loss.
- Develop a set of insights that can assist in loan approval decisions.

## Data Source
  - The dataset includes comprehensive loan information from 2007 to 2011. It contains various applicant and loan attributes that can influence the likelihood of default.

## Methodology
  - Data Loading and Cleaning: Load the dataset, handle missing values, and preprocess categorical variables.
  - Univariate Analysis: Examine individual attributes to understand their distribution and general characteristics.
  - Bivariate Analysis: Explore relationships between applicant attributes and loan default rates, using visualizations to highlight correlations.
  - Visualization: Create plots to illustrate key findings from the analysis.
  - Conclusion and Recommendations: Summarize insights and provide recommendations for improving loan approval processes.

## Key Insights
  - Around 14.6% of borrowers have defaulted on their loans.
  - Most borrowers take loans for debt consolidation, credit card repayment, and car purchases, with debt consolidation being the most common purpose.
  - The loan amount distribution is right-skewed, peaking in the $5,000-$10,000 range, indicating that this is the most common loan amount.
  - Annual income distribution is also right-skewed, with the highest frequency in the $40,000-$60,000 range, representing the most common annual income.
  - Borrowers with higher annual incomes are more likely to fully repay their loans, while those with lower incomes tend to default.
  - Certain loan purposes, like Small Business and Debt Consolidation, are linked to higher average annual incomes, whereas Credit Card and Car loans are associated with lower incomes.
  - Default rates vary by loan purpose, with Small Business and Wedding loans showing higher default rates; loans for Small Business, Debt Consolidation, and Home Improvement also exhibit higher default risks.
  - Borrowers with a mortgage are more likely to fully repay their loans compared to renters, who are generally more prone to default.
  - Larger loan amounts are associated with a higher likelihood of charge-offs.
  - Borrowers with higher incomes are more likely to repay their loans.

## Technologies Used
   - Python
   - Pandas
   - Matplotlib
   - Seaborn
   - numpy
   - Jupyter Notebook

## Files Included
  - SireeshaSunkara.ipynb Jupyter Notebook containing the analysis, code, and visualizations.
  - SireeshaSunkara.pdf contains detailed explanation.
  - README.md: This README file providing an overview of the project.

## How to Run the Project
   - Clone the repository or download the files.
   - Install the necessary Python packages using pip install -r requirements.txt.
   - Open SireeshaSunkara.ipynb in Jupyter Notebook.
   - Run the cells to view the analysis and results.

## Conclusion
   - Loan status is influenced by a combination of factors, including annual income, loan purpose, and homeownership.
   - Income plays a Significant Role: Borrowers with higher incomes are more likely to repay their loans on time.
   - Loan Purpose Matters: The type of loan can also affect repayment outcomes. Loans for Small Business and Wedding are associated with higher risk.
   - Loan Amount : Borrowers with larger loan amounts are more likely to be charged off.
   - Homeownership is a Positive Indicator: Being a homeowner, especially with a mortgage, is generally associated with better loan performance.

## Contact
 - Created by [@sunkarasireesha] 
 - feel free to contact us via sunkara.sireesha1@gmail.com , suraj.sunny24@gmail.com
