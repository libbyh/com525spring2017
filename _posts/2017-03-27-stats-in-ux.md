---
layout: post
title: "Practical Statistics for User Research: Analyzing Survey Data"
comments: false
description: "Statistics in UX"
---

# Summary	 
Now we have our survey results, what's next? How can we make them meaningful to us, and stakeholders?


Scenario:	
We want to understand whether students and professionals use food delivery service at different times, on weekdays or weekends. So we conducted a survey with 60 subjects, 30 students and 30 professionals. We collected 21 professionals who use food delivery service on weekdays and 9 on weekends, and 14 students who use food delivery service on weekdays and 16 on weekends. 

What does this data tell us?


# Descriptive Statictics & Inferential Statistics
Two kinds of statistics.

## Descriptive Statistics

We use decriptive statistics to describe the basic features of the data in a survey. 

E.g. GPA. (Excel.)

* Frequency distribution 
	* Visualization
* Measure of central tendency
	* Mode
	* Median
	* Mean 
* Measure of variability
	* Range
	* Standard devidation 	 
* Correlation coefficient. [-1,1]  
	* Pearson's r
	
	
## Inferential Statistics

We use it to try to reach conclusions that extend beyond the immediate data alone.
We use it to infer from the sample data, what the population might think.


Go back to our scenario at the beginning. (In Excel.)

.			
.		
.	

It looks like ..
What if ..
		
	
How do we know they are significantly different? 	
When can we confidently say that they're different in the whole big data set?	
Is this difference a "real" difference, or just caused by chance?	
If we conduct the research again, would we get the same conclusion?	


* Normal Distribution (curve)

	
<img src="http://d2r5da613aq50s.cloudfront.net/wp-content/uploads/400455.image2.jpg">
	
When the difference caused by chance happens less than 5%, we reject the hypothesis. (p < .05)

### Chi-Square Test

A chi-squared test, also written as χ2 test. It's used to compare the proportion of difference between the sets arose by chance.

* Data type: categorical data (e.g, Male/Female, A/B)

* Use Chi-Square test in the first scenario, with Excel.

* Check p value. 

* When p < .05, the different is significant.

Similarly, for the question,	

Rank the criteria in order of priority/importance.

* Price
* Location
* Reviews


### T-test

T test is used to evaluate whether two sets of data are significantly different.

* Data type: Numeric data. (e.g., time, errors)

* Scenario: Netflix. Hours ~ Sex. Use t-test with Excel.

* Check p value.

* When p <.05, the different is significant.

(Independent-samples t-test. for Between subjects.)

<b>Between v.s. Within</b>

Paired-samples t-test is for within subjects.

* Scenario: GrubHub. Criteria Score ~ Criteria.

# Report

Some things you need to include:

* Sample size. How you decide what kind?
* Variability.
* Significance.
* Discussions & findings. (Who's your audience? What do we do survey for?)






