# School District Analysis

## Project Overview
### Part I: 
Process reading and math proficiency standards test data for analysis, reporting, and presentation to provide insights to City School performance and trends.  This information will be used to inform discussions and make strategic decisions at school and district levels.  The analysis includes:
1. District summary
1. School summary
1. Top and bottom five performing schools, based on the overall passing rate
1. Average math and reading scores for each grade level from each school
1. Scores by school spending per student, by school size, and by school type

### Part II: 
The school board discovered evidence of academic dishonesty; specifically, the reading and math scores for Thomas High School ninth graders appear to have been altered.  A revised School District Analysis was conducted, excluding the Thomas High School ninth grade reading and math scores.

## Results, comparing the revised and original analyses:
 * _DISTRICT SUMMARY_ - No impact
 
    ![DistrictSumOrig](https://user-images.githubusercontent.com/90986041/136877940-f94e6c23-5aab-4dc1-acaa-723bbebe14e0.png)
    ![DistrictSumRev](https://user-images.githubusercontent.com/90986041/136880577-201fe6c6-87b2-4b86-8995-f5759dff7463.png)


 * _SCHOOL SUMMARY_ - No impact other than Thomas High School's reading, math, and overall scores and percentages decreased.
 
    ![PerSchoolSumOrig](https://user-images.githubusercontent.com/90986041/136878683-546d8daa-278d-4f93-a76e-b72fda8c2d53.png)
    ![PerSchoolSumRev](https://user-images.githubusercontent.com/90986041/136880608-12ff6239-442c-4a91-a2db-f1e7cd09dc6f.png)

 * _SCHOOL RANKINGS_ - Thomas High School's overall performance relative to other schools did not change. 
 
   ![Top5Orig](https://user-images.githubusercontent.com/90986041/136878712-91b7c697-3850-4ece-9ebc-a7b064d2357f.png)
   ![Top5Rev](https://user-images.githubusercontent.com/90986041/136880631-7c92299a-770a-4a98-9b16-81f28b46340c.png)

 * _REPLACING THE NINTH-GRADE SCORES AFFECT ON THE FOLLOWING_:
 
 ** Math and reading scores by grade - No impact other than Thomas High School's ninth grade scores are removed in the lists.
 
   ![MathScoreGradeOrig](https://user-images.githubusercontent.com/90986041/136878751-36d988d7-6fcd-4461-b41c-7d6b2fa24099.png)
   ![MathScoreGradeRev](https://user-images.githubusercontent.com/90986041/136880671-4e73b969-9e6c-4795-9568-146ed0a4ccb4.png)

   ![ReadScoreGradeOrig](https://user-images.githubusercontent.com/90986041/136878770-3c9217ce-f8fb-4288-ae7a-3085de1cd2f6.png)
   ![ReadScoreGradeRev](https://user-images.githubusercontent.com/90986041/136880709-0ffc0b7a-d485-41d5-b494-c8a4da11c88b.png)

 ** Scores by school spending - No impact
 
   ![SpendSumOrig](https://user-images.githubusercontent.com/90986041/136878797-7b166631-b797-4a55-bdb4-c14ce7cd326f.png)
   ![SpendSumRev](https://user-images.githubusercontent.com/90986041/136882396-55d6ba09-26b9-42bc-8da9-f2083be2022c.png)

 
 ** Scores by school size - No impact
 
  ![SpendSizeOrig](https://user-images.githubusercontent.com/90986041/136878821-528a390b-400f-42c4-9cb7-2501c3b38500.png)
  ![SpendSizeRev](https://user-images.githubusercontent.com/90986041/136880736-dde5fa81-d41a-46d0-b9e1-124ab36cb222.png)

 ** Scores by school type - No impact

  ![TypeSumOrig](https://user-images.githubusercontent.com/90986041/136878855-9f5f4985-339e-49e6-a885-e75581fe678b.png)
  ![TypeSumRev](https://user-images.githubusercontent.com/90986041/136880751-bd275ea4-bdca-4a97-9ea4-719f4b109d9f.png)

 ## Summary:
 As shown above, removal of the Thomas High School ninth grade reading and math scores only impacted these analyses:
 1. School Summary - School figures remained the same, except those specifically related to Thomas High School's reading, math, and the overall percentages.
 1. School Ranking - While Thomas High School's overall percentage decreased, it wasn't enough to change their second place ranking among the Top 5 schools.
 1. Math Scores by Grade - Thomas High School ninth grade math score is listed as "nan" (No available Number), proof that the scores were removed in the revised analysis.
 1. Reading Scores by Grade - Thomas High School ninth grade reading score is listed as "nan" (No available Number), proof that the scores were removed in the revised analysis.
 
___
## Resources
_Data Sources_: https://github.com/SJLewer/School_District_Analysis/tree/main/Resources

_Python 3.7.6 Script (Original Analysis)_: https://github.com/SJLewer/School_District_Analysis/blob/main/PyCitySchools.ipynb

_Python 3.7.6 Script (Revised Analysis)_: https://github.com/SJLewer/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb

_Analyst_: S. Lewer
