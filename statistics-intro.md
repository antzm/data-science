
# Probability and Statistics Main Concepts


## Probablilities

* Flipping a coin:
Every time we flip a coin, there's a 50% probablility that head will appear, and 50% probablility that tails will appear. In other words, the probablity for each outcome is 0.5 and so, the total probablility for both outcomes is 1, something which is very important in the probablility theory, as the sum of the indivdual outcomes is always 1, or 100%.

* Throwing a dice:
When we throw a dice, there are 6 different outcomes and each one has a probablility of 1/6 to appear. On the other hand, if we throw simmultaneously 2 dices, there are 6\*6=36 different outcomes, and so each outcome will have a probablility of 1/36 to appear.

* Picking a card:
When we pick a card from a set of playing cards, there's a probability of 1/52 to choose a specific card, as there are 52 cards in the playing set. All the cards have the same probablility to be chosen, so the probability of each card is the total probability, which by definition is always 1, divided by the number of cards which is 52.


## Probability distribution

The probailities of the different outcomes of a random event, will always add to 1 (or 100%), which means that always one of the possible outcomes will take place. For example, depending on the season and the current weather conditions, tommorow, for example, there will be a probability of 0.7 (70%) to rain and a probability of 0.3 (30%) not to rain, but either way, only one of those outcomes will be true.

There also some functions that are used in the probability theory, which help us to predict the outcome of various random events, and those functions are called "probablility distributions". The most common one is the Normal Distribution, which is a bell shaped didtribution used extensively in probablility and statistics.

The common thing in those probability distributions is in their graphs. The area in those graphs always equals 1, which reflects the fact that the outcomes of a random event will always add to 1. 


## Permutations
When the order does matter
	* Permutations with repetition
	* Permutations without repetition

Example 1:  
3 friends (A, B, C) go to a cinema and they sit next to each other.
Their seat arrangment could be either ABC, ACB, BAC, BCA, CAB or CBA.
*Permutations without repetition*

Example 2:
In football predictions, we mark each match as either 1, 2 or X. If there are e.g. 13 matches, then there will be 3*3*3*...*3 = 3^13 different results.
*Permutations with repetition*

Example 3a:
How many 5 letter words can we create, regardles if they have a meaning?
*Permutations with repetition*

Example 3b:
How many 5 letter words can we create, without using a letter twice, regardles if they have a meaning?
*Permutations without repetition*

Example 4a:
How many 5-digit numbers can we create, without using the zero?
*Permutations with repetition*

Example 4b:
How many 5-digit numbers can we create, without using a number twice and without using the zero?
*Permutations without repetition*


## Combinations
When the order doesn’t matter
	* Combinations with repetition
	* Combinations without repetition

Example:  
From 5 students (A, B, C, D, E) we would like to select a team of 2 students to take part in a contest.
The diiferent teams could be either AB, AC, AD, AE, BC, BD, BE, CD, CE, DE. 
*Combinations without repetition*


## Normal distribution

The Normal distribution is the most widely used probability distribution, as it represents a wide variety of cases. For example:

* The time needed to go to work is represented by a normal distribution. Most days of the week it would be something close to a certain value, while rarely the time would be extremely longer or extremely shorter, compared to that value.

* The height of the trees in a forest is around a certain height, while very few trees are extremely tall or extremely short.

* The temperatures in a city are around a certain value, for every season, and only during fews days the temperatures are extrmemly height or extremely low, compared to their usual value.

The Normal distribution therefore can be used in many cases and its main characteristic is that it resembles a bell shaped distribution.


## Population vs Sample

In statistical terminology, a population is anything that we would like to study and thus, it can refer to people, animals, plants but also in any item we could think of.

If we would like to study the people living in a big city, the population we are interested in, is the population of that city. But if we would like to study the grades of the highschool students in that city, then the population we are interested in, is the population of the highschool students.

In a similar way, if we want to study the trees in a forest, then the population we are interested in, is the total number of threes in that forest. But if we would like to study only the fir trees in that forest, then we will define our population as the total number of fir trees in that forest. In case though we are interested only in the fir trees above 2 meters high, then we will define our population as the total number of fir trees in that forest that are above 2 meters height.

In most cases though, the population we are interested to study is so large that it's not possible to study each individual member, as this is something impractical and expensive. For that reason we select just a sample from the population we are interested to study and based on that sample, we draw our coclusions for the entire population.

In that way, we can study just a sample of a few hundred people and draw conclusions for a population of a few million people. The quality though of our research, depends on the good selection of the sample and the usage of the proper statistical methods, in order to draw conclusions that are representative of the entire population.

In practise though, we can never be 100% sure if our conclusions for the entire population are correct, as we never have the chance to study the whole population. If a similar research though, from another researcher at a later time, will draw similar conclusions for that population, then this is good indication that our research was on the right track.

Usually, the only time that we can actually see how good the predictions from the sample were, is when we have access to the complete population, and this is something that happens during elections. In this case, the exit polls represent the sample, while the election results represent the complete population. Obviously, the population conists of the voters who actually vote and the sample is the exit poll that took place on the same day as the election. Thus, depending on how good the exit  polls predicted the actual result, we understand how good the sampling process was, and how good was the use of the statistical methods that were applied.  
The gullops that take place before the elections, are not so representative compared to the exit polls, because some voters may change their vote untill the election day.

There are also cases where although it's possible to have access to the complete population, we are not interested to study the complete population. One example is the number of smart phones that a factory produces. We need to use a sample of those phones for quality tests, but not all the phones that the factory produces. The quality tests may destroy the devices that are tested, so it wouldn't make sense to run a quality test for every phone that the factory produces. Instead, based on the quality tests that take place on a sample of the total phones produced, it helps to understand the quality of the phones produced by that factory, and to improve the manufacturing quality whenever is neccesary.


