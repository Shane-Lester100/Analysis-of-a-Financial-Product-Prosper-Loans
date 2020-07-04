# Analysis of a Financial Product: Prosper Loans

'Prosper Loans' is a technology investment company connecting loan requests directly to investors. Their purpose is to cut out banks as the middleman for loan requests. 

This product analysis focuses on the customer base of requests and historical returns on investment. The purpose is to understand the customer base to know who will be receiving investment money and to look at historical data to see which metrics signify the maximum return with the minimum amount of risk. The final report suggests an investment strategy for choosing the optimal product.

To view the exploratory analysis, [click here](https://nbviewer.jupyter.org/github/Shane-Lester100/Analysis-of-a-Financial-Product-Prosper-Loans/blob/master/Exploratory%20Analysis%20-%20Loans.ipynb).

To view the results as a Jupyter Notebook [click here](https://nbviewer.jupyter.org/github/Shane-Lester100/Analysis-of-a-Financial-Product-Prosper-Loans/blob/master/Explanatory%20Analysis%20Prosper%20Loans.ipynb).

To view the results as a PDF slideshow, [click here](https://github.com/Shane-Lester100/Analysis-of-a-Financial-Product-Prosper-Loans/blob/master/Prosper%20Loans_%20A%20New%20and%20Exciting%20Investment%20Option.pdf). 

Below is a summary of the exploratory and explanatory analysis with its limitations. How to set up the environment to reproduce the results is also below.  Lastly, where the dataset came from is described.


## Exploration

First, the analysis of univariate variable for the number of investors, loan amounts, types of requests, terms, the current status of loans, interest rates, risk scores, income levels/ credit scores/ and locations of borrowers, and distribution of returns occurs.

Next, the analysis of risk scores and estimated returns are associated with location data. No valuable discoveries are here.

We then explore 'Prosper Loans' as a financial product: interest rates, APRs, and estimated returns are analyzed together. They follow a clear trend that shows how macroeconomic variables link the true-cost to borrowers to the true-return of the investor.

Then, statistics are computed with scatterplots to describe the relationship between term limits and risk scores to estimated return. Outcomes were a categorical variable. The story is best through line graphs

Linear models are made that show statistically significant practically-important results given term limits and prosper score in estimating estimated returns. They only explained 15% of the model, which is not surprising because calculating estimated risk can get very sophisticated.

## Explanation
Prosper loans are a loan for borrowers and a financial asset for investors. The data story builds a profile of the borrower. It shows they are typical middle-income Americans with good credit that typically use these loans for debt consolidation.
Then we examine Prosper Loans from the perspective of a financial asset. The analysis shows Prosper Score risk ratings and term limits as predictive metrics for estimated returns. We then analyze the historical trends to build a framework on how to think about and invest in Prosper Loans in a predictable and replicable way.
Lastly, the main limitations are that averages leave out some information and only provide a measure-of-center, which can be misleading. Additionally, the metrics on our framework only account for 15% of the predictive behavior in our model estimating estimated returns. But for this analysis, which is to build a basic framework for investment strategy, this limitation isn't important. The fact that our results are statistically significant and practically important is good enough for our use case.

## Files available

- two datasets in CSV format, one for Prosper Loan data and the other for the associated metadata

- an exploratory analysis in a Jupyter Notebook. This is a raw analysis that is just meant for exploring the data

- an explanatory analysis, made to tell the data story and display the code for the chart generations and data manipulation

- a slide-deck in a pdf file. This is the final product of the analysis: describing the explanatory analysis in a cleaner fashion meant for an audience, using the polished charts throughout the presentation.

- an environment.yaml file, to reproduce the environment given a Conda installation to be able to run the code

## Datasets

The dataset was provided by Udacity.com, a data analytics learning platform. It is also made available through the public API for Prosper Loans.

The dataset contains 113937 rows and 81 columns. The metadata is available as well as the original dataset in the sam folder as the document.
