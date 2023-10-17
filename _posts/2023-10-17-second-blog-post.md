**What is your overall goal when doing an EDA?**  In general terms, the over-arching goal is to gain a better understanding of the data with which one is working.  The EDA may be used to evaluate the feasibility of using said data to investigate particular question(s) of interest, and/or may used to generate additional questions which said data might be useful in addressing.  In the course of doing so, one may wish to summarize the data, often times using graphics (e.g. "a picture's worth a thousand words").

**What methods do you think are important?** 
* Obtaining metadata such as # of records, # of columns, column names, and a listing of any ID-type variables
* Using "proc eyeball", i.e. open the dataset and peruse
* Generating summary statistics such as freqs, means, "five number summaries", and correlation coefficients 
* Generating graphical summaries such as bar charts, histograms, boxplots, scatterplots, run charts, PDF and PMF plots

**What things do you try to look for?** 
* How the data are structured, e.g. is there one record per unit, or multiple records per unit
* The contents of the data, e.g. what measures are included
* Patterns of missing data, e.g. scope and prevalence of missing-ness, and whether data is legitimately missing ("not applicable"), or missing because its simply not available
* Variable types, e.g. categorical vs. continuous
* Univariate distributions and frequencies
* Bi-variate relationships
* Outliers and data anomalies/inconsistencies
* Potential specifications for modelling
