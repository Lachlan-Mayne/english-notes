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

We want to choose $p$ that maximises the function $$