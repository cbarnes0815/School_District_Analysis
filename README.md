# School_District_Analysis

## Overview of Project
A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

# Analysis

### How is the distric summary affected?
When comparing the original analysis with the summary post removing the Thomas High 9th graders there was not much of a difference. The total number of students remained the same do to the grades of the Thomas High students were the only things dropped. The student count and budget remained the same. When looking at the grades after removing the student, the scores dropped about 1% whhich isnt a big difference since the rounded number will still be the same.

### Original Summary:

<img src= "Resources/Original_School_Summary.png"/>

### Adjusted Summary:
<img src= "Resources/Adjusted_District_Summary.png"/>

### How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate. This was concerning to the Board therefore after removing the 9th graders and recalculating,the rest of the testing data was adjusted accordingly. The results showed that the Thomas High School **Passing Math %, Passing Reading % and Overall %** dropped drastically. The average went from about 91% to 65%.

Orginal Analysis:
<img src = "Resources/Original_School_Summary.png"/>

Adjusted Analysis:
<img src = "Resources/Adjusted_Thomas_School_Summary.png"/>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the Original Analysis Thomas HS ranked in the 90th percentile as the 2nd ranking school, which was alarming to the School Board. After removing the 9th grade scores from Thomas High the school rank in the bottom 10 placing Thomas HS in 8th place District wise with a 65%.

Original Analysis:
<img src = "Resources/Original_Reading_Math_Overall.png"/>

Adjusted Analysis:
<img src = "Resources/Adjusted_Reading_Math_Overall.png"/>

### How does replacing the ninth-grade scores affect the following:
## Math and reading scores by grade
Replacing the 9th grade math and readig scores did not have a direct impact on the other grade levels grades

Reading: 

<img src = "Resources/Reading_Scores.png" width=35% height=35%>

Math:

<img src = "Resources/Math_Scores.png" width=35% height=35%>

## Scores by school spending
There was little to no impacted on the spending ranges after removing the 9th grade scores. Thomas HS falls within the $630- $644 per student range.

Original Analysis:
<img src ="Resources/Original_School_Spending.png"/>

Adjusted Analysis:
<img src ="Resources/Adjusted_School_Spending.png"/>

## Scores by school size
There was little to no impacted on the school size range after removing the 9th grade scores. Thomas HS falls within the range to be classified as a medium sized school.

Original Analysis:
<img src ="Resources/Original_School_Size.png"/>

Adjusted Analysis:
<img src ="Resources/Adjusted_School_Size.png"/>

## Scores by school type
There was little to no impacted by school type after removing the 9th grade scores. Thomas HS is a Charter School.

Original Analysis:
<img src ="Resources/Adjusted_School_Type.png"/>

Adjusted Analysis:
<img src ="Resources/Adjusted_School_Type.png"/>

### Summary

In summary the 4 major changes in the School District Analysis after removing the 9th Grade Scores for Thomas High School were:

  1. The overall passing rate for Thomas High School changed from 91% to 65%
  2. Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.
  3. The 9th Grade reading and math data will now read "NaN" for Thomas High School
  4. The averages and percentages including overall passing rate for Thomas High School saw atleast a 1% change.
