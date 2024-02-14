# Data Science for sport
- Sport analytics is a sub-branch of data science
Data science is a new field of study, combining:
- Computer programming
- statistics
- exploratory data analysis & visualisation
- Data extraction, cleaning & transformation
- Machine learning & artificial intelligence

Types of data used include:
- Individual performance
- Team performance
- Wearable sensors (smart watches, bike computer)
- Video

It involves binomial probability:
If we have a number of $n$ events with only two possible outcomes, governed by a probability $p$, we say that a random number $x$ has a Binomial distribution

Unfinished Example:
Flipping a coin 5 times
Probability 0.5 heads
$P(x=2)=\frac{5!}{2!(5-2)!}\times(\frac{1}{2})^2$ unfinished line, teacher skipping

In sport, the probability of winning is unknown, so an estimation is calculated, which is known as *maximum likelihood estimation*.
Example: hawks won 1/5 past games, therefore MLE is $p=\frac{x}{n}=\frac{1}{5}=0.2$

We want to choose $p$ that maximises the function $\binom{5}{1}p^1(1-p)^4$
MLE can be done using calculus, e.g. with logs to calculate
e.g. $\ln{P(x)}=\ln{\binom{n}{x}}+x\ln{p}+(n-x)\ln{1-p}$
Then can be derived to find maximum point
Flaw with this method:
- if team hasn't won any games, the probability would be 0

Ability scores:
Imagine the probability of $p_{i,j}$ of team $i$ beating team $j$ depends on the relative abilities of the two teams, $a_i$ and $a_j$
Ability scores aren't constant, they can change throughout the season
