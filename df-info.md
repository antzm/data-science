Degrees of Freedom

Let's imagine that a university would like to conduct a research on nutritional habits and is looking for volunteers to participate in the research.

They need a sample of exactly 100 people and, without going into further details, after a few days 100 people are waiting in the auditorium for their briefing on the research.

At this time, our sample has 100 degrees of freedom. At any time, if some of the participants change their mind, they can leave from the research and they will be replaced by new participants from a waiting list. The only thing we need, is that the total number of the participants should be 100. At this time, anyone is free to leave and anyone is free to take the place of the person who leaves. Should they wish, all 100 participants can leave and they will be replaced by 100 new volunteers. Currently, there is absolutely no constraint. This is why we have 100 degrees of freedom.

After a while, the people in the auditorium fill an online form with their ages, and the mean value of their ages is calculated. The research has just begun!

Let's say now that the mean value is 40 years old. Nice! We just lost 1 degree of freedom! Why? Because from now on, if some of the participants would like to leave, they can only be replaced by certain people, because the mean value, which is 40 years old, should remain the same.

Thus, as soon as we calculated the mean value of the participants age, we extracted a piece of information from our sample. Extracting this piece of information, is like we placed a constraint on our sample that from now, our sample follows. This is not just a sample anymore but a sample with a mean value of 40. From now on, participants can leave, new participants can join, but the mean value should remain the same. So, we placed 1 constraint to our sample and this is why we lost 1 degree of freedom and we now have 99 degrees of freedom.

Next, we use the ages of the participants and we calculate the variance. The sample size is n=100 but in order to calculate the variance we divide with n-1 = 99. Why? Because we have already lost 1 degree of freedom. We have already extracted 1 piece of information (mean) from our sample, and we have put 1 constraint to our sample. Now, we are extracting another piece of information (variance) and so we are putting a new constraint to our sample and the degrees of freedom, from now on, are n-1-1 = 98.

It's like saying to our sample: Dear sample, from now on you should follow 2 rules:
Rule 1. You should have a mean value of 40
Rule 2. You should have a variance of 400 (which corresponds to a standard deviation of 20)

So, any participants who would like to leave the research, should be replaced only by participants who will not alter the mean value and the variance of the sample.

And then we continue and extract more information from our sample. And with every new piece of information we extract, we place new constraints or rules to our sample, and every time we lose 1 or more degrees of freedom (depending on the kind of information we extract).

In general, whenever we see a formula where the logic says that we should divide by n (the sample size) but the actual formula says that we should divide with something smaller than the n, it is because we have lost degrees of freedom on the way and this is something that is always taken into consideration during the calculations.

This is why we need our sample size to be large enough so in the end, after extracting all the information we need, we will still have enough degrees of freedom.

But why do we need to have enough degrees of freedom at the end of our analysis? Because this means that our results are more solid and they generalize much better.

Let's say, for example, that two universities perform a similar nutritional research in a city with 5 million people. The first university uses a sample of 500 volunteers while the second university uses a sample of 50 volunteers.
At the end of the analysis, let's assume that we have 480 degrees of freedom for the first research and 30 degrees of freedom for the second research.

Although the research has ended, theoretically speaking, we could replace some of the participants, with some other participants (provided they follow all the constrains or rules of that sample) and the results of the research would still be the same.

If we were to randomly replace some of the participants in a research with some randomly chosen people from the city, and the constraints of the sample were still true, then we were going to get the exact same results from our research. Which means that our results generalize better.

And the reality is that it's much easier to randomly replace the participants in a sample with 480 degrees of freedom than in a sample with 30 degrees of freedom.

Thus, is better to have enough degrees of freedom at the end of our analysis.
