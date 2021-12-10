# TEACHING-METHODOLOGY-EFFECTIVENESS-USING-ANOVA

# TO DETERMINE WHETHER OR NOT ALL THE THREE METHODS OF TEACHING THAT IS --> BLACKBOARD,CASE STUDY, POWEPIONT PRESENTATION IS SAMELY  EFFECTIVE OR 
# DIFFERS FROM EACH OTHER. AND EACH METHOD YIELDS DIFFERENT PERFORMANCE /RESULT OF STUDENT.


ABOUT THE LIBRARIES USED:
1. pandas.melt

    pandas.melt(frame, id_vars=None, value_vars=None, var_name=None, value_name='value', col_level=None, ignore_index=True)
    Unpivot a DataFrame from wide to long format, optionally leaving identifiers set.

    This function is useful to massage a DataFrame into a format where one or more columns are identifier variables (id_vars), while all 
    other columns, considered measured variables (value_vars), are “unpivoted” to the row axis, leaving just two non-identifier columns, ‘variable’ and ‘value’.
    
2. ANOVA and OLS regression are mathematically identical in cases where your predictors are categorical (in terms of the inferences you are drawing 
from the test statistic). To put it another way, ANOVA is a special case of regression. There is nothing that an ANOVA can tell you that regression 
cannot derive itself. The opposite, however, is not true. ANOVA cannot be used for analysis with continuous variables. 
As such, ANOVA could be classified as the more limited technique. Regression, however, is not always as handy for the less sophisticated analyst. 
For example, most ANOVA scripts automatically generate interaction terms, where as with regression you often must manually compute those
terms yourself using the software. The widespread use of ANOVA is partly a relic of statistical analysis before the use of more powerful statistical
software, and, in my opinion, an easier technique to teach to inexperienced students whose goal is a relatively surface level understanding 
that will enable them to analyze data with a basic statistical package. Try it out sometime...Examine the t statistic that a basic regression spits out,
square it, and then compare it to the F ratio from the ANOVA on the same data. Identical!


3. The Ordinary Least Squares (OLS) regression or model technique falls under the Supervised Learning. It is a method for estimating the unknown parameters by 
creating a model which will minimize the sum of the squared errors between the observed data and the predicted one.


4.statsmodels.stats.anova.anova_lm(*args, **kwargs)  ------> ## Anova table for one or more fitted linear models.
