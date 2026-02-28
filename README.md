# NYC-Market-Value

## Context
The relationship between certain condominium characteristics and the average full market value of condominiums in New York City is in question.

## Objectives
To determine if and how variability in full market values of New York City condominiums is explained by differences in condominium-related characteristics such as Gross Square Feet, Gross Income per Square Feet, and Estimated Expense.

## Design and Setting
The NYC Department of Finance provides a data set relating to 31,600 condos, including their Full Market Value and characteristics at a condominium suffix level, all reported from 2012-2018 and publicly available on NYC Open Data Records. A subset of the original data was used for this report, which contains a random sample of 200 condominiums in NYC along with a subset of the originally listed characteristics.


## Main Outcome Measures
A multiple linear regression model of Log Full Market Value was constructed considering the following condominium characteristics: Total Units, Year Built, Gross Square Feet, Estimated Gross Income, Gross Income per Square Foot, Estimated Expense, Expense per Square Foot, Net Operating Income, Report Year, and Market Value per Square Foot.


## Results
The derived multiple linear regression model demonstrates strong statistical significance for both predictors, with Log Gross Square Feet having a coefficient value of 0.9606 (95% CI, 0.9407-0.9796) and Gross Income per Square Foot having a coefficient value of 0.0401 (95% CI, 0.0375-0.0429).


## Conclusion
The analysis highlights that the Log Gross Square Feet of the building and Gross Income per Square Foot are strong predictors of the full market value of NYC condominiums.




