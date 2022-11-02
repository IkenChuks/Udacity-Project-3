# Prosper LLC Loan Dataset
## by Ikenna Chukwudum


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Prosper Marketplace, Inc. is a San Francisco, California-based company in the peer-to-peer lending industry. Prosper Funding LLC, one of its subsidiaries, operates Prosper.com, a website where individuals can either invest in personal loans or request to borrow money. It covers customer borrowing from 2005 to 2014.

> Wrangling efforts were adopted mostly in the univariate exploration. 'Occupation' types were observed to be ambiguous and so this was gropued out to reduce repetition of very similar job types. For instance, students had to be grouped together from 'sophomore', 'senior', etc so as to reduce noise when plotting and allow for a clearer presentation. Engineers, clergy, and some other values also got similar grouping wrangling. 'Employment status'  and 'loan status' were grouped down as well for clearer understanding of the data and easier analysis. I had to find the log of 'Original loan amount', 'Deliquent amount' and 'Monthly income' due to the high range between the minimum and maximum values an for ease of presentation. Missing values were filled for employment status in order to aid in bivariate and multivariate explorations.


## Summary of Findings

> Focus was put on key variables which directly would impact the company's bottom line. These were 'Original loan amount', 'Borrower rate', 'Loan Status', 'Employment status' and 'Stated Monthly Income'. Exploring the relationships among these variables can assist the company to determine if it is on the right path to ensure profitability and what it needs to change for the future. Occupation variable was also looked at, although to a lesser degree.

> It was observed from my analysis that loan status was affected by borrower interest rate and original loan amount to the extent that higher interes rates were more related to deliquent loans. This was similar with higher loan amounts. Surprising though, loan status was not adversely affected by employment status as unemployed customers had similar default rates with employed customers. This shows that the company closely monitors its loans given to business people who are not necessarily salary earners. 
> Mean loan amounts grew proportionally with interest rate but at a peak of about 0.175 interest rate, the loan amount began to sharply decrease as the interest rate increased. This was true for both employed and unemployed borrowers. Caution should be taken by the lending institution with regards interest rate increase as borrowers seem less inclined to patronize their service the higher the rates are. 
> The occupation variable had a large number of unknown values but some insights could be drawn from the fact that most occupation types took loan amounts of less than 10,000 dollars. It was however observed that higher earning jobs like judge, engineer, dentist, etc tended to have more spread out loan amounts not restricted to 10,000 dollars and occasionally took much more. It must be noted once more that the findings from occupation could be skewed because of the large number of unknown values.

> Summarily, Prosper LLC is a thriving company with a very loan defaulted loan figure irrespective of employer status or occupation or monthly income. This shows a good management team behind the company. They should however be careful not to raise interest rates beyond a certain threshold as there is a high risk of diminishing returns.


## Key Insights for Presentation

> I'll explore borrower interest rate vs loan status, loan status - employment status relationship and a multivariate relationship among original loan amount, borrower rate and employment status.
> Employment status values were narrowed to 'employed' and 'unemployed' for clearer presentations. Mean loan amount was used for the line plot.