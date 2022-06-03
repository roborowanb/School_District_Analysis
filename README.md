# School_District_Analysis
Using Python within an Anaconda dev environment
## Overview
Not all data sets come with impeccable integrity. In this challenge, we have been informed that the data sets we are using to analyze student performance within PyCitySchools have been tampered with. We will be helping Maria, who has been employed by the school board as a data scientist, with removing the compromised data. We will then identify the differences between our analysis before and after cleaning the data. 
## Results
### How is the district summary affected?
- At a district level, these erased data points hardly make a difference at all. As seen below in the before:
![preclean_district_summary](https://github.com/roborowanb/School_District_Analysis/blob/fc06b015f9b99661b007156feee251a6f7dfe072/preclean%20district%20summary.PNG)
And after:
![postclean_district_summary](https://github.com/roborowanb/School_District_Analysis/blob/fc06b015f9b99661b007156feee251a6f7dfe072/postclean%20district%20summary.PNG)
- The average math score changes by 0.1%, and the reading change has no material change when rounding to the first decimal place. 
### How is the school summary affected?
- The school summary will have no change except for of course, Thomas High School's Math and Reading grades. 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- It does not. Thomas High School is still #2 in the district.
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
- There is one change to one cell in the table. No other cells are affected. 
#### Scores by school spending
- No change found 
#### Scores by school size
- No change found
#### Scores by school type
- No change found

## Summary
### No changes found!
In summary, it is not worth while to cheat, because it makes no difference to scores anyways. Its also dishonest and inhibits real learning. 
