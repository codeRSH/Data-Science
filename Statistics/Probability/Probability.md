# Probability

## Terminology

* Probability is a measure that is associated with how certain we are of outcomes of a particular experiment or activity.
* An **experiment** is a planned operation carried out under controlled conditions.
* If the result is not predetermined, then the experiment is said to be a **chance** experiment. Flipping one fair coin twice is an example of an experiment.

* A result of an experiment is called an **outcome**. The **sample space** of an experiment is the set of all possible outcomes.
* Three ways to represent a sample space are: to list the possible outcomes, to create a tree diagram, or to create a Venn diagram.
* The uppercase letter S is used to denote the sample space. For example, if you flip one fair coin, S = {H, T} where H = heads and T = tails are the outcomes.

* An **event** is any combination of outcomes. Upper case letters like A and B represent events. For example, if the experiment is to flip one fair coin, event A might be getting at most one head. The probability of an event A is written P(A).

* The **probability** of any outcome is the **long-term relative frequency** of that outcome. **Probabilities are between zero and one**, inclusive (that is, zero and one and all numbers between these values). P(A) = 0 means the event A can never happen. P(A) = 1 means the event A always happens. P(A) = 0.5 means the event A is equally likely to occur or not to occur. For example, if you flip one fair coin repeatedly (from 20 to 2,000 to 20,000 times) the relative frequency of heads approaches 0.5 (the probability of heads).

* **Equally likely** means that each outcome of an experiment occurs with equal probability. For example, if you toss a fair six-sided die, each face (1, 2, 3, 4, 5, or 6) is as likely to occur as any other face.

* To calculate the probability of an event A when all outcomes in the sample space are equally likely, count the number of outcomes for event A and divide by the total number of outcomes in the sample space.

* **Law of large numbers** which states that as the number of repetitions of an experiment is increased, the relative frequency obtained in the experiment tends to become closer and closer to the theoretical probability. Even though the outcomes do not happen according to any set pattern or order, overall, the long-term observed relative frequency will approach the theoretical probability.

### " ∪ " Event: The Union

An outcome is in the event A ∪ B if the outcome is in A or is in B or is in both A and B. For example, let A = {1, 2, 3, 4,
5} and B = {4, 5, 6, 7, 8}. A ∪ B = {1, 2, 3, 4, 5, 6, 7, 8}. Notice that 4 and 5 are NOT listed twice.

### " ∩ " Event: The Intersection

An outcome is in the event A ∩ B if the outcome is in both A and B at the same time. For example, let A and B be {1, 2,
3, 4, 5} and {4, 5, 6, 7, 8}, respectively. Then A ∩ B = {4, 5}.
The complement of event A is denoted A′ (read "A prime"). A′ consists of all outcomes that are NOT in A. Notice that P(A) + P(A′) = 1. For example, let S = {1, 2, 3, 4, 5, 6} and let A = {1, 2, 3, 4}. Then, A′ = {5, 6}. P(A) = 4/6 , P(A′) = 2/6 , and
P(A) + P(A′) = 4/6 + 2/6 = 1

### Conditional Probability

The conditional probability of A given B is written P(A | B). P(A | B) is the probability that event A will occur given that the event B has already occurred. **A conditional reduces the sample space.** We calculate the probability of A from the reduced sample space B. The formula to calculate P(A | B) is P(A | B) = P(A ∩ B) / P(B) where P(B) is greater than zero.

For example, suppose we toss one fair, six-sided die. The sample space S = {1, 2, 3, 4, 5, 6}. Let A = face is 2 or 3 and B = face is even (2, 4, 6). To calculate P(A | B), we count the number of outcomes 2 or 3 in the sample space B = {2, 4, 6}. Then we divide that by the number of outcomes B (rather than S).

We get the same result by using the formula. Remember that S has six outcomes.

P(A | B) = P(A ∩ B) / P(B) = (the number of outcomes that are 2 or 3 and even in S) / 6
/
(the number of outcomes that are even in S) / 6
= 1/6 / 3/6
= 1/3

## Odds

The odds of an event presents the probability as a ratio of success to failure. This is common in various gambling formats.

