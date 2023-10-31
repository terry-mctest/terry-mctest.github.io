At the risk of over-simplifying, it seems there are two broad categories of variable selection methods for building statistical models:  (1) selecting predictor variables based on theory / background knowledge, and (2) data-driven/machine learning-type selection methods (e.g. forward selection, backward selection).

Each of this week's recommended readings provides extensive detail regarding the relative weaknesses of the latter set of variable selection methods.  Among the points that most resonated in my own thick skull:
* Per Biom (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969114/), iterative data-driven approaches have the following shortcomings (among others):  "First, unaccounted multiple testing will generally lead to underestimated p‐values. Second, p‐values for coefficient tests from a model do not test whether a variable is relevant per se, but rather whether it is relevant given the particular set of adjustment variables in that specific model."
* Per https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf (also regarding iterative data-driven approaches): "Because of the one-at-a-time nature of adding/dropping variables, it’s possible to miss the optimal model."
* Per Ratner (https://link.springer.com/content/pdf/10.1057/jt.2009.26.pdf), stepwise approaches are "based on methods (for example, F tests) that were intended to be used to test pre-specified hypotheses."
* Also per Ratner, these approaches "prevent us from thinking about the problem."

Two questions may help guide one towards one of these two large bins of variable selection methods:
* Do you know anything about the data with which you're working?
* Are you interested in using your model for prediction, or for making inference?


