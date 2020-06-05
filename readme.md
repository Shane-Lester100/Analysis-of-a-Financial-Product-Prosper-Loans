# Prosper Loans: Analyzing investment data for investment strategy

## File available

- two datasets in csv format, one for prosper loan data and the other for the associated metadata

- an exploratory analysis in a jupyter notebook. This is a raw analysis that is just meant for exploring the data

- an explanatory analysis, made to tell the data story and display the code for the chart generations and data manipulation

- a slidedeck in a pdf file. This is the final product of the analysis: describing the explanatory analysis in a cleaner fashion meant for an audience, using the polished charts throughout the presentation.

- an environmnet.yaml file, to reproduce the environment given a conda installation to be able to run the code

## Dataset

The dataset was provided by Udacity.com, a data analytics investment platform. It is also made available throught the public API for Prosper Loans.

The dataset contains 113937 rows and 81 columns. The metadata is available as well as the original dataset in the sam folder as the document.

## Exploration

First univariate variable were examined for number of investors, loan amounts, types of requests, terms, current status of loans, interest rates, risk scores, income levels/ credit scores/ and locations of borrowers, and distribution of returns.

Next risk scores and estimated returns were explored with locations. No valuable information was found here.

Next time with interest rates, aprs, and estimated returns were analyzed together. They followed a clear trend which showed how macroeconomic variables relate to the the true cost to borrowers and true return of the investors. Next statistics were computed and scatterplots were built to describe the relationship of term limits and risk scores to return. Outcomes were a categorical variable. Although they were hard to visualize the story as better told through line graphs

Models were also built that showed statistically significant and practically important results given term limits and prosper score in estimating estimated returns. They only explained 15% of the model, which is expected because calculating estimated risk can get very sophisticated.

## Explanation

Prosper loans can be viewed as a loan for borrowers or as a financial asset for investors. The data story first built a profile of the borrowers. It was found that they are typical middle income Americans with good credit that typically use these loans for debt consolidation.

Then we examined Prosper Loans as a financial assets. We examined Prosper Score risk ratings and term limits as predictive metrics for estimtated returns. We then analyzed the historical trends to build a framework on how to think about and invest in Prosper Loans in a predictiable and replicable way.

Lastly limitations were addressed. The main limitations were that averages were used, which although a good metric for the distributions in our dataset still is only a measure of center. An additional limitation was that the metrics on our framework only account for 15% of the predictive behavior in our model estimating estimated returns. This was addressed although it is to be expected: calculating estimated returns can be have very sophisticated modeling. But because the purposes of this analysis was to build a basic framework, this limitation isn't very important. The fact that our results are statistically significant and practically important is good enough for our use case.