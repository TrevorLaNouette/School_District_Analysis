# School_District_Analysis


## Overview of Project:

The purpose of this analysis is well defined (3 pt).
Results:
After helping Maria build an analysis of her school district she has asked that I assist in futher analysis targeting the 9th grade class at Thomas High School. She has asked that I repeat the a similar process used to conduct the district analysis but with the removal of the 9th grader's state test scores. This is in effort to compare the resulting data to the original to see how it affected the data. significant changes in the average data will help determine if there was any academic dishonesty in the schools reporting of test scores.


### Summary
- inorder to analize the impact of the scores of the 9th grade student at Thomas High School I had to replace all of the reading and math grades with NaN(Not a Number).

<img width="847" alt="Thomas HS 9th NaN" src="https://user-images.githubusercontent.com/82718969/125376479-b1836800-e350-11eb-9a0c-3069feb3e64f.png">

-Once this was completed I could begin to run the the same analysis of the district and compare the new data to the original data.

- Below are the key metrics used to determine the affected by the changes in the data. Results of the removal of the 9th grade test scores are analized in each category.

* The district summary DataFrame:
 -   The average score for the math for the district was lowered by approximately .01 point and .1% The change average score and percentage passing in reading were not significant enough to change our data. The overall passing rate was lowered by .1%.


### Original District Summary DataFrame

<img width="830" alt="Original District Summary DF" src="https://user-images.githubusercontent.com/82718969/125376553-dc6dbc00-e350-11eb-8496-a7dbbbaf94e1.png">
 

### New District Summary DataFrame

<img width="700" alt="No ninth District Summary DF" src="https://user-images.githubusercontent.com/82718969/125376519-cd870980-e350-11eb-8504-2c30b7b63eea.png">


 
* The school summary DataFrame:
-   The school summary Datafram changes were not significant. The averag score in math dropped by approximately .067 points.  The %passing math dropped .086%. The average reading score increased by approximately .047 points. The passing rate dropped by approximately .69%. The overall passing percentage dropped by approximately .318%

Original School Summary DataFrame

<img width="838" alt="Original School Summary DF" src="https://user-images.githubusercontent.com/82718969/125376632-1474ff00-e351-11eb-9741-453ef81aca8b.png">


New School Summary DataFrame

<img width="845" alt="No ninth School Summary DF" src="https://user-images.githubusercontent.com/82718969/125376613-058e4c80-e351-11eb-934f-1d2562c2ad81.png">

* The top 5 performing schools, based on the overall passing rate:
There were no changes to the rank of top performing schools. Thomas HS still maintained its 2nd highest ranking.
* The bottom 5 performing schools, based on the overall passing rate:
Again, there was no change to the rank of the bottom performing schools rank. The only school data altered was Thomas HS
* The average math score for each grade level from each school:
The average reading scores for each grade level from each school did not change with the exception of the removal of the 9th grade scores from Thomas HS.
* The average reading score for each grade level from each school: 
The average reading scores for each grade level from each school did not change with the exception of the removal of the 9th grade scores from Thomas HS.
* The scores by school spending per student:
The scores by school spending were not altered as only the 9th grade students' scores for math and reading in Thomas High School were removed.
* The scores by school size:
The scores by school Size remained the same as no schools or students were changed in this data.
* The scores by school type:
The scores by school type remained unchanged because no schools or students were changed in this data.

## Summary 
- There were no significant changes to the district scores. Futher analysis of the data file backs up that the average score of the 9th grade students at Thomas High school (Math 83.35, Reading 83.90) were within expected range for their school. This is quite close to the average of the district (Math 78.9, Reading 81.9) thus it does not have a large effect on the district scores.
