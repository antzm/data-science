# t-test statistics

Examples on t-test statictics

## Example 1:

We randomly ask 50 students about their grades in mathematics. Based on that sample, we would like to draw some conclusions about the grades of all the students in a specific city (our population consists of all the students in the city, but we don’t have official data about their grades neither we have the ability to ask every single student in the city).
We construct e.g. the following hypothesis testing (let’s assume we read that in some other city, the mean grade is 75 and we would like to test if the students in our city have statistically the same grade or not):

Null hypothesis:
Η0: μ = 75

Alternative hypothesis:
Η1: μ <> 75

Reminder: μ is a Greek letter and so it refers to the population, as Greek letters in statistics refer to the population. On the other hand, the x bar refers to the sample, as English letters in statistics refer to the sample.
So, in this case, we are using a one-sample t-test to draw our conclusions.


## Example 2:

We ask 10 students from school A, and another 10 students from school B, about their grades in mathematics. We would like to compare the grades of those two schools. Now we have two populations. One population consists of all the students in school A, while the other population consists of all the students in school B.

We construct the following hypothesis testing:

NUll Hypothesis:
H0: μ1 = μ2

Alternative Hypothesis:
Η1: μ1 <> μ2

In this case, we are using a two-sample t-test to draw our conclusions.


## Example 3:

We ask 20 students about their grades, in the previous mathematics test they had. Then, we create a study group and a mathematician is helping those students for a week. After that, they take another mathematics test and we ask them about their grades.
We are interest to draw conclusions if the study group had an effect on the students’ grades or not. So, we don’t care what was the grade before and after the study group but only if there was a difference in the grade. For this reason, for every student, we calculate the difference between the first and the second grade, and we would like to test if that difference was 0 or not. (Obviously, we are not interested to focus if the difference was 0 or not in the sample, but rather, if we are able to include all the students of the city in our testing, would there be any difference or not?) Thus, we use the following hypothesis testing:

Null Hypothesis:
H0: μ1 = 0 (no differences in the grades of the first and second test)

Alternative Hypothesis:
H1: μ1<>0 (there are differences in the grades of the first and the second test)

In this case, we are using a paired-sample t-test to draw our conclusions.

In preactical terms though, a paired-sample t-test is similar to a one-sample t-test. This is becasue we actually take the differences in the paired-sample and we create a new sample that corresponds thosee diffrerences. After that, we proeceed in the same way as in the one-sample t-test


## Note:

In exercises, we often see that a z-test is used to draw conclusions. This implies that we have enough information about our population from previous research. In reality though, in most cases we don’t have enough information about our population, and this is why we use a t-test.

For large samples though, both the z-test and the t-test will give us the same results as the t-distribution tends to become similar to a normal distribution, as it can be seen in this graph (red=normal distribution, blue=t distribution):

[t-distributuion approaching normal distribution graph](https://www.desmos.com/calculator/xm56tvvalh)