Mathematically, the odds of an event can be defined as:
P(A) / 1 − P(A)

where P(A) is the probability of success and of course 1 − P(A) is the probability of failure. Odds are always quoted as "numerator to denominator," e.g. 2 to 1. Here the probability of winning is twice that of losing; thus, the probability of winning is 0.66. A probability of winning of 0.60 would generate odds in favor of winning of 3 to 2. While the calculation of odds can be useful in gambling venues in determining payoff amounts, it is not helpful for understanding probability or
statistical theory.

## Understanding Terminology and Symbols

It is important to read each problem carefully to think about and understand what the events are. Understanding the wording is the first very important step in solving probability problems. Reread the problem several times if necessary. Clearly identify the event of interest. Determine whether there is a condition stated in the wording that would indicate that the probability is conditional; carefully identify the condition, if any.

## Independent Events

Two events are independent if one of the following are true:
• P(A|B) = P(A)
• P(B|A) = P(B)
• P(A ∩ B) = P(A)P(B)

Two events A and B are independent if the knowledge that one occurred does not affect the chance the other occurs. For example, the outcomes of two roles of a fair die are independent events. The outcome of the first roll does not change the probability for the outcome of the second roll. To show two events are independent, you must show only one of the above
conditions. If two events are NOT independent, then we say that they are dependent.

Sampling may be done with replacement or without replacement.

* **With replacement:** If each member of a population is replaced after it is picked, then that member has the possibility of being chosen more than once. When sampling is done with replacement, then events are considered to be independent, meaning the result of the first pick will not change the probabilities for the second pick.

* **Without replacement:** When sampling is done without replacement, each member of a population may be chosen only once. In this case, the probabilities for the second pick are affected by the result of the first pick. The events are considered to be dependent or not independent.

If it is not known whether A and B are independent or dependent, **assume they are dependent until you can show otherwise.**

## Mutually Exclusive Events

A and B are mutually exclusive events if they cannot occur at the same time. Said another way, If A occurred then B cannot
occur and vise-a-versa. This means that A and B do not share any outcomes and P(A ∩ B) = 0 .

If it is not known whether A and B are mutually exclusive, **assume they are not until you can show otherwise.**

**Independent and mutually exclusive do not mean the same thing.**

## Two Basic Rules of Probability

When calculating probability, there are two rules to consider when determining if two events are independent or dependent
and if they are mutually exclusive or not.

### The Multiplication Rule

If A and B are two events defined on a **sample space**, then: P(A ∩ B) = P(B)/P(A|B) . We can think of the intersection symbol as substituting for the word "and".

If A and B are **independent**, then P(A|B) = P(A) . Then P(A ∩ B) = P(A|B)P(B) becomes P(A ∩ B) = P(A)(B) because the P(A|B) = P(A) if A and B are independent.

It is harder to satisfy two conditions than only one and of course when we multiply fractions the result is always smaller.

### The Addition Rule

If A and B are defined on a sample space, then: P(A ∪ B) = P(A) + P(B) - P(A ∩ B) . We can think of the union symbol substituting for the word "or". The reason we subtract the intersection of A and B is to keep from double counting elements that are in both A and B.

If A and B are **mutually exclusive**, then P(A ∩ B) = 0 . Then P(A ∪ B) = P(A) + P(B) - P(A ∩ B) becomes P(A ∪ B) = P(A) + P(B) .

## Contingency Tables

A **contingency table** provides a way of portraying data that can facilitate calculating probabilities. The table helps in determining conditional probabilities quite easily.

## Tree Diagrams

A tree diagram is a special type of graph used to determine the outcomes of an experiment. It consists of "branches" that are labeled with either frequencies or probabilities. Tree diagrams can make some probability problems easier to visualize and solve.

## Venn Diagrams

A Venn diagram is a picture that represents the outcomes of an experiment. It generally consists of a box that represents the sample space S together with circles or ovals. The circles or ovals represent events. Venn diagrams also help us to convert common English words into mathematical terms that help add precision.

Venn diagrams are named for their inventor, John Venn, a mathematics professor at Cambridge and an Anglican minister.
