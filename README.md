# School_District_Analysis

## Overview of the school district analysis
The School Board has requested student data related to the 9th grade of Thomas High School be replaced due to suspected academic dishonesty.  After the suspected questionable scores are removed, a new school district analysis will be performed.

### Analysis to be performed:
- Perform district summary
- Perform school summary
- Thomas High School performance relative to other schools (post replacement)
- Impact of replacing 9th grade scores:
  1. Math and reading scores by grade
  2. Scores by school spending
  3. Scores by school size
  4. Scores by school type

## Resources
- Data Source: [schools_complete.csv](https://github.com/nkinsler/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Data Source: [students_complete.csv](https://github.com/nkinsler/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Software: Python 3.7 (64 bit)
- Python: [PyCitySchools_Challenge](https://github.com/nkinsler/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Results

### District Summary

##### Original
![Original_District_Summary](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_District_Summary.png)

##### Adjusted
![Adj_District_Summary](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_District_Summary.png)

The impact of the district summary with the adjustment of the Thomas High School 9th grade scores removed is minimal.  The average math score dropped 0.1 and average reading score remained the same.  The passing percentage of math decreased by 0.22% while passing percentage of reading decreased 0.15%.

### School Summary

##### Original
![Original_School_Summary](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_School_Summary.png)!
##### Adjusted
![Adj_School_Summary](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_School_Summary.png)!

The impact of the school summary with the adjustment of the Thomas High School 9th grade scores removed is also minimal as it relates to average math and reading scores.  The average math and reading scores remained unchanged.  The passing rates were impacted by the adjustment.  Passing math percentage increased 26.274375% while passing reading percentage increased 27.35513%.  Overall passing percentage increased 25.553781%.

### Thomas High School performance relative to other schools (post replacement)

#### Top/Bottom 5 Performing Schools

##### Original Top 5
![Original_Top5](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Top5.png)!
##### Adjusted Top 5
![Adj_Top5](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Top5.png)!
##### Adjusted Top 5 Including 9th Grade
![Adj_Top5_With9th]https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Top5_With9th.png)!

##### Original Bottom 5
![Original_Bottom5](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Bottom5.png)!
##### Adjusted Bottom 5
![Adj_Bottom5](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Bottom5.png)!
##### Adjusted Bottom 5 Including 9th Grade
![Adj_Bottom5_with9th](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Bottom5_With9th.png)!

Based on the results of the top 5 performing schools before and after the adjustment, nothing significant changed with Thomas High School as compared to the other schools.  Thomas High School still remains as second best overall performing school.

Comparing the school information includisze of the 9th grade indicates a significant difference.

### Impact of replacing 9th grade scores

#### Math and reading scores by grade

##### Original Math Scores
![Original_Math_Grades](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Math_Grades.png)!
##### Adjusted Math Scores
![Adj_Math_Grades](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Math_Grades.png)!

##### Original Reading Scores
![Original_Reading_Grades](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Reading_Scores.png)!
##### Adjusted Reading Scores
![Adj_Reading_Grades](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Reading_Scores.png)!

The only impact to the math and reading scores by grade is the removal of Thomas High School's Math and Reading scores to say nan.

#### Scores by school spending

##### Original
![Original_Schools_by_Spending](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Scores_by_School_Spending.png)!
##### Adjusted
![Adj_Schools_by_Spending](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Scores_by_School_Spending.png)!

The average math score decreased 0.02 while the average reading score increased 0.02 for schools spending between $630-644.  The passing math percentage decreased 0.02% while passing reading percentage decreased 0.07% for schools spending between $630-644.  Overall passing percentage decreased 0.08% for schools spending between $630-644.  Based on the results, the impact of the adjustment was minimal.

#### Scores by school size

##### Original
![Original_Schools_by_Size](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Scores_by_School_Size2.png)!
##### Adjusted
![Adj_Schools_by_Size](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Scores_by_School_Size.png)!

The impact of the adjustment is limited to medium sized schools.  Average math score decreased 0.01 while average reading score increased 0.01.  Passing math percentage decreased 0.02% while passing reading percentage decreased 0.06%.  Overall passing percentage decreased 0.06%.  Based on the results, the impact of the adjustment was minimal.

#### Scores by school type

##### Original
![Original_Schools_by_Type](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Original_Scores_by_School_Type.png)!
##### Adjusted
![Adj_Schools_by_Type](https://github.com/nkinsler/School_District_Analysis/blob/main/Analysis/Adj_Scores_by_School_Type.png)!

The impact of the adjustment is limited to charter school types.  Both the average math and reading scores remained unchanged. Passing math percentage decreased 0.01% while passing reading percentage decreased 0.04%.  Overall passing percentage decreased 0.04%.  Based on the results, the impact of the adjustment was minimal. 

## Summary

Overall the most noticed changes to the school district analysis after reading and math scores for the ninth grade at Thomas High School was replaced is as follows:
1. District wide, a minimal (less than 1%) decrease in math, reading, and overall passing percentages.
2. In comparing schools, Thomas High saw a significant increase in math, reading, and overall passing percentages with the adjustment.
3. Thomas High School still remained ranked the second highest performing school.
4. Minimal impact to scores when grouped by spending, size, and type.  Removing an entire grade from one school doesn't seem to impact the district overall.