## Descriptive statistics

Descriptive statistics uses the available data to draw conclusions about what happend in the past. It analyzes the available data and presnts the results in a consice way that can be easily understood and intrpreted. These results though, refer exclusively to the data that was analyzed, while the conclusions from that data, have no broader or more generalized application.

> Descriptive statistics is used by the Data Analysts.


## Inferential statisctis

Inferential statistics on the other hand, not only uses the tools available to the decriptive statistics, but it goes further as it uses the available data from a sample, in oder to make inferences for a population, and also to predict future tendencies based on the available data.

> Inferential statistics is used by the Data Scientists.


## Statistical notation

In statistical notation, both English and Greek letters are used. It's very important though, to understand when the English letters are used, and when the Greek letters are used.

**English letters are always used whenever we refer to a sample:**
   * x bar = sample mean
   * s = sample variance
   * r = sample correlation coefficinet

**Greek letters are always used when we refer to a population:**
   * μ = population mean
   * σ = population standard deviation
   * ρ = population correlation coefficient

In inferential statistics, we use a sample in order to draw conclusions about a population. Thus, we use sample parameters, denoted with English letters, in order to estimate the unknown population parameters, denoted with Greek letters.

The better the quality of the sample, the better will be the estimation of the population parameters.


## Hypothesis testing

In every football game there is a refferee who ensures that the rules of the game are followed by all the players, and so the result of the game is as objective as possible.

It wouldn't make much sense if we had let the teams make such decisions, as each team would tend to favour itself.

The exaxt same approach is used in statistics, because it wouldn't make much sense to let every researcher decide by himeself or by herself, about the quality of his or her own research.

Thus, we also need a referee in statistics that would make decisions in an objective way, as much as possible.

This referee is called "Hypothesis testing" and is used throughout inferential statistics for every single decision that a statistician, a researcher or a data scientist has to make.

In statistics though, the boundaries are not so clear as in a foorball game where, most of the time at lest, it's very clear if there was a goal or not. Instead, in statistics there's no way to be 100% sure that the correct decision has actually been made.

We cannot make decisions with 100% certaintly in statistics, but most of the time we consider that a 95% probability to be correct is acceptable, and usually this is the level of certaintly that most researchers and data scientists use.

In a hypothesis testing we always compare two hypotheses.

The first one is called the null hypothesis, and it always corresponds to A being equal with B.

While the second one is called the alternetive hypothesis, ant it always coresponds to A being different than B.

The important thing to remeber is that the null hypothesis correspons always to being equal, while the alternative hypothesis always corresponds to being different.


## Hypothesis testing - Example 1

Let's assume that a factory produces light bulbs with an average duration of 1000 hours. A new production technique though, will produce light bulbs with an average duration of 1050 hours. The managers though wonder if it woulbe be worthy to switch to the new production techinque, so to advertise that their new bulds last longer.

Using our logic, we would say that 1050 is better than 1000, but things in statistics are somehow different. In our case, we are not comparing the duration values of two bulbs, but the average duration of two sets of bulbs. And also, those two sets represent just two small samples of the millions of the bulbs that the factory produces.

If we make a histogram for each sample, we get a distribution for that sample where we can see the average value and the variance.

But in statistics, we are not interested for the sample itself but rather for the population, from where that sample was collected.

In this case, our approach is to statistically test if those two samples belong to the same population (with an average of 1000) or if they belong to two different populations (with averages of 1000 and 1050 respectively).

Thus, the null hypothesis H0 would be  

H0: μ1=μ2 or  
H0: μ1-μ2=0  

(μ1-μ2=0 means that there are no differences in the means, and this is why we call it the null hypothesis)

While the alternative hypothesis Η1 would be

H1: μ1<>μ2

Where we want to test if the means are different

In some other cases though, we could also use these alternatives hypotheses:

Η1: μ1<μ2 or Η1: μ1>μ2

But usually, the most common case is to test for inequality in the alternative hypothesis, which is called a two-sided test. If though we only test for greater or smaller in the alternative hypothesis, it's called one-sided test.

> The important thing to remember is that the null hypothesis H0 always tests for equality while the alternatve hypothesis H1 always tests for inequality (either not equal, or greater, or smaller)


## Hypothesis testing - Example 2

Let's use a different example now. A factory produces light bulbs and has two lines of production, A and B. Both lines produce the same product but the machinery used, and the corresponding callibration, may be a little different between the two lines of production. Thus, we suspect that there might be a difference in the quality of the light bulbs produced, between the two lines.

In this case, we have two populations. Population A corresponds to all the light bulbs produced from the production line A, while population B corresponds to all the light bulbs produced from the production line B.

Theoritically, to find the exact average duration of the light bulbs in population A, we should take every single light bulb produced in line A, and then test it to see how long it will last. Obviously this is not possible, and for this reason we take only a small sample and based on that sample, we draw conclusions for the entire population.

The exact same logic applies also to the light bulbs produced in the production line B.

In this example, our purpose is to find if there is a difference in the quality of the ligh bulbs between production lina A and production line B.

Theoritically, if we had the complete data for the entire population A, and also the complete data for the entire population B, we would have drawn the data distribution for population A, and the data distribution for population B, and then we would compare those distributions.

Unfortunately though, we don't have the complete data for population A or B. For this reason, we estimate the population distribution based on a sample from population A, and a sample from population B.

Then, we compare those estimated population distributions. If they overlap at a great extent, then we consider that the two population distributions are identical and only by chance they have a small difference between them.

On the other hand, if they overap by a small percentage, then we consider those populations to be two distinct populations.

And here we come to the big question in statistics. How can we decide if two populations are actually identical, or if they are actually two different populations?
