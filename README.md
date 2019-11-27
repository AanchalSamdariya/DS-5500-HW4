# Homework 4 Solutions 

## Problem 1

### For the districts you selected for budget cuts in HW 3 Problem 4, calculate and visualize the proportion of each district’s total funding that will be lost. 

The figure below shows the proportion of total funding lost by each of the districts.

![](/images/Q1_budget_cut_proportion.png)

### Which districts will be affected by your budget cuts the most?

![](/images/Q1_districts_affected.png)

As we can see, these are the top 10 districts which would be affected by the budget cuts.

## Problem 2

### A common problem with purely data-driven solutions is that they can inadvertently perpetuate hidden pre-existing biases in the data, and further disadvantage groups that are already disadvantaged. Calculate the proportion of enrolled students by race for each district, then visualize the distributions of these for districts that received budget cuts versus districts that did not receive budget cuts. 

The calculations are performed in the Notebook file to get the proportion of enrolled students by race for each district. Below is the figure showing the distributions of these for districts that did not receive budget cuts versus districts that received budget cuts.

![](/images/Q2_race.png)

### Comment on whether the distributions appear to be the same or different. Did your selection include any hidden biases, or manage to avoid them?

The distributions appear to be different for districts that received budgets cuts and for districts that did not receive any budget cuts based on the races.
As we can see, the distribution of proportion of people recieving revenue cuts for all races are different from proportion of people not receiving budget cuts for all races. We can also see that, based on caste, revenue cuts are not spread out evenly and districts with a large number of people belonging to WH race would have higher chances of receiving a busget cut. This unsimilarity in distribution of proportions shows that there has been bias introduced in calculations which has resulted in these numbers.

## Problem 3

### Calculate the proportion of enrolled students by disability status (students with an IEP under IDEA) for each district, then visualize the distributions of these proportions for districts that received budget cuts versus districts that did not receive budget cuts.

The calculations are performed in the Notebook file to get the proportion of enrolled students for each district whoa re disabled and who are not disabled. Below is the figure showing the distributions of these for districts that did not receive budget cuts versus districts that received budget cuts.

![](/images/Q3_disability.png)

### Comment on whether the distributions appear to be the same or different. Did your selection include any hidden biases, or manage to avoid them?

The distributions appear to be the same for districts that received budgets cuts and for districts that did not receive any budget cuts based on the disability factor.
As we can see, the proportion of people who are not disabled and receiving revenue cuts is higher than those not receiving any budget cuts. Also, there are higher proportions of disabled people not receving budget cuts than those which receive budget cuts. This similarity in distribution of proportions shows that there has not been any bias introduced in calculations which has resulted in an unbiased solution.

# Problem 4:

### Choose and critique one of your fellow classmates’ selection of schools for budget cuts in HW 3 Problem 4 and Problem 5. What was the justification of their selection? Discuss any advantages or disadvantages of their approach.

HW3 reviewed: [Github link](https://github.com/devanshigariba/Applications-of-Data-Science/blob/master/README.md)

I chose Devanshi Gariba's strategy for budget cuts. She has used the idea of not cutting equal amounts from each of the school districts, instead cut revenue according to the proportion of current revenue and expenditure. This is justified because some school districts might earn less and some might earn more. Deduction of equal amount of budget would be unfair to school districts with lower revenue. She also considered only those school districts which have a positive funding after taking into account their revenue and expenditure. This is also a beneficial point and adds to better results. One disadvantage of this method is that only the monitary features were taken into consideration. It might help remove bias if any, by taking additional features like demographics into account.
An additional check she did was to check if the budget cut from different school districts actually add up to how much of a cut is required. This was a well thought of step as it could avoid cutting budgets unnecessarily.

# Problem 5:

### Summarize and comment on what you learned from one the special topics lectures (MapReduce + Hadoop, Visualization, Causal Inference, or the Industry Panel) of your choice.

The most interesting special lecture topic I found was the MapReduce lecture by Jan Vitek. He gave a brief understanding about MapReduce and how it is implemented at a basic level. He also gave light on the history of MapReduce and Big data. It was very informational as big data is the talk of the town. In our coursework, we don not generally get to work with large datasets, whereas almost every big company would have very large datasets to deal with. I understood the need to be aware of such technology and concepts which could help in faster and better processing or big data. Parallelization of processes would also help increase efficiency and is made possible by using MapReduce concepts. 
