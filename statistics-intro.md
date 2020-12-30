
# Probability and Statistics - Main Concepts

* [Probabilities](#Probabilities)
* [Probability distribution](#Probability-distribution)
* [Permutations](#Permutations)
* [Combinations](#Combinations)
* [Normal distribution](#Normal-distribution)
* [Other probability distributions](#Other-probability-distributions)
* [Population vs Sample](#Population-vs-Sample)
* [Descriptive statistics](#Descriptive-statistics)
* [Inferential statistics](#Inferential-statistics)
* [Statistical notation](#Statistical-notation)
* [Hypothesis testing](#Hypothesis-testing)
* [Hypothesis testing - Example 1](#Hypothesis-testing---Example-1)
* [Hypothesis testing - Example 2](#Hypothesis-testing---Example-2)
* [Hypothesis testing - statistical tests](#Hypothesis-testing---statistical-tests)
* [Hypothesis testing - level of significance](#Hypothesis-testing---level-of-significance)
* [Hypothesis testing - Choosing between H0 and H1](#Hypothesis-testing---Choosing-between-H0-and-H1)
* [Hypothesis Testing - Clarification Example 1](#Hypothesis-Testing---Clarification-Example-1)
* [Hypothesis Testing - Clarification Example 2](#Hypothesis-Testing---Clarification-Example-2)
* [One Way vs Two Way Statistical Tests](#One-Way-vs-Two-Way-Statistical-Tests)
* [Hypothesis testing - A metaphor](#Hypothesis-testing---A-metaphor)
* [Hypothesis Testing - Out of the ordinary](#Hypothesis-Testing---Out-of-the-ordinary)
* [Hypothesis Testing - Overview](#Hypothesis-Testing---Overview)
* [Hypothesis Testing - Results interpretation](#Hypothesis-Testing---Results-interpretation)
* [Hypothesis testing with more than two populations](#Hypothesis-testing-with-more-than-two-populations)
* [Importance of the ANOVA method](#Importance-of-the-ANOVA-method)


## Probabilities

* Flipping a coin:
Every time we flip a coin, there's a 50% probability that head will appear, and 50% probability that tails will appear. In other words, the probability for each outcome is 0.5 and so, the total probability for both outcomes is 1, something which is very important in the probability theory, as the sum of the individual outcomes is always 1, or 100%.

* Throwing a dice:
When we throw a dice, there are 6 different outcomes and each one has a probability of 1/6 to appear. On the other hand, if we throw simultaneously 2 dices, there are 6\*6=36 different outcomes, and so each outcome will have a probability of 1/36 to appear.

* Picking a card:
When we pick a card from a set of playing cards, there's a probability of 1/52 to choose a specific card, as there are 52 cards in the playing set. All the cards have the same probability to be chosen, so the probability of each card is the total probability, which by definition is always 1, divided by the number of cards which is 52.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Probability distribution

The probabilities of the different outcomes of a random event, will always add to 1 (or 100%), which means that always one of the possible outcomes will take place. For example, depending on the season and the current weather conditions, tomorrow, for example, there will be a probability of 0.7 (70%) to rain and a probability of 0.3 (30%) not to rain, but either way, only one of those outcomes will be true.

There also some functions that are used in the probability theory, which help us to predict the outcome of various random events, and those functions are called "probability distribution". The most common one is the Normal Distribution, which is a bell shaped didtribution used extensively in probability and statistics.

The common thing in those probability distributions is in their graphs. The area in those graphs always equals 1, which reflects the fact that the outcomes of a random event will always add to 1.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Permutations
When the order does matter
	* Permutations with repetition
	* Permutations without repetition

Example 1:  
3 friends (A, B, C) go to a cinema and they sit next to each other.
Their seat arrangement could be either ABC, ACB, BAC, BCA, CAB or CBA.
*Permutations without repetition*

Example 2:
In football predictions, we mark each match as either 1, 2 or X. If there are e.g. 13 matches, then there will be 3*3*3*...*3 = 3^13 different results.
*Permutations with repetition*

Example 3a:
How many 5 letter words can we create, regardless if they have a meaning?
*Permutations with repetition*

Example 3b:
How many 5 letter words can we create, without using a letter twice, regardless if they have a meaning?
*Permutations without repetition*

Example 4a:
How many 5-digit numbers can we create, without using the zero?
*Permutations with repetition*

Example 4b:
How many 5-digit numbers can we create, without using a number twice and without using the zero?
*Permutations without repetition*  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Combinations
When the order doesn’t matter
	* Combinations with repetition
	* Combinations without repetition

Example:  
From 5 students (A, B, C, D, E) we would like to select a team of 2 students to take part in a contest.
The different teams could be either AB, AC, AD, AE, BC, BD, BE, CD, CE, DE. 
*Combinations without repetition*  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Normal distribution

The Normal distribution is the most widely used probability distribution, as it represents a wide variety of cases. For example:

* The time needed to go to work is represented by a normal distribution. Most days of the week it would be something close to a certain value, while rarely the time would be extremely longer or extremely shorter, compared to that value.

* The height of the trees in a forest is around a certain height, while very few trees are extremely tall or extremely short.

* The temperatures in a city are around a certain value, for every season, and only during few days the temperatures are extremely height or extremely low, compared to their usual value.

The Normal distribution therefore can be used in many cases and its main characteristic is that it resembles a bell shaped distribution.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Other probability distributions

Besides the Normal Distribution, there are numerous other probability distributions and one difficulty in statistics lies in choosing the appropriate probability distribution for each case.

The most commonly used probability distributions are:

* Binomial distribution
* Poisson distribution
* Normal distribution
* Student's t distribution
* Chi square distribution
* F distribution  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Population vs Sample

In statistical terminology, a population is anything that we would like to study and thus, it can refer to people, animals, plants but also in any item we could think of.

If we would like to study the people living in a big city, the population we are interested in, is the population of that city. But if we would like to study the grades of the high school students in that city, then the population we are interested in, is the population of the high school students.

In a similar way, if we want to study the trees in a forest, then the population we are interested in, is the total number of threes in that forest. But if we would like to study only the fir trees in that forest, then we will define our population as the total number of fir trees in that forest. In case though we are interested only in the fir trees above 2 meters high, then we will define our population as the total number of fir trees, in that forest, that are above 2 meters height.

In most cases though, the population we are interested to study is so large that it's not possible to study each individual member, as this is something impractical and expensive. For that reason, we select just a sample from the population we are interested to study and based on that sample, we draw our conclusions for the entire population.

In that way, we can study just a sample of a few hundred people and draw conclusions for a population of a few million people. The quality though of our research, depends on the good selection of the sample and the usage of the proper statistical methods, in order to draw conclusions that are representative of the entire population.

In practice though, we can never be 100% sure if our conclusions for the entire population are correct, as we never have the chance to study the whole population. If a similar research though, from another researcher at a later time, will draw similar conclusions for that population, then this is good indication that our research was on the right track.

Usually, the only time that we can actually see how good the predictions from the sample were, is when we have access to the complete population, and this is something that happens during elections. In this case, the exit polls represent the sample, while the election results represent the complete population. Obviously, the population consists of the voters who actually vote and the sample is the exit poll that took place on the same day as the election. Thus, depending on how good the exit  polls predicted the actual result, we understand how good the sampling process was, and how good was the use of the statistical methods that were applied.  
The gallops that take place before the elections, are not so representative compared to the exit polls, because some voters may change their vote until the election day.

There are also cases where although it's possible to have access to the complete population, we are not interested to study the complete population. One example is the number of smart phones that a factory produces. We need to use a sample of those phones for quality tests, but not all the phones that the factory produces. The quality tests may destroy the devices that are tested, so it wouldn't make sense to run a quality test for every phone that the factory produces. Instead, based on the quality tests that take place on a sample of the total phones produced, it helps to understand the quality of the phones produced by that factory, and to improve the manufacturing quality whenever is necessary.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Descriptive statistics

Descriptive statistics uses the available data to draw conclusions about what happened in the past. It analyzes the available data and presents the results in a concise way that can be easily understood and interpreted. These results though, refer exclusively to the data that was analyzed, while the conclusions from that data, have no broader or more generalized application.

> Descriptive statistics is used by the Data Analysts.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Inferential statistics

Inferential statistics on the other hand, not only uses the tools available to the descriptive statistics, but it goes further as it uses the available data from a sample, in order to make inferences for a population, and also to predict future tendencies based on the available data.

> Inferential statistics is used by the Data Scientists.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Statistical notation

In statistical notation, both English and Greek letters are used. It's very important though, to understand when the English letters are used, and when the Greek letters are used.

**English letters are always used whenever we refer to a sample:**
   * x bar = sample mean
   * s = sample variance
   * r = sample correlation coefficient

**Greek letters are always used when we refer to a population:**
   * μ = population mean
   * σ = population standard deviation
   * ρ = population correlation coefficient

In inferential statistics, we use a sample in order to draw conclusions about a population. Thus, we use sample parameters, denoted with English letters, in order to estimate the unknown population parameters, denoted with Greek letters.

The better the quality of the sample, the better will be the estimation of the population parameters.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing

In every football game there is a referee who ensures that the rules of the game are followed by all the players, and so the result of the game is as objective as possible.

It wouldn't make much sense if we had let the teams make such decisions, as each team would tend to favor itself.

The exact same approach is used in statistics, because it wouldn't make much sense to let every researcher decide by himself or by herself, about the quality of his or her own research.

Thus, we also need a referee in statistics that would make decisions in an objective way, as much as possible.

This referee is called "Hypothesis testing" and is used throughout inferential statistics for every single decision that a statistician, a researcher or a data scientist has to make.

In statistics though, the boundaries are not so clear as in a football game where, most of the time at lest, it's very clear if there was a goal or not. Instead, in statistics there's no way to be 100% sure that the correct decision has actually been made.

We cannot make decisions with 100% certainty in statistics, but most of the time we consider that a 95% probability to be correct is acceptable, and usually this is the level of certainty that most researchers and data scientists use.

In a hypothesis testing we always compare two hypotheses.

The first one is called the null hypothesis, and it always corresponds to A being equal with B.

While the second one is called the alternative hypothesis, ant it always corresponds to A being different than B.

The important thing to remember is that the null hypothesis corresponds always to being equal, while the alternative hypothesis always corresponds to being different.  

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - Example 1

Let's assume that a factory produces light bulbs with an average duration of 1000 hours. A new production technique though, will produce light bulbs with an average duration of 1050 hours. The managers though wonder if it would be be worthy to switch to the new production technique, so to advertise that their new bulbs last longer.

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

> The important thing to remember is that the null hypothesis H0 always tests for equality while the alternative hypothesis H1 always tests for inequality (either not equal, or greater, or smaller)

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - Example 2

Let's use a different example now. A factory produces light bulbs and has two lines of production, A and B. Both lines produce the same product but the machinery used, and the corresponding calibration, may be a little different between the two lines of production. Thus, we suspect that there might be a difference in the quality of the light bulbs produced, between the two lines.

In this case, we have two populations. Population A corresponds to all the light bulbs produced from the production line A, while population B corresponds to all the light bulbs produced from the production line B.

Theoretically, to find the exact average duration of the light bulbs in population A, we should take every single light bulb produced in line A, and then test it to see how long it will last. Obviously this is not possible, and for this reason we take only a small sample and based on that sample, we draw conclusions for the entire population.

The exact same logic applies also to the light bulbs produced in the production line B.

In this example, our purpose is to find if there is a difference in the quality of the light bulbs between production line A and production line B.

Theoretically, if we had the complete data for the entire population A, and also the complete data for the entire population B, we would have drawn the data distribution for population A, and the data distribution for population B, and then we would compare those distributions.

Unfortunately though, we don't have the complete data for population A or B. For this reason, we estimate the population distribution based on a sample from population A, and a sample from population B.

Then, we compare those estimated population distributions. If they overlap at a great extent, then we consider that the two population distributions are identical and only by chance they have a small difference between them.

On the other hand, if they overlap by a small percentage, then we consider those populations to be two distinct populations.

And here we come to the big question in statistics. How can we decide if two populations are actually identical, or if they are actually two different populations?

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - statistical tests

Almost everything we do in statistics, involves various hypotheses tests. So, first step is to create a Null Hypothesis and an Alternative Hypothesis and then, choose the proper statistical test in order to check which one of the two hypotheses we should accept and which one we should reject.

In a football game, we choose an experienced referee, in order to objectively judge if the rules are followed. For the same reason, we choose an experienced referee for a basketball game. But it wouldn't make much sense to choose a football referee in a basketball game, and vice versa.

The same principle applies to statistics. There are various statistical tests available, like z-test, t-test, F-test, x square test etc. and the difficulty in statistics lies in choosing the correct statistical test for each situation. Otherwise, if we choose the wrong statistical test it would be like using a basketball referee in a football game.

Then, depending on the results of the statistical test, we would either choose the Null Hypothesis or the Alternative Hypothesis.

So, every decision in statistics involves a Hypothesis Testing and depending on the situation, we choose the proper statistical test which will tell us, in an objective way, if we should accept the Null or the Alternative Hypothesis.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - level of significance

One key aspect in hypothesis testing is the level of significance. Regardless of the statistical test that we will use, we will make our decisions based on the level of significance we choose. A different level of significance, will probably give us different results.

As it has been mentioned earlier, in Hypothesis testing we use the Greek letter μ (μ1 and μ2) to compare two populations. We use Greek letters, because we refer to populations, and hypothesis testing is always about testing populations.

Now, every time we compare two populations, we wonder if those population distributions are actually two different distributions or not. As both populations are unknown, we estimate the populations based on the two samples. So, different samples, could give us different results, and this is why we should use the proper sampling technique.

But how we will decide if two populations are actually one population (appearing as two because of the sampling we used) or if they are actually two different populations?

It all depends on the overlapping of the two population distributions. Usually, when the overlapping between the two populations is more than 5%, then we consider that the two populations are actually one. Whenever though the overlapping is 5% or less, then we consider that the two populations are actually two different populations.

This threshold of 5%, which determines our decisions, is called the level of significance and it's symbol is the Greek letter α, and usually we use α=0.05 or α=5% (rarely though, we also use α=1% or α=0.01).

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - Choosing between H0 and H1

Regardless of the statistical test that we will use, we will always get a result which is a probability number between 0 and 1. When we choose the level of significance at 5% (0.05), then we have these two options.

Probability result:
   * Between 0.05 and 1 (0.05, 1]
   * Between 0.00 and 0.05 [0.00, 0.05]

If the result is in the range (0.05, 1], then the two population distributions overlap more than 5% and so the two distributions are actually just one, and only by chance they appear as two different distributions. In this case, we accept the null hypothesis H0 which states that the two distribution populations are equal (μ0 = μ1).

On the other hand, if the result is in the range [0.00, 0.05], then the two population distributions overlap less than 5% and so they are actually two different distributions and thus, we accept the alternative hypothesis H1 which states that the two distribution populations are different (μ0 <> μ1).

Similarly, if we choose the level of significance at 1% (0.01) then we have two options:

Probability result:
   * Between 0.01 and 1 (0.01, 1]
   * Between 0.00 and 0.01 [0.00, 0.05]

Thus, when the probablity result is 0.01 and greater, then we accept the H0, as we consider that the two distributions are actually the same.

On the other hand, if the probability result is 0.01 and smaller, then we accept the H1, as we consider that the two distributions are actually two different distributions.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis Testing - Clarification Example 1

It may look strange that we can come to a conclusion that two population distributions are actually just one, but we should always remember that in statistics we are not comparing just numbers, but actually we are always comparing sets of numbers, so the comparison process is foundamentaly different.

As an example, we could consider a forest and a researcher who would like to measure the height of the trees in that forest. It is a large forest though and there are thousands of trees in it, but the reasearcher is able to measure only 30 trees and based on that result, to draw conclusions about the whole forest.

But how will the researcher select those 30 trees? One approach would be to use a map of the forest and split the map into e.g. 100 squares and then to randomly select only 30 of those squares. After that, the researcher will measure one tree in each square, e.g. the tree that is closest to the center of that square.

Using this approach, the resarcher will randomly select and measure 30 trees, and based on that sample, the researcher will estimate the average height of all the trees in the forest.

As we understand though, if 2 researchers follow independently this exact procedure, they will come up with 2 different estimations for the forest. To be exact, 2 different population distributions that actually depict the exact same forest. The reason this happens, is that each researcher makes estimations based on a different sample, and obviously no two samples would ever be the same.

But the forest is just one, and it has only one population distribution which is unknown (because no one ever measuered the height of all the trees). So, one reasercher says that "this is the population distribution" while the other researcher says "no, this is the population distribution". But which one is actually the correct distribution?

If we perform a Hypothesis Test in this case, between the results of the two researchers, we will have:

H0: μ1 = μ2  
Null Hypothesis: The estimate for the μ1 is equal with the estimate of the μ2, or, the two populations we are comparing, are actually one. In other words, both samples were actually collected from the exact same population. As for the terminology, the population mean which is based on the first sample is μ1, while the population mean which is based on the second sample is μ2. The sample means are x1 bar and x2 bar respectively, and based on those means we estimate the population means μ1 and μ2. The x1 bar and x2 bar are calulated with accuracy, as we use the sample data to calculate them. The μ1 though and the μ2 are unknown and we use the x1 bar and the x2 bar to estimate them. As mentioned before, English letters refer always to the samples and can be accurately calculated, while Greek letters refer always to the populations and can only be estimated.

H1: μ1 <> μ2  
Alternative Hypothesis: The estimate for the μ1 is not equal with the estimate of the μ2, or, the two populations are different and the samples came from two different populations.

In this case, the expected result would be to accept the Null Hypothesis as both samples represent the same population, but if the sampling process was not representative of the population, there is a chance to accept the Alternative Hypothesis. In the first case, we get correcet results, but in the second case we get wrong results.

Obvisously, here we know beforehand that we have just one population, but in real situations we never know such information and we always try to find out if two populations are actually the same or not.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis Testing - Clarification Example 2

In this example, we want to compare two varities of wheat. The first one is the variety that is currently being  cultivated by the farmers, while the second one is a new variety with higher yield, at least in the laboratory, and we want to test if it also has a higher yield in the field.

In this example, we have seeds of the current variety and seeds of the new variety. We will compare the wheat plants that will grow from those seeds. This is our sample, while the population in this case are all the future plants that will grow from the seeds of each variety.

So, in this example, the null and the alternative hypotheses will be as follow:

H0: μ1 = μ2

Η1 = μ1 < μ2

Where μ1 is the population mean of the existing variety, and μ2 is the population mean of the new variety. The null hypothesis states that both varieties have actually the same population mean and only by chanche there is a difference between the two population mean estimates .

The alternative hypothesis though, doesn't state that there is difference between the two varieties, but it is more specific as it states that the μ2 population mean is larger that the μ1 population mean.

The reason is that we are not interested for a new variety that has just a different mean yield from the existing variety, but instead we are only interestd for a variety that has a higher mean yield. Otherwise it wouldn't make any sense for the farmers to cultivate the new wheat variety.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## One Way vs Two Way Statistical Tests

As it has been mentioned earlier, the null hypothesis has always the equal sign in its comparison i.e. H0: μ1=μ2 and is called null because it could also be written as H0: μ1-μ2=0 which states that there are no differences between the two population means.

Although it was also mentioned, we should always remember that hypothesis testing is always about populations and we never use hypothesis testing for samples. This is the reason why in hypothesis testing we use Greek letters like μ1 and μ2 for the population means. 

Now, the alternative hypothesis examines the unequal i.e. Η0: μ1 <> μ2 and this is a two way statistical test. But there are also times where we are not interested if the populations are different but we want to know more specifically if the first population mean is greater or smaller compared to the second population mean.

In this case, the alternative hypothesis would be written, depending on the situation we are testing, either as

H1: μ1 > μ2

or

H1: μ1 < μ2

So, in this case we are interested only in one of the sides of the population distribution, either the left or the right side, and not both sides as we did with with the hypothesis H1: μ1 <> μ2

This is why we call these statistical tests as one-way tests.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing - A metaphor

In hypothesis testing we compare two population distributions and if they overlap a lot, then we considered them as one and the same population distribution.

In a normal distribution, using a two-way test and a 5% level of significance, we will mark with a different colour the 2.5% of the right tail and the 2.5% of the left tail of the distribution. Those two areas are extremely important in every distribution.

Then, when we compare two normal distributions (like the ones just discribed) we focus on the tails of the two distributions. Let's assume that the two distributions are coloured green and that the 2.5% at the end of each tail is coloured red.

If the green color of one distribution overlaps with the green color of the other distribution, then both distributions are the same. In other words, if we were able to take better samples, we would have seen that actually both distributions would be almost similar, and this why we considered them as one and the same distribution.

Also, when a red colour from one distribution overalps with a green color of the other distribution, we would also consider those distributions as one.

If though, and only if, the red color from one distribution overlaps only with the red color of the other distribution, then we have two different distributions. It's the case when we select the alternative hypothesis.

What about though if the two distribution don't overlap at all? Obviously, in this case we would also select the altrenative  hypothesis as we have two different populations. But to be exact, even in this case the red parts of the distributions ovelap because the tails of the normal distribution extend to infinity.

Now, let's think about a methaphor for a while. Let's imagine that the center 95% of a normal distribution corrsponds to a football field and that the two tails, of 2.5% each, correspond to the goalposts. The football field is green like the center part of our normal distribution while the goalposts, that correspond to the two tails of the distribution, we would consider them as red, just like the red tails of our normal distribution.

Every football game gets really excited when a team scores a goal, otherwise the game may look a little boring and uniteresting without any goals at all. In other words, if the game takes place only in the green part of the field, it's a little boring, and it gets interesting only when the ball crosses the red part of the field, whenever a goal is scored.

Well, the exact same logic applies also to the normal distribution. Things are a little boring in the main green part of the distribution, while they get really intereing in the red part of the distribution, or in other words in the 2.5% of both tails of the distribution.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis Testing - Out of the ordinary

Rephrasing the above, the null hypothesis represents the status-quo, the ordinary, the existing situation, while the alternative hypotheis represents the out of the ordinary, the unusual, the new discovery.

When making reasearch, the data from a research experiment will either reinforce the existing situation (accepting the null hypothesis) or point towards a new interesting concept or maybe a new discovery (accepting the alternative hypothesis).

So, in other words, the existing situation is represented with the center 95% of the Normal distribution, while the 2.5% of the left and the right tale represent the new discovery, either a small or a bigger discovery. Those red areas, show the place in the distribution where the interesting, the different and the unusual take place. And whenever we reach those areas, we are actually leaving the existing distribution and we are moving towards a new distribution, which lies either in the right or the left side of that distribution.

To clarify things a little more, if the statistical test used gives us a probality inside the 2.5% of the two tails, then this means that the tails of the distribution, which corresponds to the populatation with a mean of μ1, actually they don't belong to the μ1 population but in fact are the tails of the μ2 population and it just happens that the tails of the μ1 and μ2 distribution simply overlap.

Let's also picture the situation in a different way. We have two distributions, next to each other, and either they overlap a little or they overal a lot. How do we decide if those distributions are actually one or two? We will use a statistical test which will act as a referee and it will draw a vertical line between those distributions. If that line goes through the 95% main part of the first distribution, then the two distributions are the same. But if the line goes through the 2.5% of either tail, of the first distribution, then the two distributions are different.

The first distribution is considered the one that we are using in the null hypothesis, while the second distribution is considered the one we are comparing with in the alternative hypothesis.

So, whenever the statistical test we are using tells us to move outside of the 95% main part of our existing distribution, towards the newer distribution that we are comparing, then in practical terms this means that we have just discovered something, which is either something of a smaller or something of a greater importance.

On the other hand though, if we accept the null hypothesis then this means that we are actually verifying the discoveries of other previous researchers, as we come to the conlusion that what has been accepted as true all this time, is actually true.

As an example, let's assume that a researcher would like to test the hypothesis that the emotional intelligence EQ (or emotional quotient) is affected by our exposure to sunlight. And let's assume that some previous researchers who studied this hypothesis in the past, found that there is no effect between EQ and exposure to sunlight.

So, this researcher takes a sample from the people who live in the northern part of a country, with less sunshine, and another sample from the people living in the south part of the country, which has more sunshine.

The null hypothesis is that there are no differneces in the mean EQ values between the north and the south part of the country. In this case, if the statistical test tells us to accept the null hypothesis, then the researcher is simply reinforcing the existing research.

On the other hand, if the researcher will find out that the null hypothesis should not be accepted, then he or she has obviously discovered something new which is completely different from what the previous researchers had discovered.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis Testing - Overview

The important thing is to rember that we construct a null hypothesis H0 where we test fo equality, and an alternative hypothesis H1 where we test for inequality.

It would be a mistake if we would construct a null hypothesis to test for inequality, as in the null hypothesis we use always the equal sign and we always test for equality.

Only in the alternative hypothesis we test for inequality, either as μ1<>μ2, or μ1<μ2, or μ1>μ2.

The decision if we would accept the null hypothesis or the alternative hypothesis, depends on the results of the statistical test that we will use. In the vast majority of cases, if the statistical result is between 0 and 5% [0, 0.05], then we accept the alternative hypothesis, while if the statistical result is greater that 5% and up to 100% (0.05, 1.00), then we accept the null hypothesis.

The construction of a null hypothesis and an alternative hypothesis, it always follows the exact same logic. Depending now on each case, we will select the appropriate statistical test which will tell us, in an objective way, if we should accept the null or the altrenative hypothesis.

In this way, every decision we take in statistics, is done using an objective referee which decides if we should select a null or an alternative hypothesis. That objective referee is called the statistical test.

Although there is a great number of statistical tests, in the vast majority of cases we only use just a few of them. Knowing though which statistical test to choose for in a ceratin case, is as essential and very important knowledge in statistics.

Only by having a deep understanding of the main statistical tests, and their corresponding probability distributions, a data scientist can choose the proper test for each case. Otherwise, choosing a wrong statistical test would probably create some meaningless results that will have no connection to the real situation.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis Testing - Results interpretation

When we are using a statistical program to compare two sets of data, we will get as a result a number representing the probability that those two sets are statistically the same, or they are statistically different. 

If the result is greater than 0.05 then it means that the probalility that those two sets are actually the same is higher than 5% and thus is considered that those two sets actully are the same as they belong to the same population.

If though the result is 0.05 or less, then this means that the probability of those two sets belonging to the same population is 5% or less and so we consider that those two tests belong in two different populations.

The sets of data that we are comparing, are actually two samples from two populations, and what we are actually trying to understand is, whether those two samples belong to the same or in different populations.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Hypothesis testing with more than two populations

In the beggining of the 20th century, the world population was rising, the urbanaziation was increasing and the demand for food was increasing at a greater rate compared to what the farmers would be able to supply. The only solution was to introduce new varities with grater yield. Unfortunately though, a new wheat variety needed several years to be introduced and one reason for this, was the lack of the proper statistical tests that would easily distinguish the most promising varieties out of a very large number of new varities.

The solution to this problem was introduced by Fischer, who was trying to find an easy way to compare a large number of wheat varities at once. And at this point, the modern era of statistics begun.

Fisher itroduced the F-distribution and the ANOVA (ANalysis Of VAriance) statistical tests.

When we are using the ANOVA method, the null hypothesis and the alternative hypothesis are as follows:

H0: μ1=μ2=μ3=...=μn (where n is the last population mean we are testing)

H1: At least one of the μ1, μ2, μ3...μn is not equal with the other population means

Depending on the result of the ANOVA test we will either accept the nulll hypothesis, meaning that e.g. all the wheat varieties we are testing are statistically the same as the existing cultivated variery μ1, or if we accept the alternative hypothesis, then at least one variety is statistically different from the existing cultivate variety μ1.

In the case of wheat varieties, Fisher was able with just one statistical test, to throw away a numerous number of new varieties that were no better that the existing variety.

Only when the alternative hypothesis was accepted, then that particular group of varieries was tested again in order to find which one was the best variety of all the ones that were tested.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Importance of the ANOVA method

It may seem somewhat exaggerating but ANOVA was actually one of the greatest discoveries ever made. The reason is that for the first time ever, it allowed scientists to easily test a large number of new varities and to find the most promising varieties in a short ammount of time. This allowed scientists to introduce new varities for cultivation, with higher and higher yields, that helped to meet the increasing demand for worldwide food.

It should also be taken into consideration that there were no computers at that time, and for this reason ANOVA was the perfect approach because with few calculations, it allowed the comparison of a large number of varieties. Something that otherwise would have been impossible.

Nowadays, 100 years after it's discovery, ANOVA is still a great method to compare a big number of populations at once and see if there is at least one population which is different than all the others, or if all the populations we are comparing are actually the same.

ANOVA gives us only information if there is at least one population that is different from the other but it doesn't provide any information about which one or which ones of the populations we are comparing are different.

For this reason, when the results of the ANOVA analysis shows that there is at least one population that is different, then we need to proceed further with more specialized stastical tests in order to find the populations that differe from all the others.

*[Index](#Probability-and-Statistics---Main-Concepts)*  


## Linear regession

Whenever we have two variables, X and Y, where X affects the Y, then we call the X as independent variable and the Y as dependent variable.

When we draw a scatter plot of those two variables, and have a look at the points in the graph, we can understand what kind of relationship exists between those two variables.

If the points in the graphs can be approximated with a straight line, then we can use linear regression to predict the value of Y based on the value of X.

The equation of a linear regression model has the form 'y=ax+b' and given the x we can predict the value of y.

In this equation, a is the slope of the line and b is the y intercept.


## Multiple linear regression

Most of the times, there are more than one independent variables that affect our dependent variable. In those cases, we can use the multiple linear regression to be able to create a more accurate model.

Assuming we have three independent variables (x1, x2, x3), the equation of our model would be:

y = ax1 + bx2 + cx3 + d


## Correlation r and r-squared

Correlation shows us, in a scale from -1 to 1, how good our data is represented by a line. If the correlation is negative, then this means that as our independent variable is increasing, our dependent variable is decreasing, while positive correlation means that as our independent variable is increasing, our dependent variable is also increasing, while correlation close to zero means that changes in the independent variable does not affect the dependent variable.

The correlation is measured using r while the r squared, taking values from 0 to 1, shows how well our indpendent variable explains our dependent variable.

The closer to 1 our r-squared, the better our linear regression model will be. A good model is considered the one who has an r-squared above 0.7 but it actually something subjective.

To decide in an objective way if our r-squared is good or not, we should use a hypothesis testing where we will test the following null and alterneative hypothesis:

H0: r-squared = 0

H1: r-squared <> 0

Meaning that the null hypothesis will test if the r-squared is statistically not significant (statistically, equal to 0) and the alternative hypothesis will test that the r-squared is statistically significant (statistically, different from 0).

Referring to what was mentioned earlier, the r and r-squared always refer to a sample. Whenever though we refer to a population, we use the Greek letters ρ and ρ-square.

This is because in statistics, we use English letters for the samples and Greek letters for the populations.

Thus, to test if there's statistically significant correlation in a population, we will use the following hypothesis testing:

H0: ρ = 0

H1: ρ <> 0
