Memo
- 1.1: in RQ2 all of the predictors had p value 0 (?) so they are all statistically significant, better to say -> "Although GDP per capita and total electricity generation are statistically significant predictors, their efect sizes are modest, in contrast, the share of fossil fuels in the power mix is both statistically and practically significant, showing the largest influence on whether a countrexceeds 50% renewable electricity."
- 1.6.4 bottom of ROC plot analysis is cut off

Technical Appendix
- 2.2.1 RQ1: specify in model that i=country, t=time
    - Add summary table for estimates, errors, Cl's, p Vals (included in memo too but required for appendix)
    - Add short section explaining that we initially modeled without log transforming GDP but had weaker diagnostic plots andwith EDA observations, decided to use log GDP (see RQ1 qmd for reference of this done)
- 2.2.2 RQ2: in the table of the model summary, can you display more precision for p value so it doesn't look completely 0 ifpossible?
- Mention possible confounders for models?
- 2.2.2.1: Diagnostics: change this sentence to not sounds chatgpt lol from "your" to "our" -> "All Cook's distances are essentially near zero and well below 1, which means no observation has unusually large infuence on the logistic model-this matches what we observed in our plot"