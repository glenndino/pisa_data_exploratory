# Pisa data 2012 exploration


## Data

This dataset is a survey of student's skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school

Around 510,000 students in 65 economies took part in the PISA 2021 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

For this paticular investigation, I chose 12 features:

Gender, parents level of education, 4 variables of attitude of the students, average score of math, reading, and science, total learning time, out of school study time, and parental presence.

Pisa data 2012 zip file was too large, the file can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip) for the full dataset.

## Summary

This study investigates the influence of various different factor towards students academic performance. Multiple variables are collected, wrangled, and observed to find any relationship or correlation to the main variable of interest, which is the average total score of the student.

In the beginning, we looked at the average total score for each gender, and the plot shows that both are normally distributed. We looked further and boxplot and found that female does slightly better in the average score.

The next variable we investigated is the parents level of education. We found that 32% of the parents hold at least a bachelor degree or higher. We can conclude that most parents are well-educated. But does this impact the kids academic performance?

Before we further investigate, we broke down the categorical variable (attitude/persevearance level) into numeric and found that most of the students remain neutral to the questions whether they give up easily, likes to procrastinate, or they consider themselves as a good student who perform well in school.

When comparing the parents level of education to the average total score, there is a strong relationship between these two variables. The higher the education of the parents, the better their performances are in school through the total average of all three subjects. As for the the level of agreement to the attitude variables, we found a slight interaction and correlation where the more positive attitude they agreed to, the higher the score they have and the more study time they put in. When adding another variable in, which is the parental presence at home, it seems that it does not have a strong effect to the attitude but rather to their academic performance. As to both learning time and study time, the students put in almost the same amount of time regardless either parents are home. Investigating even further for each of the different categories the students spend their time studying outside of school, we found some interesting insight. For example, the out of school total study time seem and average total score seem to have no correlation at first but when we took the analysis deeper to each of the categories in the variable, we found out that the more homework time the students put in, they generally do better than the average. And as for the other variables, such as personal tutor time, tutor with commercial company, or even guided homework time with parents or computer, we see 0 to negative correlation. Maybe the students who took the time to get from outside help are already struggling in school? The same case for the attitude variable need to be implemented, we need to investigate further in order to state a conclusion with strong basis of argument. So in conclusion, The level of education of the parents and their presence, and how much time the students put in for homework are big predictors of success in student's academic pursuit. 
