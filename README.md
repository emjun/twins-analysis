# twins-analysis
Causal analysis of twin health outcomes

# Research Questions
1. Does mother’s health have an impact on the difference in birth weight of twin pairs?

2. Does birth weight have an impact on mortality rate?
    
3. Does birth order have an impact on birth weight?

4. Does mother’s health have an impact on the risk of twins developing chromosomal abnormalities?

# Files
`data_wrangling.Rmd`: Clean and wrangle data
`matching_pairs.Rmd`: Match twins from the individual observations/rows
`eda.Rmd`: Exploratory data analysis

# Subsetting the original dataset
- the orininal denominator and numerator are downloaded from the ncbi website.
- using the DPLURAL variable (with levels singleton, twin, triplets, etc.) to subset it only to data without singletons
- use a long string of covariates to match observations with the same set of covariates (Note that the `number` and `identifier` are basically the same thing. Just want to have something easier to refer to so I added the `number`)
- I was being conservative one picking the set of covariates by looking at the table with numbers of twins, triplets, ... in the our matched sample compared to what the orginal data reported in DPLURAL. By conservative, I meant I want our numbers to be no larger than what they reported. 
- This result in ~89.5% of matched samples which is similar with 90.5% reported in the paper for a different year. 

# Subsetting the matched data to data with birth order info
- I only subset it by looking at the number of unique birth orders match with the number of babies in that birth (e.g. for triplets, they should have 3 distinct birth orders)
- This is not perfect as explained in our meeting. Can work more on it later. 


# Presentations
Initial project overview: https://docs.google.com/presentation/d/1mMjyNRkq14cksO3MPji0mi4Vsnqf55Rp1gwpX0l6-7M/edit?usp=sharing
Final presentation: TBD