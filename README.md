# School_District_Analysis

# Overview:
In this project, an analysis of scores is done for a school district.  During the course of the analysis it is discovered that the 9th grade class at one of the schools had cheated and thus their data had to be removed.  This project analyzes the impact that removing that data had upon the original analysis.

# Results:
## 1. How is the district summary affected?
Dropping the students that cheated from the district summary had the following effects:
- Average math score dropped by 0.1%
- % of students passing math dropped 0.2%
- % of students passing reading dropped 0.3%
- % of overall passing students dropped 0.1%

See the images below.

### District Summary Before:
![image](Resources/district_summary_before.jpg?)

### District Summary After:
![image](Resources/district_summary_after.jpg?)

## 2. How is the school summary affected?
Dropping the students scores, but still counting the students, that cheated from the school summary had the following effects on Thomas High School:
- Average math score dropped by approximately 0.06%
- Average reading score increased by approximately 0.05%
- % of students passing math dropped from 93.3% to 66.9%
- % of students passing reading dropped from 97.3% to 69.7%
- % of overall passing students dropped from 90.9% to 65.1%

See the images below.

### School Summary Before:
![image](Resources/school_summary_before.jpg?)

### School Summary After:
![image](Resources/school_summary_after.jpg?)

## 3. How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
Removing the 9th grade scores and updating the summary put the scores from Thomas High back into line with the other charter schools as one would expect.  Before, with the scores removed but students still included, the scores were abnormally low compared with the other charter schools in the school district.  See the image below for updated scores.

### School Summary with 9th Graders at Thomas High Dropped:
![image](Resources/school_summary_after_fixed.jpg?)

## 4. How does replacing the ninth-grade scores affect the following:
### - Math and reading scores by grade

Nothing changed here except that Thomas High now shows nan for 9th grade scores.

### - Scores by school spending

Nothing changed here with the updated data.

#### Scores by Spending Before:
![image](Resources/scores_by_spending_before.jpg?)

#### Scores by Spending After:
![image](Resources/scores_by_spending_after.jpg?)

### - Scores by school size

Nothing changed here with the updated data.

#### Scores by School Size Before:
![image](Resources/scores_by_size_before.jpg?)

#### Scores by School Size After:
![image](Resources/scores_by_size_after.jpg?)

### - Scores by school type

Nothing changed here with the updated data.

#### Scores by School Type Before:
![image](Resources/scores_by_type_before.jpg?)

#### Scores by School Type After:
![image](Resources/scores_by_type_after.jpg?)

# Summary
In conclusion, removing the 9th grade class scores from Thomas High School had the following effects on the school district analysis:
- Average math score dropped by 0.1%
- % of students passing math dropped 0.2%
- % of students passing reading dropped 0.3%
- % of overall passing students dropped 0.1%
