# Loan-Analysis-Report-Visualization
Visualize loan analytic model, reference for more advance pre-approve model / Loan Data Analysis


Data Summary

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Purpose to analyze these Data.

Consider you are one the investor or Board member of this financial institution. This report serves as an internal tool for reviewing the bank’s performance from 2009 to 2014. the main purpose is to find out the core aspect of business performance. like the various performance of different occupations, regions or groups. so it can better allocate or optimize company's resource to boost performance. This report also reviewing the macro performance trend, company profit trend, they dynamic impact of various performance indicators. hope it help decision maker to better understand the real market situation, provides a reference to improve or adjust the loan service.

What are the main factors/features of interest in this dataset ? The purpose of the report has two focus First: The bank needs a pre-approve model to determine whether the application will fall in 'bad loan' category, what is the potential return from this loan. Hope this report can provide a basic reference for this pre-approve system no matter from the model or basic data analysis Second: I hope this report can be used as a reference for periodic business summary, to review business situation from a macro or micro perspective, and find out the factors that affect the business (where, who, when, what), so the management can adjust the in time. Because my report will be focus on how to improve the bank performance, so i will use more performance related feature inhere are the questions i try to find out from the report my anasis. here are the questions i try to find out from the report :

What factors affect the estimate return,
What factors caused the bad loan.
Selecting Data

I choose the following data for analyze because I believe they are significant and relevant to the report. .CREDIT GRADE .TERM .LOAN STATUS .ESTIMATEDLOSS .ESTIMATERETURN .EMPLOYMENTSTATUS .CREDITSCORERANGLOWER .CREDITSCORERANGEUPPER .CURRENTDELINQUENCIES .PUBLICRECORDSLAST12MONTHS .DEBTTOINCOMERATIO .INCOMRANGE .STATEDMONTHLYINCOME .LOANORIGINALAMOUNT

Steps of Analysis

• Preliminary Wrangling/Data Cleaning • Bivariate Exploration • Multivariate Exploration • Observation & thought • Reference

As I mentioned before there are two major purpose I studying this dataset, find the correlation causing default and charge off loans, find out the features (who,where,when,what) affects the estimate return. Here are the key words for most of the loans (CA, Current, Term 36, Income 50000− 50000 − 74999, 2013, Q2,Q3. ProsperRating(C,D), Occupation: Other) Answer(When)2013 is the turning point for loan business, the loan listing amount skyrocketing, the major listing Loan (current, complete) go up dramatically ; Q2 and Q3 are more busy quarter compare to q1 and q4 by average. Answer(Who & Where)Customer’s Job title(who), Which state they living(where) does not affecting their loan status or estimate income. Answering(What) By average speaking, Bad loan has higher average estimate income than Good Loan. (what). Correlation: Income/APR(higher income, lower APR)； Apr/Estimate Return( High APR,Higher Return) ； Term/Return (Longer Term, Higher Return). Estimate Income ( lower income, higher estimate return, who is your occupation or when you live doesn’t matter)‘income' and 'APR' are the factors that affect the loan status, most declines loan has lower monthly income and higher APR compare to not declines loan, when Prosper Score is between range 2-6 and income are close or below 4k, there is high probability declines loan will happen. Higher Income and Lower APR, more chance not lead to charge off and default loan.

Key Insights for Presentation: There is contradiction between avoids bad loan and maximize estimate return. Because the bad loan has higher estimate average income 0.12 than good loan 0.09. and other plots are verify my finding. I guess the reason is bank charge more fee or interest for those high APR and low-income customer in order to cover the potential bad loan lost, that causing the bad loan average estimate return higher than good loan. But that doesn’t mean we don’t avoid bad loan, because if bank not handle charge/default loans properly, it will turn to lost, even though estimate return is higher but actually return are badly hurt because the bank spend more resource to handing the loan.
