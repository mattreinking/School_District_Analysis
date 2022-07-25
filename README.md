# School_District_Analysis

## Project Overview
The School Board found evidence in a csv file of academic dishonesty. The math and reading grades for the Thomas High School ninth graders appear to have been altered. It is currently unknown to what extent but the board wants to uphold state-testing standards. The School Board has asked to replace the math and reading scores with NaNs while maintaining the rest of the data intact. After replacing the math and reading scores, Maria would like a new school district analysis done to show how the overall analysis has been affected.

## Resources
Data Sources: students_complete.csv/school_complete.csv files
Software: Python 3.9.12, Visual Studio Code 1.69.2, Jupyter Notebook

## Results

### District Summary
- The overall district summary was minimally affected by the omission of the Thomas High School ninth grade math and reading scores. It is such a diminutive difference, it is practically negligible.
#### Before
![image](https://user-images.githubusercontent.com/86776606/180700619-91d15811-1875-4bfe-9986-4d59bb4d9857.png)
#### After
![image](https://user-images.githubusercontent.com/86776606/180700665-cad5a3db-6a3f-49f8-b451-b3226e7b5504.png)

- The average percentage never exceeded three tenths of a percent in any category. The data suggests the number of ninth graders in Thomas High School is not enough to have a significant impact on the overall average of the school district.

### School Summary
- The overall percentage of students passing greatly increased after recalculating the percentages for Thomas High School after omitting the ninth graders.
#### Before
![image](https://user-images.githubusercontent.com/86776606/180703042-49813a80-e2e7-4974-b026-7d56abdcc5e9.png)
![image](https://user-images.githubusercontent.com/86776606/180701778-2e6ef2ae-60be-4ef3-b2a8-3a7fa960703e.png)
#### After
![image](https://user-images.githubusercontent.com/86776606/180703070-e0e67751-81d9-439b-8503-a264b0dfbd8e.png)
![image](https://user-images.githubusercontent.com/86776606/180701845-fa6e9f39-33cd-471b-8063-4c40a4df600b.png)

- The percent passing in math, reading, and overall were struggling to reach 70% when including the ninth graders. After removing the ninth graders from the calculations, all percent passing categories saw a staggering improvement to at least 90% passing for percent overall and percent passing reading having as high as 97%.

### Thomas High School Performance Metrics
- The images above suggest the school's average math and reading scores were unaffected by the ninth graders being nullified but saw major improvements in percentage passing. In relation to other schools in the district, Thomas High School saw little change in average scores aside from the ninth grade column being replaced with NaN.


- Scores by school spending were unaffected only seeing as much of a difference up to a few tenths of a percent in each category as seen below
#### Before
![image](https://user-images.githubusercontent.com/86776606/180885362-6ff0c48f-208e-49c4-809e-44227f55b732.png)
![image](https://user-images.githubusercontent.com/86776606/180885177-5e22b592-9f8a-4148-8033-6a26a0671ab3.png)
#### After
![image](https://user-images.githubusercontent.com/86776606/180885484-f00106fa-d808-40d3-881a-8c782b17f2b9.png)
![image](https://user-images.githubusercontent.com/86776606/180885537-2a2fff45-4752-47bd-9832-65ff7214478d.png)


- Scores by school size remained minimally affected as seen below
#### Before
![image](https://user-images.githubusercontent.com/86776606/180886142-bfb62aa6-a239-4ca6-b617-a3cc9fc1b2ee.png)
![image](https://user-images.githubusercontent.com/86776606/180886178-ea56ffe5-d839-427b-b1df-680b25860c65.png)
#### After
![image](https://user-images.githubusercontent.com/86776606/180886342-fcef1bdc-3f20-49f6-916e-a9d5fdd8ed0a.png)
![image](https://user-images.githubusercontent.com/86776606/180886370-f2d114ba-f32f-4b46-b1d3-21d4783d2854.png)


- Scores by school type was not affected at all as seen below
#### Before
![image](https://user-images.githubusercontent.com/86776606/180886811-958add2a-6bf1-4a8b-acfe-471623f20e73.png)
#### After
![image](https://user-images.githubusercontent.com/86776606/180886854-60a8c097-eec2-485d-91ef-62ac9702695e.png)
## Summary
