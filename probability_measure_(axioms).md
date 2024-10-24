# Probability measure (Axioms)

[[Probability space]] [[Properties of probability measure]] [[Distribution functions]]

Essentially the 3rd component of a probability space. This is defined by Axioms of probability
A probability measure P on (Ω, F) is a set of function with the domain F satisfying:
P(A) >= 0 for all A in F
P(Ω) = 1
For all pairwise disjoint Ai in F,  P(UAi) = ΣP(Ai)

P: F -> [0,1]

A probability measure operates over sets (events) rather than over individual outcomes.
The measure assigns probabilities to events (subsets of the sample space), but it doesn’t directly describe how these probabilities are distributed across individual points.
The sample space  Ω  represents all possible outcomes of a random experiment, and an event is a collection (subset) of one or more outcomes. The probability measure tells us how likely a given event is to occur.
For example, consider the experiment of rolling a die. The sample space is:
Ω = {1, 2, 3, 4, 5, 6}

A possible event could be “rolling an even number”, which corresponds to the subset  {2, 4, 6} . The probability measure might assign a probability of  1/2 to this event.

In contrast a [[Distribution Functions]] defines how probabilites are distributed over the Random variable of Ω. e.g. P(X≤2) = 1/3

Why the distinction is important:
A probability measure on its own describes the likelihood of events, not how the probability is distributed within those events.
To describe how probability is distributed across individual outcomes (points) in a more detailed manner, you use concepts like a probability distribution or probability density function (PDF) for continuous variables, which give you more granular information about how probability is assigned across individual points.


In a continuous probability space, assigning probabilities to individual outcomes doesn’t usually make sense. For example, if you’re measuring the exact height of a person (a continuous variable), the probability of measuring exactly 170.000000… cm is effectively 0. Instead, the probability measure assigns probabilities to intervals (sets of possible outcomes), such as the probability that the height is between 170 and 171 cm. This is why in continuous spaces, probability measures focus on sets (like intervals) rather than individual points.

A probability measure underpins the entire probability space, ensuring that the axioms of probability are satisfied.

#classnotes #psm #probability #ch1 #appliedstats
