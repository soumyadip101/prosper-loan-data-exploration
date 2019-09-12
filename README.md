# Prosper Loan Data Exploration
## by Soumyadip Mitra


## Dataset

> The dataset consisted of Borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found in [this](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) link with feature documentation available in [this](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) link.

## Summary of Findings

> In the exploration, I found that the borrower APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decreases with the increase of loan amount. The borrower APR also decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. The relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better. I also found that the borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the increase of borrow term.

> Apart from of the main variables of interest, I found that the number of loans with time shows an increasing trend. There were two steep drops in the number of loans borrowed, one between the year 2008 to 2009 which was the period of The Great Depression and the other at the end of 2012 which lasted for a shorter period of time. Also after further research it was known that the SEC imposed a cease and desist order on Prosper from the end of November 2008 till July 2009, which explains the steep fall in the number of loans issued. Also, the loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term. I also found that borrowers with better ratings have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. There is a interaction between categorical term and Prosper rating features. Proportionally, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers. For loan amount, there is a interaction between term and rating. With better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.


## Key Insights for Presentation

> For the presentation, I focused on features that could affect the borrower APR, which are original loan amount, Prosper rating. I started by showing the distribution of borrower APR and loan amount variable. Then, I showed the relationship between APR vs. loan amount, as well as APR vs. rating. I also investigated the effect of rating on ralationship between APR and loan amount, as well as the effect of rating on relationship between borrower APR and term.

## Resources referred:
- https://seaborn.pydata.org/
- https://matplotlib.org/3.1.0/
- https://github.com/yduan004/

## Details of the files in the project:-
- 'exploration_prosper_loan_data.ipynb' consists of the Exploratory Analysis done with the data
- 'exploration_prosper_loan_data.html' is the HTML version of the Exploratory Analysis done with the data
- 'slide_deck_prosper_loan_data.ipynb' is the code file of the final Explanatory slides
- 'slide_deck_prosper_loan_data.html'  is the HTML version of the final Explanatory slides
- 'slide_deck_prosper_loan_data.slides.html' is the HTML version of the slide deck crated for Explanatory purpose of the data

