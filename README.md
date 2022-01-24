# -School_District_Analysis.-
## Overview of the school district analysis:
The school board has informed Maria about the CSv file showing the possibility for academic dishonesty. Particularly in the reading and math grades of the 9th graders at Thomas High School. The purpose of this analysis is to perform a new School District Analysis after replacing the reading and math scores for ninth-graders for Thomas High School and write a report how this has impacted the overall analysis.

For this analysis we used the Pandas library in Python. Data from separate CSV files are read into Pandas and merged to create multiple different dataframes and analyzed.


## Results:
Deliverable 1: we replaced Ninth-Grade Reading and Math Scores.First we selected the ninth-grade reading and math scores for Thomas High School using the Pandas loc method with conditional statements and comparison and logical operators. Then, the reading and math scores were replaced to NaN using the Pandas NumPy module.

![deliverable 1](https://user-images.githubusercontent.com/96032051/150737979-f32f0a54-f43c-461e-bcab-fb89a6915f3b.png)

![Thomas students ](https://user-images.githubusercontent.com/96032051/150741817-aadb6bff-fcf3-42d7-86ab-0aac9848ecbc.png)


Deliverable 2:
we preformed a new analysis the following metrics after replacing the 9th-graders scores from Thomas High School:

##### The District summary

Original analysis:![ds](https://user-images.githubusercontent.com/96032051/150750108-dac75087-1c1d-46ce-b3e1-506655d36a87.png)



Re-analysis:![district summary](https://user-images.githubusercontent.com/96032051/150738026-90a6ffee-3c25-44ee-a8a3-ba30ff66c4bf.png)


How is the district summary affected?

After re analysis the district summary showed slight effect as seen in image.Average Math Score , % Passing Math , % Passing Reading , % Overall Passing decreased by <1%




##### The school summary

Original analysis:![O-school summary](https://user-images.githubusercontent.com/96032051/150743835-de2cd82e-84a2-4208-b2f9-ae8b6f336e84.png)

Re-analysis:![school summary](https://user-images.githubusercontent.com/96032051/150738427-8d3dd663-dddf-47f9-85a1-ff1f2da13718.png)


How is the school summary affected?

The school summary had an impact in % Passing Math from 93% to 67%, % Passing Reading from 97% to 70%, % Overall Passing from 91% to 65% after re-analysis


##### The top 5 and bottom 5 performing schools, based on the overall passing rate

Original analysistop 5 schools:![o-top 5 schools](https://user-images.githubusercontent.com/96032051/150744157-b2b404f7-30f6-40f3-ad80-1bf4d1f8b425.png)

Re-analysis:![top five schools](https://user-images.githubusercontent.com/96032051/150738452-807781ec-674f-4cbd-a387-0be9b24340f6.png)


Original analysis bottom 5 schools:![o- bottom 5 schools](https://user-images.githubusercontent.com/96032051/150744229-482c9a2e-7558-4499-aab2-48fb30cd6849.png)

Re-analysis:![bottom five schools](https://user-images.githubusercontent.com/96032051/150738470-2c5d3591-364b-4e5f-97b9-5703e7892971.png)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders’ math and reading scores at Thomas High School showed reduced performance compared to the other schools

##### The average reading score for each grade level from each school


Original analysis:![o- average reading scores for each grade](https://user-images.githubusercontent.com/96032051/150744282-db35b93e-1314-4616-888f-d79a31a3a1cd.png)

Re-analysis:![average reading scores for grade](https://user-images.githubusercontent.com/96032051/150738538-1571087d-a9ee-4ee4-ac88-4bd329716b22.png)


##### The average math score for each grade level from each school

Original analysis:![o- Average math scores for each grade](https://user-images.githubusercontent.com/96032051/150744306-f9768a9a-3866-4298-8844-794e4dd1ea99.png)

Re-analysis:![average math scores for each grade](https://user-images.githubusercontent.com/96032051/150738570-72b60da1-9b32-4d80-b225-96ae082ff133.png)


Math and reading scores by grade: Math and reading scores by grade were higher after removing 9th Grader scores from Thomas High School

##### The scores by school spending per student, by school size and by school type
##### scores by school spending per student
Original analysis:![o- spending summary](https://user-images.githubusercontent.com/96032051/150744339-2f9afd90-2bfd-46b8-b58d-2b220db068c4.png)

Re-analysis:![spending summery](https://user-images.githubusercontent.com/96032051/150738666-9f980de9-90af-495a-aa84-edfc93b78a3c.png)


Scores by school spending : The scores by school spending  has impacted for the $630 - $644 category only



##### scores by school size

Original analysis:![o- size summary](https://user-images.githubusercontent.com/96032051/150744427-31c2d98c-3113-474c-82c2-3137674d6919.png)

Re-analysis:![size summary](https://user-images.githubusercontent.com/96032051/150738695-280ac316-3267-4326-bcfc-3b829def3f95.png)


Scores by school size:The medium size school scores were effetced after re-analysing the data.


##### scores by type

Original analysis:![o- type summary](https://user-images.githubusercontent.com/96032051/150744464-df59841a-f4a1-46eb-81be-3a38c6b9533d.png)

Re-analysis:![Type summary](https://user-images.githubusercontent.com/96032051/150738714-d4e0b29c-0525-4d18-9e09-086a134e6934.png)

Scores by school type:charter schools score by type was changed after the data change.


## Summary:



After removing of Thomas High Schools ninth grade math and reading scores and re-Analysing, the schools metrics were impacted.
The school's ranking changed among the other schools in the district.
There is an Improvement in Thomas High School overall reading and math scores.
we can notice the Change in Medium-sized school pass rates and Charter School pass rates.
There is also a change in  $630-644 school's budget catogery pass rates.
