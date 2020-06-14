# Statistics and Data Science Paper Analysis
##### Below is a short summary of our findings, the attached document named `project.pdf` gives a full project report of our findings. Furthermore, `project-explore.ipynb` will show our data cleaning and visualization process as well as how we got to our conclusion. 

## Abstract
Deciding which college to attend has always been a difficult and life-changing moment for people and as a result, we wanted to help incoming students to understand the different factors that goes into determining how much an univesrsity tuition would be. Furthermore, we are interested in the representation of African-American in post-secondary institution and thus, we will be comparing the enrollment percepntage of African-American to other major races such as Hispanic, White and Asian.

## Dataset
We will be using 3 major datasets in our project which are all acquired from Kaggle and served to give us additional insight into tuition cost and diversity within institutions. The three dataset names are tuition cost, world ranking and total enrollment. The tuition cost dataset gives the user a sense of the major expenses students are in charged of during the first semeseter/quarter at the university. World ranking will show an institution's position with comparison to other institutions around the world. Lastly, the total enrollment dataset includes not just the sheer number of how many students enrolled in each college but also portray the ethnicity composition of the number of students as well.

## Method and Analysis
In the project, we will be using Altair as our main visualization library and skLearn as our machine learning library. Using Altair, we will use scatterplot as the primary comparison tool between the enrollment percentage in different institutions as well as factors that contributes to determining in-state tuition cost. Additionally, we will also construct and analyze the first and second principle component inside our dataset to explore interesting patterns between different states and their respective average tuition. Moreover, skLearn Linear Regression will be utilized to help us build a multi-linear model that can predict the in-state tuition given a set of factors

## Notable Figures
![Alt text](relative/path/to/roomAndBoardVsInState.png.jpg?raw=true "Room and Board Cost vs. In-state tuition")
![Alt text](relative/path/to/caucVsAfr.png.jpg?raw=true "Caucasion vs. African American Student Percentage Enrollment")
![alt text](https://github.com/trungbui2000/ds100_final_project/blob/master/roomAndBoardVsInState.png?raw=true)


## Results
After thoroughly explored the possible relationship of different factors that determined in-state tuition, we concluded that total enrollment does not correlate to in-state tuition. However, we did determine that there is a positive correlation between college room and board cost and in-state tuition, a negative correlation between school ranking and in-state tuition, both type of degree and type of institution all have a positive correlation with in-state tuition. Furthermore, regardless of which institution we analyze, Cacausian students in general have a 30% or higher enrollment percentage than African-American students. Additionally, higher tuition rates will generally corresponds to less African-American students enrollment percentage.
