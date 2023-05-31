# Bias-variance trade off on the use of person non-response weights in inequality estimates
Presentation at the Q2022 - Bias-variance trade off on the use of non-response weights in inequality estimates

## Author
:man: Josep Espasa Reig - Data Scientist @ LIS - Cross-National Data  Center in Luxembourg

## Introduction
:wave: Welcome to the repository of my presentation for the [Q2022](https://q2022.stat.gov.lt/lt/) conference in Vilnius!

## Contents
Here you will find a short [summary of the presentation](#summary--tldr) and the [paper in PDF] format.

## Summary / TL;DR:
:question: Should inequality researchers use person-level weights instead of household-level ones if these are available? 

In recent years, some National Statistical Offices have started producing weights at individual-level. Compared to those at household-level, these contain an extra 
adjustment by the non-response propensity of individuals. This adjustment might imply more variance in weights and thus larger Standard Errors for estimates. If the variables used to correct for individual non-response are not associated with those used for inequality analyses, then there wouldn't be any benefit using the individual-level weights.

The paper uses LIS datasets for Germany and US. When using person-level weights (instead of household-level ones):
* Inequality estimates increase slightly
* The gap in the coverage ratio with National Accounts gets reduced
* There is an increase in variance and therefore a reduction in the effective sample size
* The points above are especially true for the last decade of German surveys and for indicators such as the ‘Poverty Gap’ and ‘Poverty Headcount’ 

Researchers should therefore use person-level weights whenever available, as they are most likely reducing bias. They should, however, be aware that this adjustment comes at a cost of decreased precision in estimates.

### Paper in PDF
<object data="https://github.com/JosepER/Q2022_use_nonresponse_weights/blob/main/presentation/person_nonresponse_inequality.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/JosepER/Q2022_use_nonresponse_weights/blob/main/presentation/person_nonresponse_inequality.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/JosepER/Q2022_use_nonresponse_weights/blob/main/presentation/person_nonresponse_inequality.pdf">Download PDF</a>.</p>
    </embed>
</object>
