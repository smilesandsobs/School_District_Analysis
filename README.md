# School_District_Analysis:

## Overview of the school district analysis: The purpose of this analysis.

I am helping Maria, the chief data scientist for a city school district, analyzise information on student funding and student test schools. We are looking for trends in school performance. The data we were provided includes, school name, type, size, budget, student name, gender, grade, school attending and reading and math scores. This analysis will help the school board make decision about the school budget. 

There is evidence in the datafile of academic dishonesty, so I have been asked to replace the math and reading scores for Thomas High School with NaNs. 

## Resources:

-Data Souce: clean_students_complete.csv
             schools_complete.csv   
Software: Python 3.7.6, Jupyter Notebook

## Results 
### How is the district summary affected?:

The average Math score decreases by .1 
The percentage passing math decreases by .2%
The percentage passing reading decreases by .3%
The total overall passing decreases by .9%

#### District Summary with Thomas High School's 9th grade results:

![This is an image](https://github.com/smilesandsobs/stocks-analysis/blob/main/Resources/VBA_Challenge_2017/CodeRun-%202017.png)

#### District Summary withOUT Thomas High School's 9th grade results:

![This is an image](https://github.com/smilesandsobs/stocks-analysis/blob/main/Resources/VBA_Challenge_2017/CodeRun-%202017.png)

### How is the school summary affected?:

The results for Thomas High School are the only results that change on our school summary DataFrame
The average Math score decreases by approximatly .1 
The percentage passing math decreases by approximatly .1%
The percentage passing reading decreases by approximatly .3%
The total overall passing decreases by approximatly .3%

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?:

Removing the ninth graders' math and reading scores does not impact Thomas High School's performance relative to other schools. Their 10th-12th grade students have high math and reading overall passing percentages and They remain in second when the data is sorted in descending order. 

#### Descending School Summary with Thomas High School's 9th grade results: 

![This is an image](https://github.com/smilesandsobs/stocks-analysis/blob/main/Resources/VBA_Challenge_2017/CodeRun-%202017.png)

#### Descending School Summary withOUT Thomas High School's 9th grade results: 

![This is an image](https://github.com/smilesandsobs/stocks-analysis/blob/main/Resources/VBA_Challenge_2017/CodeRun-%202017.png)

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade:
The only change to our results is that when broken out by school. The 9th grade results for Thomas High School show as NaN.

Our dataset is large enough that when we remove these 100 and something values our overall averages do not change.  

#### Scores by school spending:

Our averages and percentages passing change for our $630-644 spending range slightly.
The Average Math Score goes down by approximatly .01
The Average Reading Score goes down by approximatly .01
The % Passing Math goes down by approximatly .02%
The % Passing Reading goes down by approximatly .08%
The % Overall Passing goes down by approximatly .01%

#### Scores by school size:

Our Medium school size (1000-2000) is the only range changed.
The Average Math Score goes down by approximatly .01
The Average Reading Score goes down by approximatly .01
The % Passing Math goes down by approximatly .01%
The % Passing Reading goes down by approximatly .06%
The % Overall Passing goes down by approximatly .1%

 
#### Scores by school type:
Charter Schools ranges are changed
The Average Math Score goes down by approximatly .01
The Average Reading Score goes up by approximatly .1
The % Passing Math goes down by approximatly .01%
The % Passing Reading goes down by approximatly .03%
The % Overall Passing goes down by approximatly .1%


## Summary:

To summarize just a few of the changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School were replaced with NaNs.

#### Summary by Grades 
![This is an image](https://github.com/smilesandsobs/stocks-analysis/blob/main/Resources/VBA_Challenge_2017/CodeRun-%202017.png)

- The 9th grade results for Thomas High School show as NaN.
- All of our averages in our summaries were slightly impacted with the reading score decreasing more than the math averages.
- The $630-644 spending range bins averages go down slightly. 
- The Medium school size (1000-2000) bins averages go down slightly. 
- The Charter Schools averages go down slightly.




